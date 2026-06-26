# Software Development Lifecycle (SDLC)

The Software Development Lifecycle (SDLC) is a structured process used by software
engineering teams to plan, design, build, test, deploy, and maintain software systems.
It provides a repeatable framework that ensures software is delivered on time, within
budget, and meets the required quality standards.

Phases of the SDLC

1. Planning
The project is defined at this stage. Teams identify the scope, goals, timeline,
resources, and risks involved. Key questions answered here include: What problem are
we solving? Is it feasible? What will it cost?

Outputs: Project plan, feasibility study, resource allocation

2. Requirements Analysis
Stakeholders and developers work together to gather and document exactly what the
system must do. Requirements are classified as functional (what the system does) or
non-functional (how the system performs — speed, security, scalability).

Outputs: Software Requirements Specification (SRS) document

3. System Design
The requirements are translated into a blueprint for the system. This includes
architecture design, database design, UI/UX design, and technology stack decisions.

Outputs: System design document, architecture diagrams, data models

4. Implementation (Coding)
Developers write the actual code based on the design documents. This is typically
broken into modules or features and worked on by different team members simultaneously.

Outputs: Source code, unit tests

5. Testing
The software is tested against the requirements to identify bugs, performance issues,
and security vulnerabilities. Types of testing include unit testing, integration
testing, system testing, and user acceptance testing (UAT).

Outputs: Test reports, bug reports, sign-off from QA

6. Deployment
The tested software is released to the production environment where real users can
access it. Deployment can be done all at once (big bang) or gradually (phased rollout
or canary release).

Outputs: Live system, deployment documentation, release notes

7. Maintenance
After deployment, the software is monitored for bugs, performance issues, and new
requirements. Updates, patches, and new features are released through subsequent
SDLC cycles.

Outputs: Patches, updates, performance reports

## How the Phases Relate

Each phase feeds directly into the next:
- Poor planning leads to unclear requirements
- Unclear requirements lead to flawed design
- Flawed design leads to buggy code
- Buggy code that isn't properly tested reaches real users
- Poor deployment practices cause downtime and data loss
- Skipping maintenance causes systems to degrade over time

SDLC is not always linear. Modern teams use Agile to iterate through these
phases in short cycles called sprints, delivering working software incrementally
rather than all at once.

## Key Takeaway

SDLC exists to bring order to the complexity of building software. Without it,
teams risk building the wrong thing, over budget, with poor quality. Understanding
SDLC is foundational to working effectively in any engineering team.