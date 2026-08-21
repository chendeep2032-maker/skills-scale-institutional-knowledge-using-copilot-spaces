# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a structured, customer-first project management methodology focused on iterative delivery, clear ownership, and data-informed decisions. This documentation centralizes our processes, roles, and best practices to enable consistent, repeatable project execution across the organization.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

1. **Initiation** → Define problem, stakeholders, timeline
2. **Planning** → Break work into shippable increments
3. **Execution** → Build, test, review, iterate
4. **Release** → Deploy, verify, announce
5. **Close & Retrospective** → Capture learnings

## OctoAcme Project Management Approach

### Foundational Approach and Principles

OctoAcme operates on a customer-first, iterative delivery model grounded in five core principles: prioritizing customer value and usability, delivering small testable increments, maintaining clear ownership through designated Project Managers and Product Leads, making data-informed decisions, and fostering psychological safety through open feedback. The project lifecycle follows a structured five-phase approach: Initiation (validating business need and aligning stakeholders), Planning (breaking work into shippable increments with clear acceptance criteria), Execution (building, testing, and iterating in daily standups and sprints), Release (deploying to production with pre-release verification), and Close & Retrospective (capturing learnings and driving continuous improvement). This framework ensures that every project moves intentionally from conception through delivery with consistent governance and stakeholder alignment.

### Roles, Responsibilities, and Communication Cadence

Three core personas drive OctoAcme projects: Product Managers define what should be built to maximize customer and business value through prioritization and success metrics; Project Managers coordinate delivery, manage schedules, risks, and cross-team dependencies while maintaining transparency; and Developers design, build, test, and collaborate on implementing features that meet acceptance criteria. The communication rhythm is structured and consistent—daily standups (15 minutes) focus on progress and blockers, weekly delivery syncs track progress and flag risks, weekly PM-to-PdM alignment meetings ensure coordination, and monthly stakeholder updates provide visibility. This cadence ensures rapid issue identification while maintaining clear escalation paths: Level 1 (team-level triage in standups), Level 2 (PM escalates to Product Lead and dependent teams), and Level 3 (sponsor-level escalation for business-critical issues).

### Execution, Quality, and Risk Management

Execution follows disciplined workflows anchored in GitHub Projects boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and small, focused pull requests (≤ 400 lines). Before merging, all changes must pass automated tests, linting, and security scanning in CI, require at least one code review approval, and include clear acceptance criteria and issue links. Quality assurance is comprehensive: unit tests validate new logic, integration tests verify component interactions, end-to-end smoke tests confirm critical flows before release, security scanning runs in CI, and manual QA ensures feature acceptance when needed. Risk management is proactive—risks are identified during planning and execution, assessed for impact and likelihood, mitigated through documented contingency plans, and monitored weekly. A Risk Register tracks each issue (ID, description, impact, probability, owner, mitigation, status), enabling teams to surface dependencies and escalate cross-team blockers during weekly syncs before they derail delivery.

### Release, Learning, and Continuous Improvement

Releases are standardized and traceable through a defined checklist: all acceptance criteria must be met, CI/security scans must pass, release notes must be drafted, rollback plans documented, and smoke tests prepared. Release types are classified as Patch (hotfixes), Minor (incremental features), or Major (significant functionality or breaking changes), with clear communication to stakeholders and support teams upon deployment. Post-release, OctoAcme captures learnings through structured retrospectives held after each sprint, release, or milestone, using anonymous idea boards when needed to encourage candor. Retrospectives follow a consistent format (what went well, what could improve, action items with owners and due dates) and timebox to 45–75 minutes to maintain focus. These action items flow back into the project backlog or as GitHub issues with clear owners and timelines, with progress reviewed in weekly PM syncs, closing the feedback loop and embedding continuous improvement into the culture.

## Process Documents

### Foundation & Overview

- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** - Start here for a concise introduction to our approach, roles, and key artifacts
- **[OctoAcme Roles & Personas](octoacme-roles-and-personas.md)** - Understand responsibilities and communication patterns for Developers, Product Managers, and Project Managers

### Project Phases

- **[Project Initiation Guide](octoacme-project-initiation.md)** - Validate business need, align stakeholders, create initial plan
- **[Project Planning](octoacme-project-planning.md)** - Turn approved initiatives into actionable backlog and delivery plan
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Manage day-to-day execution, team rhythm, and progress tracking
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** - Standardize feature releases and production deployments
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and convert to actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Identify, manage, and communicate risks, dependencies, and stakeholder updates

## Issue Templates

When creating work related to process improvements, use the appropriate template:

- **[Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** - Submit updates or new content for process documentation

## How to Use This Documentation

1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the path: Initiation → Planning → Execution → Release → Retrospective
3. **Need help with a specific concern?** Check Risk Management & Communication or the specific phase document
4. **Want to improve our processes?** Use the issue template to propose updates

## Navigation

All documents use consistent terminology and cross-reference each other. Each document includes:

- **Purpose**: Why the document exists
- **When to use**: The appropriate phase or scenario
- **Checklists**: Actionable steps to ensure nothing is missed
- **Templates**: Sample formats and examples

## Contributing

OctoAcme's project management practices evolve with team feedback and experience. To suggest improvements or clarifications, open an issue using the [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

---

**Last Updated**: 2026-08-21
