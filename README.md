# Advertising Repository Assurance Room

## One-sentence benefit
Helps regulators, platforms and researchers assess whether advertising repositories enable meaningful public scrutiny.

## Live demo
Run the Java service and Angular application locally to use the complete experience.

## Screenshots
![advertising repository assurance workspace](docs/screenshot.png)

## Main features
Search repository reviews, create an assurance case, progress remediation and monitor approval and high-priority transparency gaps.

## Technology used
Angular, TypeScript, signals, computed state, server rendering, Spring Boot and Java.

## Installation instructions
Start the backend with `cd backend && mvn spring-boot:run`. In another terminal run `npm install && npm start`.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
Digital services coordinators, platforms, researchers and civil society need shared evidence about archive completeness, searchability and advertiser identity.

## Key workflows
Teams can find a repository review, add a validated assurance case and advance corrective work to approval.

## Angular framework highlights
The interface uses standalone components, signals, computed values, OnPush change detection, built-in control flow and SSR-safe loading.

## Java backend highlights
The Spring Boot service provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
Angular HttpClient connects signal-based state to the Java API and updates the visible board after every write.

## Accessibility and responsive behaviour
Semantic structure, labelled controls, visible focus, high contrast and compact responsive tables support varied users and devices.

## Verification commands
Use `npm test -- --watch=false`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains the Angular experience, `backend` contains the Java service, and `docs` contains verified media.

## Tradeoffs
Records are held in memory for demonstration speed; operational use would add identity, durable evidence, repository imports and supervisory integrations.

## Roadmap
Add automated repository sampling, advertiser-identity checks, export comparisons, research access and audit-ready persistence.
