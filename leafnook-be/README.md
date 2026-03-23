# Leafnook Backend

This module contains the backend application for **Leafnook**.

## 🧠 Overview

The backend is built as a **modular monolith** using:

* Kotlin
* Spring Boot
* Gradle (multi-module setup)

The application is responsible for:

* User authentication and authorization
* Email verification
* Private library management
* PDF storage and access (via MinIO)
* Reading progress tracking
* Dictionary support (foundation for future features)

## 🏗️ Architecture

The backend follows a **multi-module structure**:

* `leafnook-be-app` – main Spring Boot application (entry point)
* domain modules (auth, user, book, reading, storage, dictionary, etc.)

All modules are combined into a **single executable JAR**.

## 🚀 Runtime

The backend is deployed as:

* a single container
* exposing REST API (`/api/v1/...`)

## 📦 Responsibilities

* Business logic
* API layer
* Persistence (PostgreSQL)
* File storage integration (MinIO)
* Security (JWT, verification flow)

---

Work in progress 🚧
