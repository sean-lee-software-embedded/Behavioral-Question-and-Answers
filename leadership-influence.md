# Leadership – Influencing Quality Standards Across Sites

## Situation
When I inherited Barco’s ClickShare connectivity team, our Belgian headquarters and Taiwan development hub used different quality bars. HQ was piloting SonarQube with ≥90% unit test coverage, while the Taiwan team focused on integration tests. Executives asked me to “get everyone aligned,” but neither site wanted to adopt the other’s process.

## Task
As the new team lead, I needed to influence both sites to converge on a single quality standard that kept velocity intact while satisfying HQ’s compliance targets.

## Action
- Analyzed failure data from Jenkins and mapped each incident to the layer that caught it (unit vs. integration), building a neutral fact base that showed gaps on both sides.
- Hosted a joint technical review with engineers from both regions, walking through the data and highlighting which defects unit tests would have prevented and where integration tests still provided unique coverage.
- Proposed a blended standard: SonarQube gating with 90% coverage on critical modules plus daily integration smoke tests. I volunteered to own the transition plan, including tooling support and training.
- Piloted the approach on the Qualcomm Wi-Fi driver subsystem, pairing developers across sites, capturing lessons learned, and reporting progress in the VP’s weekly review so leadership saw transparent metrics rather than opinions.

## Result
Within two sprints, both sites hit the new SonarQube gate without missing sprint commitments, and escaped defects on the Wi-Fi subsystem dropped noticeably. HQ leadership adopted the blended standard as the template for other ClickShare teams, and engineers across regions credited the shared data and pilot for making the change easier to accept.

**Interview Takeaway:** I influence across teams by grounding the conversation in shared data, co-creating a path forward, and proving the value through a transparent pilot rather than top-down mandates.
