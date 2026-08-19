# Peblo TV Mini — Full-Stack Development Challenge

A miniature streaming platform inspired by Peblo TV, built as part of the Peblo Full-Stack Development Challenge.

The project includes:

- FastAPI + PostgreSQL backend
- React + TypeScript CMS
- React + TypeScript viewer
- Published catalogue generation
- Artwork validation and storage abstraction
- Role-based access control
- Search and filtering
- Docker Compose
- Automated tests
- GitHub Actions CI

---

## 1. Architecture

```text
CMS (React)
     |
     v
FastAPI API + PostgreSQL
     |
     v
Publish Job
     |
     v
catalogue.json
     |
     v
Viewer UI (React)
