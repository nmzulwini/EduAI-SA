# EduAI-SA Database Schema

## Overview

This document defines the database structure for EduAI-SA.

The platform uses Firebase Firestore as the primary database.

---

# Collections

## Users

Stores information for all users.

Fields:

- userId
- fullName
- email
- role
- schoolId
- profileImage
- createdAt
- updatedAt

Roles:

- Learner
- Teacher
- Parent
- Administrator

---

## Schools

Fields:

- schoolId
- schoolName
- province
- district
- circuit
- principal
- createdAt

---

## Classes

Fields:

- classId
- grade
- className
- teacherId
- schoolId

Example:

Grade 7C

---

## Subjects

Fields:

- subjectId
- subjectName
- grade

Example:

- Mathematics
- Technology

---

## Lessons

Fields:

- lessonId
- subjectId
- title
- description
- week
- content
- resources

---

## Assessments

Fields:

- assessmentId
- subjectId
- title
- totalMarks
- dueDate

---

## Results

Fields:

- resultId
- learnerId
- assessmentId
- mark
- percentage
- feedback

---

## Progress

Fields:

- progressId
- learnerId
- subjectId
- lessonsCompleted
- quizzesCompleted
- overallProgress

---

## AI Chats

Fields:

- chatId
- userId
- prompt
- response
- timestamp

---

## Achievements

Fields:

- achievementId
- learnerId
- badge
- description
- dateAwarded

---

## Notifications

Fields:

- notificationId
- userId
- title
- message
- read
- createdAt
