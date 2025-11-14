# Leadership – Delivering WPA3 to Unlock 6 GHz at InfoComm

> **Question:** Describe a time when you set a goal and how to achieve it.

## Situation
Ahead of the InfoComm showcase, I wanted ClickShare to operate in the 6 GHz band so we could demo interference-free wireless sharing alongside dozens of other vendors. Industry compliance rules, however, require WPA3 before 6 GHz can be enabled, and we hadn’t implemented or validated it yet.

## Task
My goal was to deliver WPA3 end-to-end—spec, implementation, and automation—so we could safely enable 6 GHz in the field without any compliance issues or demo risk.

## Action
- Aligned with the product owner on the requirement, demo deadline, and success criteria so the entire team knew 6 GHz enablement depended on WPA3 being production-ready.
- Pulled the WPA3 specifications, confirmed the exact security and onboarding requirements, and translated them into actionable stories for supplicant, AP, and system-level changes.
- Guided the implementation by pairing with the engineer building the wpa_supplicant automation, reviewing the design, and standing up regression scripts that proved WPA3 handshake reliability across our devices.

## Result
We delivered WPA3 support on schedule, enabled 6 GHz for InfoComm, and ran the event demos without bandwidth or latency issues despite the congested environment. Sales showcased the smooth 6 GHz experience to prospects, reinforcing our innovation message.

**Interview Takeaway:** I achieve ambitious goals by clarifying the requirement, mastering the technical detail, and driving the implementation through to proof so the capability lands exactly when it’s needed.
