# Conflict Management – Driving a Cross-Functional Thermal War Room

## Situation
On a new ClickShare platform, we discovered catastrophic thermal failures: a high-performance SoC squeezed into a compact chassis overheated whenever we ran sustained 4K encode/decode. Hardware wanted copper heat spreaders, mechanics argued for a taller enclosure, HQ product management refused to change the industrial design, software debated aggressive throttling, the Wi-Fi vendor pushed radio tweaks, and our ODM insisted their lab conditions were already optimal. The debate stalled progress and risked derailing the NPI schedule.

## Task
As Barco’s embedded lead on site with the ODM, I had to break the stalemate, align every stakeholder, and find a cross-discipline solution that would pass thermal validation without compromising the device aesthetics or the launch timeline.

## Action
- Established a daily “thermal war room” at the ODM with representatives from hardware, mechanical design, firmware, the Wi-Fi chip vendor, and the ODM lab so decisions happened in real time.
- Reviewed each 4K stress test report together, dissecting power draws, temperature ramps, and MCS rates to understand how each lever—copper spreads, enclosure height, throttling trip points, core counts, transmit power, and lab air quality—affected headroom.
- Drove rapid experiments: mechanics trialed a 0.5 cm internal standoff for airflow without changing the exterior lines, firmware tuned thermal trip points and big.LITTLE core usage, the Wi-Fi vendor supplied alternate BDF and Green Tx profiles, and the ODM validated clean-room setups to keep link quality at MCS-8/9 so we could lower TX power safely.
- Consolidated the winning combination into an engineering change package, documented the thermal budget assumptions, and presented it to HQ PM and NPI leadership to secure approval for DVT2.

## Result
The blended fix passed the thermal test criteria with margin, unblocking DVT2 and keeping NPI on schedule. Each team saw their contribution reflected in the outcome, which defused the conflict and gave HQ confidence in the production plan.

**Interview Takeaway:** When multiple disciplines clash, I put everyone in the same room, anchor decisions in shared data, and iterate quickly until we have a solution each stakeholder can stand behind.
