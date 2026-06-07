# Roadmap

This roadmap organizes OpenSource for Humans' development into phases, epics, and smaller tasks that can be distributed to contributors on GitHub.

It should be used as the basis for GitHub milestones, issues, discussions, RFCs, and project boards. The goal is not only to list features, but to help an open source community build the product without violating the project's mission, privacy rules, security requirements, governance model, or data policies.

## Core Rule

People seeking help are never the product.

At the initial stage, the platform must not store server-side personal data from people seeking help or general visitors. If statistics are needed, they must be anonymized and aggregated before storage.

## How to Use This Roadmap on GitHub

## Milestones

Each phase in this document should become a milestone:

- `phase-0-foundation`
- `phase-1-local-mvp`
- `phase-2-public-launch`
- `phase-3-organizations`
- `phase-4-safe-ai`
- `phase-5-local-chapters`
- `phase-6-ecosystem`

## Epics

Each epic section can become a parent issue with a checklist or a pinned discussion.

Suggested format:

`[Epic] Phase 1 - Service search and listing`

## Issues

Each candidate task should become a small issue with clear scope and acceptance criteria.

Suggested format:

`[area/frontend] Build mobile search form`

## Suggested Labels

Type:

- `type/feature`
- `type/bug`
- `type/docs`
- `type/research`
- `type/design`
- `type/data`
- `type/security`
- `type/privacy`
- `type/governance`
- `type/rfc`

Area:

- `area/frontend`
- `area/backend`
- `area/admin`
- `area/docs`
- `area/product`
- `area/data-model`
- `area/data-quality`
- `area/accessibility`
- `area/i18n`
- `area/search`
- `area/devops`
- `area/security`
- `area/privacy`
- `area/ai`
- `area/governance`
- `area/community`
- `area/local-chapters`
- `area/funding`

Priority:

- `priority/p0-critical`
- `priority/p1-high`
- `priority/p2-medium`
- `priority/p3-low`

Effort:

- `effort/xs`
- `effort/s`
- `effort/m`
- `effort/l`
- `effort/xl`

Contribution:

- `good-first-issue`
- `help-wanted`
- `needs-maintainer`
- `needs-data-review`
- `needs-legal-review`
- `needs-design-review`
- `needs-security-review`
- `blocked`

## Definition of Ready

An issue is ready to be worked on when it has:

- a clear objective;
- enough context;
- affected files or areas;
- acceptance criteria;
- privacy, security, or social impact risks;
- known dependencies;
- correct labels;
- scope small enough for one person to contribute.

## Definition of Done

An issue should only be considered done when:

- acceptance criteria are met;
- tests or manual validation are documented;
- relevant documentation is updated;
- no unnecessary personal data collection is introduced;
- LGPD + GDPR/RGPD rules are respected;
- sensitive flows have human review when needed;
- interface changes are verified on mobile;
- data changes have source and verification status;
- critical changes have maintainer review.

## Contribution Roles

## Technical Contributor

Works on frontend, backend, infrastructure, tests, security, accessibility, automation, and internal tooling.

## Data Contributor

Maps services, reviews sources, identifies duplicates, confirms status, improves taxonomy, and reports inconsistencies.

## Design Contributor

Creates flows, prototypes, interface copy, accessibility improvements, mobile-first experiences, and simple journeys for people with low digital familiarity.

## Documentation Contributor

Improves guides, policies, translations, examples, templates, decisions, and materials for local chapters.

## Technical Maintainer

Reviews architecture, security, code quality, deployment, tests, and technical decisions.

## Data Maintainer

Reviews published data, sources, reports, changes, and verification queues.

## Community Council

Decides critical changes involving mission, privacy, funding, sensitive AI, open data, and strategic partnerships.

## Non-Negotiable Principles

Every roadmap phase must respect:

- searching for help without mandatory login;
- no fees for people seeking help;
- no sale of personal data;
- no paid priority in essential help results;
- no server-side storage of user personal data at the initial stage;
- statistics only in anonymized and aggregate form;
- sensitive data avoided by default;
- approximate location whenever possible;
- Brazilian LGPD and European GDPR/RGPD applied together, with the more protective rule prevailing;
- service data with source, status, and last verification date;
- community suggestions, scraping, or AI always reviewed by humans before publication;
- AI as support, not final authority;
- probabilistic language for eligibility;
- accessibility and mobile-first design;
- transparency in relevant decisions.

## Phase 0: Foundation

Milestone: `phase-0-foundation`

Goal: prepare the project to receive contributors with safety, clarity, governance, and initial scope.

Expected outcome: a community can open issues, understand the mission, contribute without exposing vulnerable people, and work toward a local MVP with clear rules.

Exit criteria:

- main documentation published in English and Portuguese;
- license defined;
- issue and pull request templates created;
- labels and milestones configured;
- initial city selected;
- initial categories selected;
- initial data model approved;
- operational privacy policy applied to the MVP;
- data review process defined;
- initial GitHub backlog created.

## Epic 0.1: Repository Organization

Goal: make the repository understandable for new contributors.

Candidate issues:

- Create the initial project folder structure.
- Create `LICENSE`.
- Create `CODEOWNERS`.
- Create `.github/ISSUE_TEMPLATE/bug_report.md`.
- Create `.github/ISSUE_TEMPLATE/feature_request.md`.
- Create `.github/ISSUE_TEMPLATE/data_submission.md`.
- Create `.github/ISSUE_TEMPLATE/data_correction.md`.
- Create `.github/ISSUE_TEMPLATE/rfc.md`.
- Create `.github/PULL_REQUEST_TEMPLATE.md`.
- Create `SECURITY.md` with a definitive private reporting channel.
- Create `MAINTAINERS.md`.
- Create `DECISIONS.md` or a `docs/decisions` folder.

Acceptance criteria:

- new contributors can understand where to open each issue type;
- PRs explicitly ask for privacy, security, and social impact review;
- data issues ask for source and verification date;
- no instruction encourages publishing personal data.

Suggested labels: `type/docs`, `area/community`, `priority/p1-high`, `good-first-issue`.

## Epic 0.2: Governance and Community Process

Goal: turn documented governance into operational process.

Candidate issues:

- Define the process for accepting new maintainers.
- Define the process for removing permissions after violations.
- Create an RFC template.
- Create a public decision record template.
- Create the flow for decisions that require community council approval.
- Create the initial list of responsibility areas.
- Create a conflict mediation guide.
- Create a translation synchronization policy between `docs/en` and `docs/pt-BR`.
- Define the canonical language for decisions.
- Create a conflict-of-interest declaration process.

Acceptance criteria:

- critical changes have a clear approval path;
- sensitive decisions do not depend on one person;
- local chapters know what they may adapt and what they may not weaken.

Suggested labels: `type/governance`, `area/community`, `priority/p1-high`.

## Epic 0.3: License and Protection Against Capture

Goal: choose licenses compatible with open source, open data, and mission protection.

Candidate issues:

- Research the code license.
- Research the documentation license.
- Research the schema and taxonomy license.
- Research the license for published institutional data.
- Create a licensing RFC.
- Review risks of private capture of community work.
- Document limits for acceptable commercial use.

Acceptance criteria:

- code license is defined;
- documentation license is defined;
- open data policy does not allow publication of personal data;
- decision is documented and reviewable.

Suggested labels: `type/rfc`, `type/governance`, `area/funding`, `needs-legal-review`.

## Epic 0.4: Initial MVP Scope

Goal: prevent the project from trying to build a global platform before validating local value.

Recommended decision:

- initial city: Sao Paulo;
- initial categories: food, shelter, documentation, mental health, employment, and immigrants;
- initial goal: 200 real services;
- initial product: mobile-first web app with search, list, and service page;
- initial users: people seeking basic help and intermediaries who support them.

Candidate issues:

- Confirm the initial city.
- Confirm initial categories.
- Define criteria to include or exclude services.
- Create the initial category taxonomy.
- Create a list of priority public sources.
- Create a user interview plan.
- Create an organization interview plan.
- Define the main MVP metric.

Acceptance criteria:

- there is a small and executable scope;
- categories have clear definitions;
- MVP does not include chat, financial donations, autonomous AI, or native mobile apps;
- main metric is defined.

Suggested labels: `type/research`, `area/product`, `area/data-quality`, `priority/p1-high`.

## Epic 0.5: Operational Privacy for the MVP

Goal: apply the no server-side personal data storage rule from the beginning.

Candidate issues:

- Create a privacy review checklist for PRs.
- Create a data matrix with purpose, legal basis, and retention.
- Define a logging policy without identifiable data.
- Define how to truncate, remove, or anonymize IPs.
- Define aggregate-only analytics.
- Define a session replay ban.
- Define a server-side individual search history ban.
- Define a server-side individual eligibility answers ban.
- Define allowed technical exceptions and maximum retention.
- Create a data protection impact assessment process.

Acceptance criteria:

- every technical issue knows what must not be stored;
- analytics only allow aggregate metrics;
- logs do not retain unnecessary user identifiers;
- exceptions require justification and review.

Suggested labels: `type/privacy`, `area/privacy`, `area/security`, `priority/p0-critical`.

## Phase 1: Local MVP

Milestone: `phase-1-local-mvp`

Goal: launch a first functional, local, simple, and trustworthy version with anonymous search and verified data.

Expected outcome: a person can open the website on a phone, search by need and city, open a service, understand how to request help, and share the information.

Exit criteria:

- mobile-first web app published in a test environment;
- catalog with 200 real services;
- search by text, category, and city;
- service page with source and last verification date;
- form to suggest a service;
- form to report incorrect data;
- minimal admin panel;
- no server-side storage of end-user personal data;
- basic aggregate metrics available;
- MVP operations documentation.

## Epic 1.1: Initial Data Model

Goal: create the minimum model for organizations, services, locations, contacts, categories, reports, and verification.

Initial entities:

- `Organization`
- `Service`
- `Location`
- `Contact`
- `Category`
- `EligibilityNote`
- `UserReport`
- `VerificationLog`
- `DataSource`

Candidate issues:

- Define the `Organization` schema.
- Define the `Service` schema.
- Define the `Location` schema.
- Define the `Contact` schema.
- Define the `Category` schema.
- Define the `UserReport` schema.
- Define the `VerificationLog` schema.
- Define service status enum.
- Define trust level enum.
- Define required fields for publication.
- Define prohibited fields.
- Create initial category seed data.
- Create validations for official contacts.
- Create data model documentation.

Acceptance criteria:

- model enables search and publication without end-user personal data;
- each service has source, status, and last verification date;
- data about people receiving help does not appear in the public schema;
- model can evolve toward HSDS/Open Referral compatibility.

Suggested labels: `area/data-model`, `area/backend`, `type/feature`, `priority/p1-high`.

## Epic 1.2: Backend and Minimal Public API

Goal: create an API to read services and safely receive suggestions and reports.

Minimum endpoints:

- `GET /categories`
- `GET /services`
- `GET /services/:id`
- `GET /organizations/:id`
- `POST /service-suggestions`
- `POST /reports`
- `GET /health`

Candidate issues:

- Create initial backend structure.
- Create database connection.
- Create migrations.
- Create categories endpoint.
- Create services list endpoint.
- Create service detail endpoint.
- Create filters by category and city.
- Create simple text search.
- Create service suggestion endpoint.
- Create report incorrect data endpoint.
- Add rate limiting to public endpoints.
- Add input validation.
- Add link and text sanitization.
- Create API tests.
- Create OpenAPI documentation.

Acceptance criteria:

- API does not create an end-user profile;
- public endpoints do not require login;
- reports and suggestions are not published automatically;
- logs do not keep unnecessary identifiable data;
- tests cover main filters and validations.

Suggested labels: `area/backend`, `area/security`, `area/privacy`, `type/feature`.

## Epic 1.3: Mobile-First Public Frontend

Goal: create the main public experience for finding help.

Minimum pages:

- home;
- search;
- service detail;
- organization page;
- suggest service;
- report incorrect data;
- about;
- privacy.

Candidate issues:

- Create mobile-first base layout.
- Create home with main search.
- Create city selector.
- Create category filters.
- Create results list.
- Create empty state for searches without results.
- Create service detail page.
- Create "Who can receive help" block.
- Create "How to request help" block.
- Create required documents block.
- Create official contacts block.
- Show source and last verification date.
- Create trust status badge.
- Create WhatsApp share button.
- Create report incorrect data button.
- Create service suggestion form.
- Create plain-language privacy page.
- Verify keyboard accessibility.
- Verify contrast.
- Verify mobile responsiveness.

Acceptance criteria:

- person can find a service without login;
- copy is simple and does not promise service delivery;
- result shows verification status;
- layout works well on phones;
- no invasive tracker is added;
- forms warn users not to send sensitive personal data.

Suggested labels: `area/frontend`, `area/accessibility`, `type/feature`, `priority/p1-high`.

## Epic 1.4: Minimal Admin Panel

Goal: allow manual review before publication.

Minimum features:

- admin login;
- services list;
- create service;
- edit service;
- review suggestions;
- review reports;
- set status;
- record verification;
- view change history.

Candidate issues:

- Create admin authentication.
- Create role-based access control.
- Create admin service list.
- Create admin service form.
- Create suggestions queue.
- Create reports queue.
- Create approve suggestion action.
- Create reject suggestion action.
- Create verification record action.
- Create change history.
- Create filters by status and city.
- Create alert for old services.
- Create protection against malicious links.

Acceptance criteria:

- no suggested service appears publicly without review;
- sensitive changes are recorded;
- admins do not see unnecessary personal data;
- critical actions require proper permissions.

Suggested labels: `area/admin`, `area/data-quality`, `area/security`, `type/feature`.

## Epic 1.5: Initial Data Operations

Goal: create the first trustworthy catalog.

Candidate issues:

- Create a standard CSV or spreadsheet format for import.
- Create a source research guide.
- Create a verification checklist by phone, website, or official source.
- Map food support services in Sao Paulo.
- Map shelter services in Sao Paulo.
- Map documentation services in Sao Paulo.
- Map mental health services in Sao Paulo.
- Map employment services in Sao Paulo.
- Map immigrant support services in Sao Paulo.
- Review duplicates.
- Review official contacts.
- Review opening hours.
- Review eligibility criteria.
- Mark unconfirmed services as unverified.
- Publish the first batch of 50 services.
- Publish the first batch of 100 services.
- Publish the first batch of 200 services.

Acceptance criteria:

- each service has a source;
- each service has last verification date;
- uncertain services are marked as uncertain;
- data about people receiving help is not collected;
- services with scam risk are not published.

Suggested labels: `type/data`, `area/data-quality`, `needs-data-review`, `help-wanted`.

## Epic 1.6: Observability Without Tracking Users

Goal: measure technical health and initial impact without storing personal user data.

Allowed metrics:

- total searches by category;
- total searches by city;
- total searches without results;
- aggregate clicks by service;
- total reports by type;
- availability;
- latency;
- 4xx and 5xx errors;
- search response time.

Candidate issues:

- Define allowed aggregate events.
- Create metrics layer without user id.
- Configure logs without identifiable IPs.
- Configure health checks.
- Create technical dashboard.
- Create aggregate impact dashboard.
- Create alert for 5xx errors.
- Create alert for job failures.
- Document metrics retention.

Acceptance criteria:

- dashboards contain no individual identification;
- product metrics are aggregated before storage;
- operational logs minimize identifiers;
- retention is documented.

Suggested labels: `area/devops`, `area/privacy`, `area/security`, `type/feature`.

## Phase 2: Local Public Launch

Milestone: `phase-2-public-launch`

Goal: open the MVP to real users in one city, with a weekly review and improvement process.

Expected outcome: real people use the product, organizations start sending corrections, and the community can measure searches with results, aggregate clicks, and data gaps.

Exit criteria:

- public domain configured;
- basic local SEO content;
- weekly data review process;
- support and report channel;
- accessibility validated;
- first community partners contacted;
- initial public aggregate impact report;
- backlog prioritized from real usage.

## Epic 2.1: Launch Preparation

Candidate issues:

- Define domain.
- Configure production environment.
- Configure backups.
- Configure monitoring.
- Configure status page.
- Review public privacy policy.
- Review terms of use.
- Create anti-scam warning.
- Create "About" page.
- Create "How we verify data" page.
- Create simple FAQ.
- Create launch checklist.

Acceptance criteria:

- environment is monitored;
- public privacy content is understandable;
- users are warned against scams;
- critical data has final review before launch.

Suggested labels: `area/devops`, `area/docs`, `area/security`, `priority/p1-high`.

## Epic 2.2: SEO and Local Pages

Candidate issues:

- Create food support page for Sao Paulo.
- Create shelter page for Sao Paulo.
- Create documentation page for Sao Paulo.
- Create mental health page for Sao Paulo.
- Create employment page for Sao Paulo.
- Create immigrant support page for Sao Paulo.
- Add metadata by category.
- Add sitemap.
- Add robots.txt.
- Add schema.org when appropriate.
- Create rule for visible update date.

Acceptance criteria:

- pages do not promise service delivery;
- pages show update date;
- content is simple and direct;
- SEO does not create misleading or duplicate pages.

Suggested labels: `area/frontend`, `area/docs`, `type/feature`, `priority/p2-medium`.

## Epic 2.3: Feedback and Reports

Candidate issues:

- Improve report incorrect data form.
- Create report categories.
- Create priority queue for critical reports.
- Create visual send confirmation.
- Create flow to hide suspicious service.
- Create internal SLA for scam reports.
- Create aggregate metric for resolved reports.
- Create guide for responding to reports.

Acceptance criteria:

- reports do not expose unnecessary personal data;
- critical reports reach admin with priority;
- suspicious service can be hidden quickly;
- resolution is recorded.

Suggested labels: `area/admin`, `area/data-quality`, `area/security`, `type/feature`.

## Epic 2.4: Accessibility and Inclusion

Candidate issues:

- Review contrast on all public pages.
- Test keyboard navigation.
- Test screen readers.
- Review plain-language copy.
- Add support for larger font.
- Ensure map is not mandatory.
- Create low-data mode.
- Review experience on older phones.
- Review experience on slow connections.

Acceptance criteria:

- search works without map;
- main content is accessible through screen readers;
- buttons and links have clear names;
- pages load well on limited connections.

Suggested labels: `area/accessibility`, `area/frontend`, `type/design`, `priority/p1-high`.

## Epic 2.5: Public Data Quality Routine

Candidate issues:

- Create weekly review calendar.
- Create queue for expired verification.
- Create monthly review routine by category.
- Create broken-link check routine.
- Create invalid-phone check routine.
- Create public data quality report.
- Create basic training for volunteer verifiers.

Acceptance criteria:

- old data enters a queue;
- volunteers have clear instructions;
- report shows verified, pending, and reported service counts;
- data quality becomes continuous work.

Suggested labels: `area/data-quality`, `type/data`, `help-wanted`.

## Phase 3: Organizations

Milestone: `phase-3-organizations`

Goal: allow legitimate organizations to register and maintain their services, with institutional verification and moderation.

Expected outcome: NGOs, faith communities, local groups, responsible companies, and public agencies can update data without automatically publishing dangerous or false information.

Exit criteria:

- organization registration;
- institutional verification;
- organization dashboard;
- organization team management;
- change history;
- review of sensitive changes;
- aggregate dashboard for organizations;
- privacy and retention rules for institutional accounts.

## Epic 3.1: Institutional Registration and Verification

Candidate issues:

- Create organization user model.
- Create organization registration flow.
- Create institutional email verification.
- Create domain verification.
- Create institutional document fields when applicable.
- Create organization status.
- Create admin verification queue.
- Create rejection with reason.
- Create resubmission flow.
- Create retention policy for verification documents.

Acceptance criteria:

- organizations do not publish automatically;
- sensitive documents have restricted access;
- verification data has defined retention;
- public organization status is clear.

Suggested labels: `area/backend`, `area/admin`, `area/privacy`, `type/feature`.

## Epic 3.2: Organization Dashboard

Candidate issues:

- Create organization login.
- Create access recovery.
- Create services dashboard.
- Create service edit form.
- Create preview before submitting changes.
- Create submit-for-review flow.
- Create change history.
- Create team management.
- Create roles inside organization.
- Create pending-review notice.
- Create reports dashboard.

Acceptance criteria:

- sensitive changes may require human review;
- organization sees reports for its services;
- change history is auditable;
- internal permissions are respected.

Suggested labels: `area/frontend`, `area/backend`, `area/admin`, `type/feature`.

## Epic 3.3: Organization Metrics Without Tracking People

Candidate issues:

- Define allowed organization metrics.
- Create aggregate visit visualization.
- Create aggregate click visualization.
- Create aggregate report visualization.
- Create aggregate export.
- Create privacy notice about metrics.
- Block drill-down to individual users.

Acceptance criteria:

- organization never sees individual user history;
- metrics are aggregated;
- no precise user location is displayed;
- dashboard does not allow re-identification.

Suggested labels: `area/privacy`, `area/frontend`, `area/backend`, `priority/p0-critical`.

## Phase 4: Safe AI

Milestone: `phase-4-safe-ai`

Goal: add AI only where it improves clarity, search, translation, review, and data quality without replacing human responsibility.

Expected outcome: AI helps people and maintainers, but does not promise rights, does not make definitive eligibility decisions, and does not publish data without review.

Exit criteria:

- AI risk assessment;
- reviewed prompts;
- logs without sensitive personal data;
- human review for published content;
- probabilistic language;
- traceability for reviewers;
- AI can be disabled by configuration.

## Epic 4.1: AI Governance

Candidate issues:

- Create RFC for the first AI feature.
- Create AI risk checklist.
- Create prompt policy without personal data.
- Create AI logs policy.
- Create record for AI-assisted decisions.
- Create human review mechanism.
- Create fallback without AI.
- Create public notice when content is AI-assisted.

Acceptance criteria:

- community council approves sensitive uses;
- prompts do not include unnecessary personal data;
- AI can be audited by reviewers;
- AI can be disabled without breaking the product.

Suggested labels: `area/ai`, `area/privacy`, `type/rfc`, `needs-security-review`.

## Epic 4.2: Safe Semantic Search

Candidate issues:

- Evaluate semantic search without personal data.
- Create indexing only for institutional data.
- Create synonym search.
- Create multilingual search.
- Create tests for common queries.
- Create evaluation for bad results.
- Create blocking of sensitive queries in logs.

Acceptance criteria:

- index contains no user personal data;
- search improves results without tracking people;
- queries are not associated with individual users.

Suggested labels: `area/ai`, `area/search`, `area/privacy`, `type/feature`.

## Epic 4.3: Assisted Summaries and Translations

Candidate issues:

- Create plain-language service summary.
- Create assisted translation to English.
- Create assisted translation to Spanish.
- Require human review before publishing.
- Create diffs for reviewers.
- Create glossary for sensitive terms.
- Create tests for prohibited language.

Acceptance criteria:

- summary does not alter service rules;
- translation does not promise service delivery;
- human review is required before publication;
- terms such as "guaranteed" and "approved" are blocked in eligibility contexts.

Suggested labels: `area/ai`, `area/i18n`, `area/data-quality`, `type/feature`.

## Epic 4.4: Careful Probable Eligibility

Candidate issues:

- Create probable eligibility RFC.
- Define allowed questions without server-side storage.
- Define local processing when possible.
- Define uncertain language.
- Create "confirm with the responsible organization" notice.
- Block definitive legal or medical advice.
- Create human review for sensitive rules.
- Create tests with edge cases.

Acceptance criteria:

- answers are not stored server-side at the initial stage;
- recommendation uses probabilistic language;
- no final automated decision exists;
- flow explains limits simply.

Suggested labels: `area/ai`, `area/privacy`, `area/frontend`, `priority/p0-critical`.

## Phase 5: Local Chapters

Milestone: `phase-5-local-chapters`

Goal: enable expansion by city, region, and country without losing quality, safety, or mission alignment.

Expected outcome: local groups can map services, review data, and operate with limited autonomy under shared standards.

Exit criteria:

- local chapter guide;
- approval checklist;
- training kit;
- local governance model;
- metrics by chapter;
- support process;
- process to pause a chapter in case of risk.

## Epic 5.1: Local Chapter Kit

Candidate issues:

- Create "how to open a local chapter" guide.
- Create minimum requirements checklist.
- Create local README template.
- Create city plan template.
- Create service spreadsheet template.
- Create source verification guide.
- Create organization outreach guide.
- Create volunteer safety guide.
- Create public communication policy.
- Create local translation kit.

Acceptance criteria:

- chapter knows where to start;
- chapter cannot weaken privacy, security, AI, or funding rules;
- process requires at least two responsible people.

Suggested labels: `area/local-chapters`, `type/docs`, `help-wanted`.

## Epic 5.2: Expansion to New Cities

Candidate issues:

- Select second city.
- Map public sources for second city.
- Define initial categories for second city.
- Recruit two local responsible people.
- Add 100 initial services.
- Review 100 initial services.
- Publish city pages.
- Create local review routine.
- Create local gap report.

Acceptance criteria:

- city has local responsible people;
- data has source and verification;
- pages clearly show local status;
- maintenance routine exists.

Suggested labels: `area/local-chapters`, `type/data`, `area/data-quality`.

## Epic 5.3: Federated Governance

Candidate issues:

- Create permission model by chapter.
- Create process to approve a chapter.
- Create process to pause a chapter.
- Create process to transfer local maintainers.
- Create periodic report by chapter.
- Create cross-chapter support channel.
- Create local data audit process.

Acceptance criteria:

- chapters have operational autonomy;
- central rules remain mandatory;
- local risk can be contained quickly.

Suggested labels: `area/governance`, `area/local-chapters`, `type/rfc`.

## Phase 6: Ecosystem

Milestone: `phase-6-ecosystem`

Goal: turn OpenSource for Humans into open infrastructure for partners, governments, organizations, and communities without selling personal data or capturing the mission.

Expected outcome: safe public API, integrations, aggregate impact reports, institutional tools, and responsible financial sustainability.

Exit criteria:

- public API documented;
- API terms of use;
- rate limits;
- safe open data;
- aggregate public reports;
- partnership policy;
- funding policy applied;
- institutional tools without paid priority in essential help.

## Epic 6.1: Safe Public API

Candidate issues:

- Create public API RFC.
- Define which data can be open.
- Define which data can never be open.
- Create partner authentication when needed.
- Create rate limiting.
- Create API documentation.
- Create usage examples.
- Create API terms of use.
- Create abuse monitoring.
- Create access revocation process.

Acceptance criteria:

- API does not expose user personal data;
- institutional data has license and source;
- abuse can be blocked;
- partners understand usage limits.

Suggested labels: `area/backend`, `area/security`, `area/privacy`, `type/feature`.

## Epic 6.2: Impact Reports

Candidate issues:

- Define allowed public metrics.
- Create monthly aggregate report.
- Create report by city.
- Create report by category.
- Create data quality metrics.
- Create resolved reports metrics.
- Create public methodology.
- Create re-identification risk review.

Acceptance criteria:

- reports do not allow re-identification;
- methodology is public;
- data is aggregated;
- limitations are explained.

Suggested labels: `area/data-quality`, `area/privacy`, `area/community`, `type/docs`.

## Epic 6.3: Partnerships and Sustainability

Candidate issues:

- Create partnership policy.
- Create funder assessment process.
- Create public supporters page.
- Create conflict of interest declaration.
- Create government partnership model.
- Create NGO partnership model.
- Create university partnership model.
- Create responsible company partnership model.
- Create limits for paid tools.
- Create audit for result priority.

Acceptance criteria:

- no funder controls governance;
- payment does not increase public trust status;
- people seeking help remain free of charge;
- conflicts of interest are published.

Suggested labels: `area/funding`, `area/governance`, `type/docs`, `needs-legal-review`.

## Recommended Initial Backlog

These issues can be created first to unblock the project.

## P0 Priority

- `[privacy] Define no server-side user data storage checklist`
- `[privacy] Define anonymized aggregate analytics policy`
- `[security] Define private vulnerability reporting channel`
- `[data] Define minimum publishable service fields`
- `[data] Define prohibited personal data fields`
- `[governance] Create GitHub issue and PR templates`
- `[product] Confirm initial city and categories`
- `[data] Create initial service verification checklist`

## P1 Priority

- `[frontend] Create mobile-first public search wireframe`
- `[frontend] Create service detail page wireframe`
- `[backend] Draft service catalog API contract`
- `[data-model] Draft Organization and Service schemas`
- `[admin] Define moderation queue workflow`
- `[docs] Create local chapter starter guide`
- `[accessibility] Create accessibility checklist`
- `[security] Create abuse and scam risk checklist`

## P2 Priority

- `[data] Map first 50 food support services`
- `[data] Map first 50 shelter or emergency services`
- `[i18n] Define translation workflow`
- `[seo] Define local SEO page structure`
- `[devops] Choose MVP hosting approach`
- `[community] Define contributor onboarding flow`
- `[funding] Draft responsible funding principles page`

## Metrics by Phase

## Phase 0

- number of essential documents completed;
- number of templates created;
- number of ready issues;
- number of initial contributors;
- initial scope approved.

## Phase 1

- services added;
- services verified;
- aggregate searches by category;
- searches without results;
- aggregate clicks on "how to request help";
- reports received;
- reports resolved;
- average search response time;
- availability.

## Phase 2

- aggregate users by city without individual identification;
- search-with-results rate;
- aggregate contact click rate;
- number of organizations contacted;
- number of corrections received;
- average age of published data;
- accessibility validated.

## Phase 3

- verified organizations;
- services managed by organizations;
- approved changes;
- reports answered by organizations;
- average update time;
- institutional data with defined retention.

## Phase 4

- AI suggestions reviewed;
- duplicates detected;
- translations reviewed;
- summaries approved;
- incidents or rejections due to unsafe language;
- percentage of flows with non-AI fallback.

## Phase 5

- active chapters;
- local responsible people;
- services by city;
- percentage of services verified by chapter;
- local reports published;
- chapters paused because of risk, if any.

## Phase 6

- active partners;
- aggregate API calls;
- blocked abuse incidents;
- impact reports published;
- public funding declared;
- result priority audits.

## Security, Privacy, and Mission Gates

Before every public release, answer:

- Does this change store end-user personal data server-side?
- If yes, is there justification, legal basis, retention, review, and an alternative without storage?
- Are statistics anonymized and aggregated before storage?
- Does any flow require login to find help?
- Does any paid service gain priority in essential help?
- Does any AI make a final decision?
- Does any page promise service delivery, legal right, approval, or outcome?
- Does service data have source and last verification date?
- Is there a simple way to report incorrect data?
- Is there risk of scam, abuse, or exposure of vulnerable people?
- Does the change work on mobile?
- Is the change understandable for people with low digital familiarity?

If an answer indicates high risk, the release must be blocked until maintainer or community council review.

## What Not to Build at the Beginning

Avoid in the MVP:

- real-time chat;
- native mobile app;
- financial donations inside the platform;
- public ranking of organizations;
- complex volunteer marketplace;
- autonomous AI;
- definitive eligibility;
- mandatory login to search for help;
- collection of tax ID, document, phone, or address from people seeking help;
- individual search history;
- ads;
- paid priority;
- banking integrations;
- full CRM for NGOs.

## Recommended Issue Size

Good contribution issues should fit into:

- `effort/xs`: up to 1 hour, documentation or small adjustment;
- `effort/s`: half day, simple component or short research;
- `effort/m`: 1 to 2 days, endpoint, screen, or small flow;
- `effort/l`: several days, smaller technical epic;
- `effort/xl`: should be broken down before anyone starts.

Practical rule:

> If an issue needs more than one person working at the same time, it should probably become an epic and be broken down.

## Short Issue Template

```md
## Objective

## Context

## Scope

## Out of Scope

## Acceptance Criteria

## Privacy Risks

## Security Risks

## Social Impact Risks

## Dependencies

## Likely Files or Areas
```

## Recommended Next Step

Create the `phase-0-foundation` milestone and open the P0 issues from the initial backlog.

After that, each Phase 0 epic should become a parent issue, and every checklist item should become a small issue with labels, assignee, and acceptance criteria.
