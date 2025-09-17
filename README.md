# SkillSphereX – AI-Powered Skill Exchange & Learning Platform on Salesforce CRM

**Exchange. Learn. Grow.**

SkillSphereX is a Salesforce-based, AI-powered platform enabling individuals and institutions to exchange, barter, and monetize skills using a credit-based system. AI matches skill providers and seekers, verifies skill quality, and recommends learning paths, while Salesforce CRM manages users, sessions, credits, and dashboards.

---

## Project Overview

### Problem Statement
In today’s fast-changing world, individuals—students, professionals, freelancers—possess valuable skills but lack access to affordable, personalized, and verified learning or mentorship opportunities. Existing platforms focus mainly on paid courses or static content, leaving a gap in peer-to-peer skill exchange.

### Proposed Solution
SkillSphereX creates a unified ecosystem where students, professionals, universities, training centers, and corporates can list skills, discover learning opportunities, and collaborate in a gamified, credit-based environment. Key features include:

- **Skill Listings:** Post skills to teach or learn.  
- **AI Smart Matching:** Recommends best matches based on expertise, availability, and goals.  
- **Credit-Based Economy:** Earn credits for teaching, spend credits to learn.  
- **Gamification & Trust Scores:** Badges, leaderboards, and verified ratings.  
- **Session Booking & Notifications:** Schedule sessions and receive automated reminders.  
- **Dashboards & Analytics:** Real-time visibility of trending skills, credit usage, and engagement metrics.  

---

## Project Implementation Phases

SkillSphereX is implemented following Salesforce best practices, covering both Admin and Developer aspects:

### Phase 1: Problem Understanding & Industry Analysis
- **Requirement Gathering** – Learners, mentors, institutions.  
- **Stakeholder Analysis** – Learners, mentors, admins, institutions.  
- **Business Process Mapping** – Current informal skill exchange → Future AI-matched credit system.  
- **Industry-specific Use Case Analysis** – Peer-to-peer learning, gamified learning ecosystems.  
- **AppExchange Exploration** – Scheduling, gamification, and reward apps.

### Phase 2: Org Setup & Configuration
- Salesforce Edition, Company Profile, Users, Roles, Profiles, Permission Sets, OWD, Sharing Rules, Sandbox setup, Deployment basics.

### Phase 3: Data Modeling & Relationships
- Objects: User, Skill, Session, CreditTransaction, Rating/Badge.  
- Relationships: User ↔ Skill, Skill ↔ Session, User ↔ Session.  
- Page Layouts & Schema Builder for optimal usability.

### Phase 4: Process Automation (Admin)
- Validation Rules, Workflow Rules, Process Builder, Approval Processes, Flow Builder, Email Alerts, Custom Notifications, Field Updates, Tasks.

### Phase 5: Apex Programming (Developer)
- Apex Classes & Triggers, SOQL/SOSL queries, Collections, Scheduled/Queueable/Future Methods, Test Classes.

### Phase 6: User Interface Development
- Lightning App Builder, Record Pages, Tabs, Home Page Layouts, Utility Bar, Lightning Web Components (LWC), Apex with LWC, Events in LWC, Navigation Service.

### Phase 7: Integration & External Access
- Named Credentials, External Services, REST/SOAP Web Services, Callouts, Platform Events, Change Data Capture, Salesforce Connect, API limits, OAuth & Authentication, Remote Site Settings.

### Phase 8: Data Management & Deployment
- Data Import Wizard, Data Loader, Duplicate Rules, Data Export & Backup, Change Sets, Managed/Unmanaged Packages, ANT Migration Tool, VS Code & SFDX.

### Phase 9: Reporting, Dashboards & Security Review
- Reports (Skill Popularity, Engagement, Credit Transactions), Dashboards (Leaderboard, Weekly Engagement, AI Match Insights), Sharing Settings, Field Level Security, Session Settings, Audit Trail.

### Phase 10: Final Presentation & Demo Day
- Pitch Presentation, Demo Walkthrough, Feedback Collection, Handoff Documentation, LinkedIn/Portfolio Showcase.

---

## Project Diagrams

### 1. SkillSphereX Flowchart
![Flowchart](images/flowchart.png)

### 2. Data Model Diagram
![Data Model](images/data_model.png)

---

## Key Performance Indicators (KPIs)
- Number of sessions booked and completed.  
- Credits earned and spent by users.  
- AI match success rate (sessions matched vs completed).  
- User engagement: Active learners, mentors, and institutions.  
- Top trending skills per category.  

---

## Future Scope
- Integration with external certification platforms.  
- Mobile app version for on-the-go skill exchange.  
- Advanced AI recommendations for learning paths.  
- Corporate internal knowledge-sharing module.  
- Social learning features (groups, forums, collaborative projects).

---

## License
This project is for educational purposes as part of the TCS Last Mile Salesforce Capstone Project.

---

