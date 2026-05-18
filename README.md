# KaloriQ — Calorie Tracking Android Application

> CE 443 Mobile Programming — Düzce University, Computer Engineering  
> 4-Person Team Project

## Overview
A native Android calorie tracking application that helps users log daily meals, manage dietary habits, and receive health-conscious food recommendations based on pre-existing medical conditions (diabetes, hypertension, high cholesterol).

## Features
- 🤖 Google Gemini 2.5 Flash AI for image-based food recognition
- 🍽️ 103 predefined Turkish foods catalog with localized names
- ⚠️ Disease-based dietary warning system (diabetes, hypertension, cholesterol)
- 📊 Weekly & monthly calorie reports with visual charts
- 🔔 Configurable push notifications (meal, water, goal alerts)
- 🌙 Light / Dark / System theme support
- 🌍 Turkish / English language switch
- 🔐 Firebase Authentication (email/password + Google Sign-In)

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Language | Java 17 |
| Platform | Android API 33+ |
| Backend | Firebase Auth + Cloud Firestore |
| AI | Google Gemini 2.5 Flash |
| Local DB | Room ORM |
| Background | WorkManager |
| Charts | MPAndroidChart |
| UI | Material Components 3 |
| Images | Glide |

## Architecture
- Repository Pattern
- WorkManager for background tasks
- Room ORM (local cache)
- Firebase Firestore (primary data store)
- Disease-based food warning logic

## Status
✅ **Completed** — CE 443 Mobile Programming course project

## Team
**Uğur Avşar** — Computer Engineering, Düzce University  
**Fatih Arslan** · **Osman Akdeniz** · **Muhammed Talha Bulut**

[LinkedIn](https://www.linkedin.com/in/uğuravşar) · [GitHub](https://github.com/Uguravsar75)
