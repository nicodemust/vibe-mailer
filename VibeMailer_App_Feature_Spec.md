# VibeMailer – Feature Definitions

## ⚙️ Required Features and Their Goals

### 1. Landing Page
- **Goal:** Serve as the entry point for all users, introducing the product and guiding them to register, log in, or reset a password.
- **Requirements:**
  - Clear CTA buttons for registration, login, and password reset
  - Lightweight, responsive design

---

### 2. User Registration
- **Goal:** Collect basic user information and create a new account for personalized content delivery.
- **Inputs:** First name, last name, email address, password
- **Outcome:** Create user record; redirect to login or dashboard

---

### 3. User Login
- **Goal:** Authenticate returning users and grant access to their dashboard.
- **Inputs:** Email and password
- **Outcome:** Start user session and redirect to dashboard

---

### 4. Password Reset
- **Goal:** Allow users to regain access if they've forgotten their password.
- **Process:**
  - Input: User email
  - Backend checks if email exists
  - If yes → Send new password by email
  - Show confirmation or error message accordingly

---

### 5. User Dashboard
- **Goal:** Central hub where users manage their account and projects.
- **Views/Actions:**
  - List of user projects
  - Account settings access
  - Buttons to create/edit/delete projects

---

### 6. Edit Account Details
- **Goal:** Let users keep their personal information and email preferences up to date.
- **Fields:**
  - First name, last name
  - Account login email
  - Destination email for content delivery

---

### 7. Delete Account
- **Goal:** Allow users to fully remove their presence from the platform.
- **Process:** Confirmation prompt → Permanent deletion of user and all associated projects

---

### 8. Create Project
- **Goal:** Let users define what kind of content they want and how often they want to receive it.
- **Inputs:**
  - Prompt (e.g., “Write a tweet about AI in education”)
  - Frequency (e.g., daily, every 3 days, weekly)
- **Outcome:** Store project, start scheduling content generation and delivery

---

### 9. Edit Project
- **Goal:** Let users modify the content prompt or frequency.
- **Inputs:** Same as project creation, but pre-filled
- **Outcome:** Update project settings; reschedule content delivery

---

### 10. Delete Project
- **Goal:** Remove a specific content delivery setup.
- **Outcome:** Stop future content generation and remove project from user view