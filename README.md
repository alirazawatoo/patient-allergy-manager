# Patient Allergy Manager

A Spring Boot and React assessment project for reviewing patient profiles and adding allergy molecules through a searchable interface.

## Workflow

```text
patient list -> patient profile -> search molecule -> select result -> update allergies
```

The Java backend exposes patient/allergy endpoints over an in-memory SQLite dataset. The React frontend renders profiles, search results, and error states. Docker Compose and GitHub Actions describe the supplied build path.

## Local setup

```bash
docker compose up --build
```

See the backend and frontend manifests for direct Maven and Node development commands.

## Attribution and scope

This repository originated as a code assessment with an existing Spring/React scaffold. The molecule-search workflow and CI work should be evaluated as changes within that supplied structure, not as a from-scratch healthcare platform.

The project uses sample data and is not a clinical system. Authorization, audit logging, privacy controls, terminology governance, and production persistence are not demonstrated. The application and tests were not run during the portfolio review.
