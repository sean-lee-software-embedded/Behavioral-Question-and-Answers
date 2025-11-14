# Leadership – Influencing Cross-Teams to Resolve a 4AXES Production Failure

> **Question:** Describe a time you showed your leadership to influence people.

## Situation
During a recent 4AXES production run, the factory reported few USB loopback failures even though earlier qualification tests had passed. The root cause was unknown, and the quality manager worried we would miss shipment targets without a clear answer.

## Task
As the on-site software lead, I needed to align factory test, HQ team, ODM reliability, NPI, quality, and hardware teams to identify the root cause quickly and recommend a safe production path.

## Action
- Collected and analyzed all loopback logs from the line, highlighting the failure pattern and framing hypotheses so each team focused on the same evidence.
- Partnered with the HQ firmware group to build a custom diagnostic image that emitted deeper loopback telemetry; this let us reproduce the fault with actionable data instead of deassembling the hardware while the condition may disappear.
- Directed the ODM to run accelerated thermal tests, including camera FPS monitoring, and ensured their results fed directly into our debug sessions.
- Briefed NPI and the quality manager daily, explaining the failure mode, quantifying risk, and aligning on interim actions so operations could plan with confidence.
- After software analysis suggested the platform was stable post-reboot, synced with the hardware engineer to inspect the physical layer. Together we used our loopback script plus an extension cable to amplify marginal conditions, which exposed cracked USB cables that degraded signal strength.

## Result
We recommended a temporary software workaround that rebooted the platform after the first detected failure while the line replaced affected cables. The enhanced loopback test became the screening tool that quickly flagged any degraded harnesses. Leadership gained confidence that both software and hardware angles were covered, and production stayed on schedule.

**Interview Takeaway:** I influence cross-functional teams by anchoring everyone on shared data, accelerating diagnostics with tailored tooling, and closing the loop with each stakeholder until we have both a short-term fix and the clear root cause.
