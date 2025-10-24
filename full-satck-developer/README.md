# Car Rental Website (Next.js, TypeScript, Python, PostgreSQL)

## Project Overview
This is a full‑stack developer machine test. Build a car rental web app matching the provided Figma design and implement a functional search results experience backed by a Python API using PostgreSQL.

Figma: https://www.figma.com/design/TQiqOmgVHUGQa7la5zAGlc/Machine-test-Web?node-id=0-1&t=giLqxXhT7jBc4EC9-1

---

## Scope

- **Homepage (UI focus):** Implement the homepage exactly as per Figma.
- **Search Results Page (logic focus):** Implement results list with filters and pagination, powered by your Python API reading from PostgreSQL.

---

## Tech Constraints

- **Frontend:** Next.js + TypeScript.
- **Backend:** Any Python framework (FastAPI, Flask, Django, etc.).
- **Database:** PostgreSQL.

---

## Data Requirement

- Load the provided JSON dataset into PostgreSQL.
- Your backend must query PostgreSQL (not the JSON file at runtime) to serve the search results API consumed by the frontend.

---

## Functional Requirements

- **Homepage:**
  - Search bar with inputs for pickup, dropoff, and dates.
  - Dummy autocomplete (static city suggestions are fine).
  - Pixel‑perfect match to Figma and fully responsive.

- **Search Results Page:**
  - Displays cars from the backend API (data sourced from PostgreSQL).
  - Filters: car type, price (min/max), etc.
  - Pagination with Previous/Next.
  - State handling: loading, empty, and error states.

---

## Evaluation Criteria

- **UI Fidelity (Homepage):** Visual accuracy, spacing, typography, responsiveness.
- **Functional Correctness (Search):** Pagination, filters, data flow from API/DB.
- **Code Quality:** Structure, typing, readability, reuse, error handling.
- **UX Details:** Smooth interactions, clear states, accessibility considerations.
- **Project Hygiene:** Clear repo organization and documentation of assumptions.
- **Bonus:** Docker, CI, thoughtful performance choices.

---

## Submission

- Provide a Git repository link with frontend and backend code.
- Hosting is preferred (frontend + backend). If hosting is not possible, include clear notes on how to run locally.
