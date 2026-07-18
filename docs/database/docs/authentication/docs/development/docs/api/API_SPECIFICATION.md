# EduAI-SA API Specification

## Overview

This document defines the REST API used by the EduAI-SA Flutter application and FastAPI backend.

---

# Base URL

Development:

http://localhost:8000/api/v1

Production:

https://api.eduai-sa.com/api/v1

---

# Authentication

POST /auth/register

Create a new user account.

---

POST /auth/login

Authenticate a user.

---

POST /auth/logout

Log out the current user.

---

POST /auth/reset-password

Send a password reset email.

---

# Users

GET /users/me

Retrieve the current user's profile.

---

PUT /users/me

Update the current user's profile.

---

# Subjects

GET /subjects

Retrieve all available subjects.

---

GET /subjects/{id}

Retrieve details for a subject.

---

# Lessons

GET /lessons

Retrieve all lessons.

---

GET /lessons/{id}

Retrieve a specific lesson.

---

# Assessments

GET /assessments

Retrieve assessments.

---

POST /assessments

Create an assessment.

---

# Progress

GET /progress/{learnerId}

Retrieve learner progress.

---

# AI Tutor

POST /ai/chat

Send a question to the AI Tutor.

Response:

- Answer
- Explanation
- Examples
- Practice Question

---

# Notifications

GET /notifications

Retrieve user notifications.

---

# Security

- HTTPS only
- JWT Authentication
- Role-based authorization
- Request validation
- Rate limiting
