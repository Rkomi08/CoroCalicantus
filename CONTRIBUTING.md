# Contributing Guidelines

Welcome to the project! This document outlines our team workflow and guidelines for contributing. By following these processes, we ensure smooth collaboration across design, development, content, and quality assurance. 

Because we all share documentation responsibilities, keeping this repository organized is a collective effort.

## Team Roles & Responsibilities

To streamline our workflow and ensure clear communication, please reference our core roles. Tag the appropriate team member(s) when opening an Issue or Pull Request (PR) or when passing a phase in our waterfall process.

* **Mirko Castorina – Team Leader / Project Coordinator / Front-end Developer / Documentation:** Drives project momentum, manages front-end development, oversees project documentation, and resolves blockers. Provides final approval for merges into the `main` branch.
* **Robert Concal – Developer / Designer / GitHub Manager / Documentation:** Leads UI/UX design (Figma), creates graphic assets (stored in `assets/`), manages GitHub repository settings/architecture, develops core application code (`src/`), and maintains technical documentation.
* **Federico Pedretti – Content & Layout Specialist / Back-end Developer / Documentation:** Architects the back-end infrastructure, manages site copy and structural layout strategy, and ensures documentation aligns with technical implementations.
* **Martino Sandri – Quality Assurance & Testing / Front-end Developer / Documentation:** Builds front-end features alongside K, manages rigorous manual and secure testing, and ensures all code meets design and quality standards before it goes live.

## Project Lifecycle (Waterfall Strategy)

We follow a structured waterfall analysis scheme to ensure quality and alignment before coding begins. 

1. **Phase 1: Documentation & Planning:** Defining requirements, structuring the architecture, and outlining site copy (All team members).
2. **Phase 2: Design & Prototyping:** UI/UX wireframing and high-fidelity mockups in Figma (Led by X, supported by Y).
3. **Phase 3: Building:** Translating designs into code, setting up the back-end, and building out the front-end (K, X, Y, Z).
4. **Phase 4: Secure Testing & QA:** Rigorous manual checks, bug hunting, and security validation before final deployment (Led by Z).
5. **Phase 5: Final Deployment:** Pushing the verified, production-ready codebase to our live environment and monitoring for stability.

## Branching Strategy

We use a highly collaborative feature-branch workflow to build and test pages safely. 

1. **`main`**: The stable, unified source for our project. Everything eventually goes into `main`, but only *after* we collaborate, review, and manually verify the changes. **Never push unverified code directly to `main`.**

## Contribution Workflow

### 1. Sync and Branch
Always ensure you have the latest updates from the team before starting new work:
```bash
git checkout main
git pull origin main
git checkout -b your-branch-name