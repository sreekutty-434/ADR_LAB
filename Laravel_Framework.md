**ADR 1**: Choosing Laravel as the Backend Framework

**Issue:** Need an MVC framework with authentication, security & scalability.
**Decision:** Laravel chosen for its MVC structure, ORM (Eloquent), authentication, and community support.
**Constraints:** Requires Composer, extra config for high performance.
**Positions:** Laravel (✔), Symfony (complex), CodeIgniter (lacks ORM), Plain PHP (repetitive).
**Implications:** Learn Laravel conventions, optimize for performance, manage dependencies with Composer.
**Related:** PHP backend, MySQL database.
**ADR 2:** Using HTML & Blade for Frontend

**Issue:** Need a templating system that integrates with Laravel.
**Decision:** HTML + Blade for reusable templates and simple integration.
**Constraints:** Requires Laravel, may need CSS/JS frameworks.
**Positions:** Blade (✔), React (API-based), Vue (adds complexity).
**Implications:** Use Tailwind/Bootstrap for styling, consider Alpine.js for interactivity.
**Related:** Laravel backend, PHP language.
**ADR 3:** Using PHP as Backend Language

**Issue:** Need a server-side language for business logic & API requests.
**Decision:** PHP chosen for Laravel compatibility and community support.
**Constraints:** Slower than compiled languages, requires optimization.
**Positions: ** PHP (✔), Node.js (fast, different stack), Python (AI-focused).
**Implications:** Optimize code, use PHP 8.x for performance.
**Related:** Laravel backend.
**ADR 4:** Using MySQL as Database

**Issue:** Need a relational database for courses, users, and bookings.
**Decision:** MySQL selected for performance and Laravel compatibility.
**Constraints:** Requires indexing for efficiency.
**Positions:** MySQL (✔), PostgreSQL (advanced but overkill).
**Implications:** Implement backup and indexing strategies.
**Related:** Laravel backend.
**ADR 5:** Using GitHub for Version Control

**Issue:** Need version control for collaboration and CI/CD.
**Decision:** GitHub chosen for repo hosting and GitHub Actions.
**Constraints:** Requires Git workflow understanding.
**Positions:** GitHub (✔), GitLab (self-hosted, more setup).
**Implications:** Enforce PR-based workflows.
**Related:** Azure deployment.
**ADR 6:** Using Azure for Cloud Hosting

**Issue:** Need scalable cloud hosting with CI/CD integration.
**Decision:** Azure chosen for GitHub integration and Laravel support.
**Constraints:** Costs may rise with usage.
**Positions:** Azure (✔), AWS (more features, complex pricing).
**Implications:** Monitor costs, optimize for scalability.
**Related:** GitHub version control.
