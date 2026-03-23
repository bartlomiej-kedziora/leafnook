# Leafnook

**Leafnook – your private reading nook.**

A self-hosted personal reading platform for PDFs (and more in the future), with progress tracking and dictionary support.

## 🚀 Vision

Leafnook is designed as a private, self-hosted alternative to commercial e-readers, focused on:

* Personal library management
* Seamless reading experience
* Reading progress persistence
* Future language learning support (dictionaries, translations)

## 🏗️ Architecture (MVP)

* Backend: Kotlin + Spring Boot
* Frontend: Angular
* Database: PostgreSQL
* Storage: MinIO (S3-compatible)
* Deployment: Docker + Nginx (Raspberry Pi ready)

## 📦 Repository Structure

* `leafnook-be/` – Spring Boot application
* `leafnook-fe/` – Angular application
* `leafnook-infra/` – Docker, Nginx, deployment configs
* `leafnook-docs/` – backlog, architecture, decisions

## 🛠️ Status

🚧 Work in progress – MVP under development

## 📖 MVP Scope

* User registration with email verification
* Private library (per user)
* PDF upload and storage
* Reading with page navigation
* Reading progress tracking
* "Continue reading" experience

## 🔮 Future Plans

* Dictionary integration
* Word translation on selection
* Multiple formats (EPUB, etc.)
* Notes and highlights

## 📁 Project Structure

- `leafnook-be/` – backend (Spring Boot, Kotlin)
- `leafnook-fe/` – frontend (Angular)
- `leafnook-infra/` – infrastructure (Docker, Nginx, MinIO)
- `leafnook-docs/` – documentation and backlog

---

Built with ❤️ as a self-hosted reading experience.
