# Creativity – Delivering Real-Time 4K Sharing on New Silicon

## Situation
Barco’s roadmap called for 4K wireless screen sharing on a new MediaTek Genio-700 platform, but our existing ClickShare pipeline only supported 1080p. We had tight demo commitments for an executive roadshow, and the hardware integration team flagged bandwidth and latency risks that could cancel the launch.

## Task
I needed to prove that the platform could handle low-latency 4K streaming without a full production rewrite. The demo had to be stable enough for leadership to greenlight continued investment and for sales to start positioning the feature with key customers.

## Action
- Built a proof-of-concept around GStreamer with hardware encode/decode, using EDID-driven mode selection to negotiate the best resolution per endpoint and avoid overrunning USB-C/DisplayPort Alt Mode limits.
- Tuned Wi-Fi 6E configurations (channel selection, DBS/HBS mode) and leveraged QoS tagging plus PID-based throttling on the Qualcomm radio to balance throughput and thermals.
- Added on-the-fly monitoring hooks to capture frame drops, congestion, and thermal data, streaming the metrics into Grafana so we could iterate quickly with RF and hardware teams.
- Packaged the PoC into a repeatable demo image with scripts and documentation so product marketing and sales engineering could run it without developer support.

## Result
The demo ran cleanly in the executive roadshow, earning approval to productize the feature and informing the final architecture for 4K content sharing. The monitoring toolkit we built became part of our standard performance test suite.

**Interview Takeaway:** I combine deep technical experimentation with pragmatic tooling so creative solutions move from “hack” to repeatable capability quickly.
