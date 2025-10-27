# Problem Solving – Cutting Release-Blocking Defects at Barco

## Situation
In 2022, my ClickShare scrum team at Barco faced a surge in release-blocking bugs coming from both in-house development and an ODM partner. Each release was slipping by one to two sprints, we were burning engineer time in late-cycle triage, and leadership was considering feature freezes to protect schedules.

## Task
As the embedded software team lead, I needed to restore delivery predictability without halting roadmap commitments. That meant identifying the systemic causes behind the defects, aligning internal and external teams on a fix plan, and delivering measurable quality improvements before the next quarterly release gate.

## Action
- Set up a joint Barco/ODM defect review cadence, introduced 5-Why root-cause templates, and required every bug to land with an owner, containment plan, and time-bound corrective action.
- Rebuilt our quality dashboards in Jenkins/Grafana so we could trace defects back to the originating component and sprint, giving product and QA real-time visibility during portfolio reviews.
- Paired engineers across sites on the thorniest driver and middleware issues, ran focused debug sessions with Qualcomm, and captured the learnings into playbooks that fed onboarding and code reviews.
- Formalized entry/exit criteria for each sprint, including automated smoke-test gates and a “no new critical bug” rule before backlog grooming closed.

## Result
Within one quarter we cut release-blocking defects by roughly 71%, recovered two lost sprints, and avoided the feature freeze. The stronger quality discipline improved trust with leadership, which allowed us to keep roadmap scope intact while still shipping a factory-qualified release.

**Interview Takeaway:** I combine structured root-cause analysis with cross-team alignment so the fixes stick, the data stays visible, and the team keeps shipping at pace.
