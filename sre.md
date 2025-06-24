"# 📘 Software Requirements Specification (SRS)

## 📌 Project Overview
- **Project Name**: ImanFlix Mobile App  
- **Author**: Muhammad Anas  
- **Date**: June 2024  
- **Description**: ImanFlix is a spiritual and educational streaming platform providing Islamic content like lectures, nasheeds, and Quranic recitations. It supports user authentication via Google, Email, and Mobile OTP, along with interactive features like commenting, liking, and downloading.

## 1. 🧩 Functional Requirements

| ID   | Requirement Description |
|------|--------------------------|
| FR1  | The app shall allow user registration via Google, Email, and Mobile number with OTP verification. |
| FR2  | The app shall support user login using valid credentials (Google, Email, or Mobile). |
| FR3  | The app shall display content categorized as Lectures, Nasheeds, Telawat, and Others. |
| FR4  | The app shall support high-quality video playback with pause/resume/fullscreen. |
| FR5  | The app shall allow video download where permitted. |
| FR6  | The app shall offer search with filters, predictive suggestions, and keyword matching. |
| FR7  | Users shall be able to like, comment, edit, delete, and share videos. |
| FR8  | The app shall validate inputs such as email format, name length, and empty fields. |
| FR9  | The app shall allow OTP resending and show error for expired/invalid OTPs. |
| FR10 | The app shall require profile completion (name, email/phone) before accessing main features. |

## 2. ⚙️ Non-Functional Requirements

| ID   | Requirement Description |
|------|--------------------------|
| NFR1 | Video playback must start within 3 seconds on a stable connection. |
| NFR2 | The app UI must be responsive and consistent across Android and iOS devices. |
| NFR3 | All error messages must be user-friendly and precise. |
| NFR4 | All content must align with Islamic values — no inappropriate or offensive material. |
| NFR5 | OTPs and tokens must expire securely and be encrypted. |
| NFR6 | The app should scale to at least 100 concurrent users without performance drops. |

## 3. 🔗 System Interfaces
- **Firebase**: for authentication and OTP services  
- **Cloud Storage / CDN**: for storing and streaming media content  
- **Backend APIs / Database**: for user data, comment handling, video metadata

## 4. 👤 User Roles

| Role            | Permissions |
|-----------------|-------------|
| Guest           | View limited content, initiate signup/login |
| Registered User | Full access to content, like/share/comment, download (if allowed) |
"""
