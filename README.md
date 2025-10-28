# 🧠 PROJECT TASK: Virtual Campus Website Development

## 📘 Context

This project is for the **Website Application Development (WAD)** course at Kuwait University, Fall 2025/2026, under Dr. Shariffah Zamoon.  
It’s a team-based assignment where students are developing a full-stack web application for the Kuwait University community.

---

## 🎯 Project Goal

Build a responsive, user-friendly **Virtual Campus** platform that connects **students and graduates** to share academic resources, chat, and access career guidance.

---

## 🧩 Problem Definition

Kuwait University students face several challenges:

1. No unified communication platform for course discussions.
2. Difficulty finding notes, slides, and study materials.
3. Confusion around university dates and academic procedures.
4. Graduates struggle to find relevant skills, certificates, and job opportunities.

The system aims to solve these by integrating:

- Chat rooms for courses and topics.
- AI chatbot to answer university-related questions.
- Centralized study material sharing.
- Career and certification guidance via OSTA.

---

## 👥 Target Users

- **Current University Students**: Need study materials, discussions, and academic support.
- **Recent Graduates**: Need job listings, certifications, and career resources.

---

## 🚀 Core Features

1. **Group Chat Rooms**

   - Real-time chat by topic or course.
   - Organized communication replacing chaotic WhatsApp groups.

2. **AI Chatbot**

   - Powered by OpenAI model.
   - Handles voice commands and FAQs (e.g., “When does registration open?”).

3. **Career Guidance**

   - Job listings and in-demand certifications (HTML, CSS, UI/UX, etc.).
   - Integration with OSTA for workshops and internships.

4. **User Accounts & Profiles**

   - Registration via KU email and ID.
   - Auto-detect major based on student ID.
   - Profile customization (name, bio, photo).

5. **Responsive Design**
   - Optimized for desktop, tablet, and mobile.
   - Bootstrap 5 grid and media queries for layout flexibility.

---

## ⚙️ Functional Requirements

- Users can log in, update profile, and navigate pages.
- Chatbot responds automatically to text queries.
- Career page dynamically suggests roles by major.

---

## 🔐 Non-Functional Requirements

- Secure authentication for users.
- Cross-device compatibility.
- Accessible font sizes, color contrast, and voice support.

---

## 🎨 UX/UI Requirements

- Consistent design (color, typography, and spacing).
- Clear navigation bar and hamburger menu.
- Informative error messages for login and form issues.

---

## 🏗️ Website Structure Overview

| Page                | Description                                                        |
| ------------------- | ------------------------------------------------------------------ |
| **Home**            | Navigation bar, intro, announcements, FAQ highlights, login/signup |
| **Chat Rooms**      | Real-time discussions organized by subjects                        |
| **Profile**         | View/edit name, major, bio, and photo                              |
| **Career Guidance** | Job listings, certifications, internships                          |
| **Contact**         | Feedback and technical support form                                |

---

## 🧰 Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Framework:** Bootstrap 5
- **Interactivity:** Custom JS (popups, dropdowns, input validation)
- **Accessibility:** Media queries, ARIA attributes, responsive layout

---

## 🧭 Navigation Flow

- Full navbar on desktop
- Collapsible hamburger menu on mobile
- Persistent links to:
  - Home
  - Chat Rooms
  - Career Guidance
  - Profile
  - Contact

---

## 🧱 Responsive Design Plan

- Uniform header and footer on all pages.
- Central content container for readability.
- Mobile optimization using media queries.

---

## 🧾 Team Contributions

| Member                               | Role                     | Contribution                                         |
| ------------------------------------ | ------------------------ | ---------------------------------------------------- |
| **Abdulrahman Mahmoud (2211137512)** | Lead Architect           | Target Users, Website Architecture & Navigation Flow |
| **Abdullah Bukoubar (2212171344)**   | UI/UX Designer           | Website Structure                                    |
| **Abdullah Alrashidi (2211124171)**  | Frontend Dev             | Interactivity & Input Handling                       |
| **Yousef Alfarhan (2211123749)**     | Frontend Dev             | Main Features, Responsive Layout                     |
| **Aisha Alsubaie (2212172410)**      | Content & System Planner | Concept, Problem, Technology Stack                   |

---

## 🧩 Development Tasks (for Codex)

### 1️⃣ HTML Structure

- Create base `index.html` (Home page)
- Add linked pages:
  - `chatrooms.html`
  - `career.html`
  - `profile.html`
  - `contact.html`
- Implement shared header/footer across all pages.

### 2️⃣ CSS Styling

- Use Bootstrap 5 base theme.
- Add `style.css` for:
  - Color scheme
  - Font customization
  - Hover transitions

### 3️⃣ JS Interactivity

- Implement chatbot input/output logic.
- Validate form inputs on login/signup.
- Add navigation animations.

### 4️⃣ Responsive Behavior

- Configure Bootstrap grid & media queries.
- Test layout on desktop, tablet, and mobile.
- Ensure accessibility compliance.

### 5️⃣ Testing & Debugging

- Verify navigation links.
- Test AI chatbot prompt-response flow.
- Validate form error messages.

---

## 📦 Deliverables

- Fully functional website (`/project` folder)
- Linked CSS and JS files
- README.md (this file)
- Screenshots or GIFs for demo

---

## 📅 Submission

- Upload to **GitHub Classroom repository**
- Ensure all contributors have commits
- Commit message format: `feat: added [component]`

---

## ✅ Evaluation Criteria

- Completeness (all pages functional)
- Design consistency and accessibility
- Proper use of Bootstrap and responsiveness
- Clean code with comments
- Team collaboration (GitHub commit history)

---
