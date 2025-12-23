# Acadence
A context-aware academic planning assistant that leverages Google Classroom data to help students organize assignments, detect workload clashes, and plan ahead effectively
# ClassPlan

ClassPlan is a context-aware academic productivity assistant designed to help students plan and manage their academic workload more effectively by leveraging data from Google Classroom.

Rather than replacing existing academic platforms, ClassPlan complements them by transforming assignment information into actionable planning insights that help students avoid last-minute pressure and workload clashes.

---

## Problem Statement

Students often experience academic stress not due to lack of effort, but due to poor visibility into overlapping assignments, unrealistic planning, and last-minute workload clustering.  
While platforms like Google Classroom centralize academic tasks, they do not assist students in understanding *when* and *how* to work on those tasks in a balanced and sustainable manner.

ClassPlan addresses this gap by organizing assignment data contextually and assisting students in planning their work ahead of time.

---

## Project Goals

- Provide students with clear visibility into upcoming academic workload
- Identify overlapping deadlines and high-load periods
- Assist students in planning assignments early to reduce last-minute stress
- Support informed decision-making without automating or enforcing academic choices

---

## Key Features

- Google Classroom integration (read-only)
- Assignment and deadline aggregation
- Workload overlap detection
- Suggested planning timelines
- User-in-the-loop scheduling decisions
- Optional AI-based planning insights

---

## Technology Stack

- **Frontend:** React.js
- **Backend:** Node.js + Express
- **Authentication:** Google OAuth (via Firebase Auth)
- **Database:** Firebase Firestore
- **Google APIs:** Google Classroom API
- **AI (Optional):** Gemini API

---

## Scope & Limitations

### In Scope
- Read-only access to Google Classroom assignments and metadata
- Planning assistance and scheduling suggestions
- User-controlled inputs for effort estimation and availability

### Out of Scope
- Modifying Google Classroom data
- Submitting assignments on behalf of users
- Automatic academic decision-making
- Stress elimination guarantees

---

## Architecture Overview

1. User authenticates via Google
2. Assignment data is fetched from Google Classroom
3. User provides effort estimates and availability
4. System generates a balanced planning timeline
5. Optional AI layer provides workload insights

---

## Setup Instructions (To be updated)



---

## Future Enhancements

- Improved workload prediction
- Enhanced AI planning insights
- Calendar integration
- Cross-platform academic data support

---

