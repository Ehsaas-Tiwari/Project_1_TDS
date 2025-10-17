#  LLM Code Deployment Project

##  Overview

This project demonstrates an **automated LLM-assisted system** to:

1. Receive a task request containing a brief and optional attachments.
2. Generate a minimal web application using a **Large Language Model**.
3. Create or update a GitHub repository.
4. Deploy the app to **GitHub Pages**.
5. Notify an evaluation server with repository metadata.

The system supports **multiple rounds per task**. In round 2, the LLM updates or refactors the app based on a new brief.

---

##  Objectives

- Host a **FastAPI endpoint** to accept JSON POST requests.
- Use an LLM to **generate or revise code** for web apps.
- Automate **GitHub repository creation**, file commits, and **Pages deployment**.
- Notify evaluation servers with details (`repo_url`, `commit_sha`, `pages_url`).
- Support **round 1 and round 2 workflows**.

---
