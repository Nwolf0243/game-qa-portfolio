# game-qa-portfolio
My Game QA Portfolio
# 🎮 Game QA Portfolio — Nicholas Wolf

Welcome! This repository showcases my work as a **Game QA Tester / Playtester**, highlighting structured testing, clear bug reporting, and player-focused quality assurance using real projects.

---

## 👤 About Me

I am a Game QA Tester with a background in **Unity, C#, and software development**, experienced in testing WebGL and Android applications. I focus on identifying gameplay, UI, and stability issues and communicating them clearly to help teams ship polished player experiences.

* 🎮 Platforms: PC, WebGL, Android
* 🧪 Focus: Gameplay systems, UI/UX, regression testing, player experience
* 🌍 Open to: Remote, contract, or full-time QA roles

---

## 📂 Projects

### 1️⃣ Unity Trivia Game (WebGL)

A Unity-based trivia game deployed to the web using WebGL.

**My QA Responsibilities:**

* Functional and exploratory gameplay testing
* UI readability and layout validation
* Browser and resolution compatibility testing
* Bug reproduction, documentation, and regression testing

🔹 **Test Artifacts:**

* [QA Test Plan](#-qa-test-plan--unity-trivia-game)
* [Bug Reports](#-bug-report-samples)

---

### 2️⃣ VIPMembers — Android App

An Android application providing tier-based access to exclusive content.

**My QA Responsibilities:**

* Testing authentication and access control flows
* Validating membership-tier permissions
* Identifying stability and crash issues
* UX consistency across Android devices

🔹 **Test Artifacts:**

* [Bug Reports](#-bug-report-samples)

---

## 📑 QA Test Plan — Unity Trivia Game

See full test plan below. This document outlines scope, environments, test types, and exit criteria used to validate the game prior to release.

---

### 1. Objective
Verify that the Unity-based Trivia Game functions correctly across supported platforms and browsers, provides a clear and intuitive user experience, and is free of critical gameplay, UI, and stability issues prior to release.

---

### 2. Test Scope

**In Scope**
- Core gameplay flow (start game → answer questions → scoring → results)
- Question display and answer selection
- Score calculation and persistence
- Pause and resume functionality
- UI layout, readability, and responsiveness
- Input handling (mouse / keyboard)
- Browser compatibility
- Performance and stability during normal play

**Out of Scope**
- Backend infrastructure
- Localization
- Accessibility certification
- Analytics integration

---

### 3. Test Environment
- Platform: PC (WebGL)
- Browsers: Chrome, Edge, Firefox
- Resolutions: 1920x1080, 1366x768
- Build Type: WebGL release build

---

### 4. Test Types
- Functional Testing
- Exploratory Testing
- UI/UX Testing
- Regression Testing
- Compatibility Testing

---

### 5. Sample Test Cases

**TC-01:** Launch game  
Expected: Game loads without errors or visual issues  

**TC-02:** Start trivia session  
Expected: First question loads correctly  

**TC-03:** Select correct answer  
Expected: Score increments and feedback displays  

**TC-04:** Select incorrect answer  
Expected: Feedback displays, score unchanged  

**TC-05:** Pause and resume gameplay  
Expected: Game resumes without breaking UI or scoring  

**TC-06:** Complete full session  
Expected: Results screen shows accurate final score  

---

### 6. Defect Reporting
All defects include:
- Clear title
- Steps to reproduce
- Expected vs actual results
- Severity and priority
- Visual evidence when available

---

### 7. Exit Criteria
- No open Critical or High-severity bugs
- Core gameplay flow fully verified
- UI readable at supported resolutions
- No crashes or progression blockers

---

## 🐞 Bug Report Samples

### Bug #1 — UI Overlap at 1080p

**Severity:** Medium
**Priority:** High

**Issue:** Long question text overlaps answer buttons at lower resolutions.

---

### Bug #2 — Score Not Updating After Pause

**Severity:** High
**Priority:** High

**Issue:** Score does not increment after resuming from pause.

---

### Bug #3 — Unauthorized Content Visibility (VIPMembers)

**Severity:** Critical
**Priority:** Critical

**Issue:** Restricted content briefly visible to basic-tier users after login.

---

### Bug #4 — App Crash on Tier Change (VIPMembers)

**Severity:** High
**Priority:** High

**Issue:** App crashes when switching membership tiers without restart.

---

## 🧠 QA Methodology

My testing approach includes:

* Reproducible steps and clear expected vs actual results
* Severity and priority distinction
* Player-focused UX analysis
* Collaboration with developers using actionable feedback

---

## 📬 Contact

📧 **Email:** [nwolf0243@gmail.com](mailto:nwolf0243@gmail.com)
🌐 **LinkedIn:** (https://www.linkedin.com/in/nicholas-wolf-482087258/)

---

Thank you for reviewing my QA portfolio. I’m excited to contribute to teams building high-quality games and interactive experiences.
