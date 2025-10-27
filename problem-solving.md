# Problem Solving – Cutting Release-Blocking Defects at Barco

## Situation
In 2022, our ClickShare ODM partner was shipping firmware drops with a spike in release-blocking defects. Their builds routinely failed our acceptance tests, leadership was questioning the supplier relationship, and we had to reject multiple releases to protect production devices.

## Task
As the embedded software lead for Barco, I needed to get the external ODM back to SLA compliance. That meant aligning their engineering leadership on root causes, setting clear expectations for defect turnaround, and restoring confidence in their release readiness.

## Action
- Introduced a 5-Why root-cause template that the ODM had to complete for every SLA breach, and ran the first few sessions myself to set the bar for rigor.
- Tightened the SLA language to include turnaround time on fixes, mandatory regression evidence, and escalation paths when the same root cause resurfaced.
- Rejected non-compliant releases, walked their QA and release managers through our expectations, and built a diagnostic checklist they could follow before shipping the next build.

## Result
After coaching the ODM through the new review process and turning away unqualified drops, they cut release-blocking defects by roughly 71%. Their release quality stabilized, we stopped burning time on emergency triage, and the supplier relationship moved back into good standing.

**Interview Takeaway:** I combine structured root-cause analysis with cross-team alignment so the fixes stick, the data stays visible, and the team keeps shipping at pace.
