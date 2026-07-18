# EduAI-SA Project Structure

## Overview

This document defines the folder structure for the Flutter application.

---

# Project Structure

```
eduai_sa/

├── android/
├── ios/
├── web/
├── linux/
├── macos/
├── windows/

├── assets/
│   ├── images/
│   ├── icons/
│   ├── animations/
│   └── fonts/

├── lib/

│   ├── core/
│   │   ├── constants/
│   │   ├── theme/
│   │   ├── services/
│   │   ├── models/
│   │   └── utilities/
│   │
│   ├── features/
│   │
│   │   ├── authentication/
│   │   ├── ai_tutor/
│   │   ├── mathematics/
│   │   ├── technology/
│   │   ├── progress/
│   │   ├── teacher/
│   │   ├── parent/
│   │   └── settings/
│   │
│   ├── shared/
│   │   ├── widgets/
│   │   ├── components/
│   │   └── helpers/
│   │
│   └── main.dart

├── test/

├── docs/

└── pubspec.yaml
```

---

# Development Principles

- Keep features independent.
- Reuse shared widgets.
- Separate business logic from UI.
- Write clean and maintainable code.
- Follow Flutter best practices.

---

# Future Modules

- Notifications
- Offline Learning
- School Administration
- AI Analytics
- Multi-language Support
