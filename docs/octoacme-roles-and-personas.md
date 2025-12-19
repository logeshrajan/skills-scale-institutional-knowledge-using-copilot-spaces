# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons serve as the primary bridge between project teams and external stakeholders. They collect requirements, relay feedback, and ensure stakeholder perspectives are represented in project decisions.

### Responsibilities
- Gather and clarify stakeholder requirements and expectations
- Communicate project updates and changes to stakeholders
- Coordinate stakeholder input for decision-making processes
- Facilitate stakeholder meetings and feedback sessions
- Translate business needs into actionable project requirements
- Escalate stakeholder concerns to Project Managers and Product Managers

### Goals
- Maintain strong stakeholder relationships and trust
- Ensure stakeholder needs are clearly understood and documented
- Minimize misalignment between stakeholder expectations and project delivery
- Facilitate timely stakeholder approvals and decision-making

### Typical Communication
- Regular stakeholder briefings and status updates
- Requirements gathering sessions
- Feedback collection and synthesis reports
- Stakeholder meeting minutes and action items

### Interaction Examples
**With Process Owners:** Stakeholder Liaisons work closely with Process Owners to ensure stakeholder feedback is incorporated into process refinements. For example, when stakeholders report confusion about deployment timelines, the Liaison coordinates with the Process Owner to update the Release & Deployment documentation with clearer communication procedures.

**With Product Managers:** They collaborate to validate that stakeholder requirements align with product vision. When a stakeholder requests a feature that conflicts with the roadmap, the Liaison facilitates a meeting between the stakeholder and Product Manager to discuss trade-offs and priorities.

**With Project Managers:** They coordinate to ensure project plans reflect stakeholder commitments. If a stakeholder changes availability for a critical review, the Liaison immediately informs the Project Manager to adjust the schedule and mitigate risks.

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads establish and maintain quality standards across projects. They design QA processes, review deliverables, and ensure all work meets defined acceptance criteria before release.

### Responsibilities
- Define quality standards and acceptance criteria for deliverables
- Design and maintain QA processes and testing strategies
- Review code, documentation, and project artifacts for quality
- Coordinate testing cycles and bug triage processes
- Mentor team members on quality best practices
- Track quality metrics and identify improvement opportunities

### Goals
- Maintain high quality standards across all deliverables
- Prevent defects from reaching production
- Reduce rework and technical debt
- Foster a culture of quality throughout the team

### Typical Communication
- Test plans and QA strategy documents
- Bug reports and quality metrics dashboards
- Code review feedback and testing guidelines
- Quality retrospective summaries

### Interaction Examples
**With Reviewers:** QA Leads define the review criteria that Reviewers use when evaluating pull requests and documentation. They might create a checklist that Reviewers follow, ensuring consistent quality standards. For instance, the QA Lead ensures Reviewers check for test coverage before approving code changes.

**With Contributors:** They provide guidance on quality expectations before work begins. When a Contributor proposes a new feature, the QA Lead outlines testing requirements, edge cases to consider, and documentation standards that must be met.

**With Developers:** They collaborate throughout the development cycle, participating in design reviews to identify testability concerns early. During a sprint, the QA Lead might pair with a Developer to create automated tests for a complex feature, ensuring quality is built in from the start.

---

## Onboarding Coordinator

### Role Summary
Onboarding Coordinators manage the knowledge transfer process for new team members. They ensure documentation-driven onboarding is smooth, comprehensive, and continuously improved based on feedback.

### Responsibilities
- Maintain and update onboarding documentation and checklists
- Coordinate new hire orientation and training schedules
- Pair new team members with mentors or buddies
- Collect feedback from new hires to improve the onboarding process
- Ensure access to necessary tools, systems, and documentation
- Track onboarding progress and identify blockers

### Goals
- Reduce time-to-productivity for new team members
- Ensure consistent onboarding experiences across all hires
- Maintain current and comprehensive onboarding materials
- Create a welcoming and supportive onboarding culture

### Typical Communication
- Onboarding checklists and welcome documentation
- Training schedules and resource guides
- New hire feedback surveys and improvement reports
- Mentor pairing notifications and progress updates

### Interaction Examples
**With Knowledge Curators:** Onboarding Coordinators work with Knowledge Curators to ensure onboarding materials are discoverable and current. They might request that key process documents be added to Copilot Spaces with beginner-friendly annotations, making them more accessible to new hires.

**With Project Managers:** They coordinate to schedule new hire participation in projects appropriately. When onboarding a new Developer, the Coordinator works with the Project Manager to identify suitable starter tasks that provide learning opportunities without overwhelming the new team member.

**With All Roles:** The Onboarding Coordinator interfaces with every role to create comprehensive onboarding materials. They might shadow a Product Manager to document their workflow, interview Developers about common pitfalls, and observe Stakeholder Liaisons to understand communication patterns, then synthesize this into onboarding guides.

---

## Change Champion

### Role Summary
Change Champions drive the adoption of process improvements and cultural changes within the organization. They gather insights from retrospectives, advocate for new practices, and help teams navigate transitions.

### Responsibilities
- Facilitate retrospective sessions and capture lessons learned
- Identify opportunities for process improvement across teams
- Advocate for adoption of new tools, practices, and workflows
- Create awareness campaigns for process changes
- Monitor adoption metrics and address resistance
- Celebrate successes and share improvement stories

### Goals
- Foster a culture of continuous improvement and learning
- Ensure process changes are adopted effectively
- Minimize disruption during organizational changes
- Increase team engagement in improvement initiatives

### Typical Communication
- Retrospective summaries and action item tracking
- Change management plans and adoption roadmaps
- Success stories and improvement case studies
- Training materials for new practices and tools

### Interaction Examples
**With All Roles (Process Owners, Curators, Contributors, Reviewers):** Change Champions connect with every role to understand pain points and champion improvements. After retrospectives reveal that documentation reviews are taking too long, the Change Champion works with Process Owners to streamline the review process, with Knowledge Curators to improve discoverability, and with Reviewers to establish review timeframes.

**With Project Managers:** They collaborate to integrate process improvements into project workflows. When introducing a new risk management tool, the Change Champion partners with Project Managers to pilot it on one project, gather feedback, and create adoption plans for other teams.

**With Developers and Product Managers:** They facilitate the adoption of new development practices. If retrospectives show that teams want to improve release planning, the Change Champion organizes workshops where Product Managers and Developers co-create improved release templates, then tracks adoption across teams.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded set of personas addresses key gaps:
  - Cross-functional engagement and stakeholder communication
  - Quality assurance and review processes
  - Onboarding and knowledge transfer
  - Continuous improvement and change adoption

