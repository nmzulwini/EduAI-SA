# EduAI-SA Authentication Flow

## Overview

This document describes how users securely register, log in, and access EduAI-SA.

---

# Authentication Provider

Firebase Authentication

Supported methods:

- Email and Password
- Google Sign-In (Future)
- Microsoft Sign-In (Future)

---

# User Registration

Steps:

1. User selects role
2. Enter full name
3. Enter email
4. Create password
5. Confirm password
6. Accept Terms and Privacy Policy
7. Verify email address
8. Account created

---

# User Roles

- Learner
- Teacher
- Parent
- Administrator

Each role has different permissions.

---

# Login Flow

Splash Screen

↓

Login

↓

Firebase Authentication

↓

Successful Login

↓

Load User Profile

↓

Open Dashboard

---

# Password Reset

User selects "Forgot Password"

↓

Enter email

↓

Receive reset email

↓

Create new password

↓

Login

---

# Session Management

Users remain logged in until they sign out.

The application checks authentication status on startup.

---

# Security

- HTTPS only
- Secure password storage by Firebase
- Email verification
- Role-based access control
- Authentication required for protected features

---

# Future Enhancements

- Multi-factor authentication
- Biometric login
- Single Sign-On (SSO)
