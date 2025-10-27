# Conflict Management – Aligning Redfish Vendors and Internal Stakeholders

## Situation
At Quanta, I managed the Redfish management controller program during a major platform refresh. We relied on an external firmware vendor, but their implementation choices clashed with our server PMO’s roadmap and our hardware team’s security requirements. Tensions escalated in weekly reviews, threatening both the delivery date and the supplier relationship.

## Task
My mandate was to get everyone back on the same page: keep the vendor engaged, protect Quanta’s platform requirements, and ensure we still hit the customer delivery window.

## Action
- Ran a reset workshop with engineering, PMO, security, and the vendor to surface each blocker, separate facts from assumptions, and capture non-negotiables versus “nice to haves.” This de-escalated the emotion and gave us a shared action log.
- Broke the debate into three decision tracks (schema compliance, security posture, and schedule), assigned a Quanta owner for each, and scheduled focused working sessions rather than trying to solve everything in the general status call.
- Authored a joint technical specification that mapped our requirements to the Redfish schema, highlighted implementation gaps, and proposed design patterns the vendor could adopt without rewriting their codebase.
- Instituted a bi-weekly executive checkpoint where I presented data on test pass rates, open risks, and mitigation plans, making trade-offs transparent and preventing last-minute surprises.

## Result
We resolved the conflicts without replacing the vendor, achieved an on-time firmware delivery, and shipped with a compliant and secure Redfish stack. The conflict-management framework became our template for future ODM collaborations.

**Interview Takeaway:** I defuse conflict by getting the right people focused on shared facts, carving the problem into solvable pieces, and keeping leadership aligned on trade-offs.
