# Jira & Confluence

## What are Jira & Confluence?
- **Jira** is a work management and issue tracking tool for software teams. It organizes **issues** (stories, tasks, bugs) into **backlogs**, **sprints**, and **boards**, enabling planning, tracking, and delivery.  
- **Confluence** is a collaborative documentation platform for creating **pages** inside **spaces**. Teams use it as a knowledge base, documentation hub, and a single place for specs and runbooks.

---

## Why do software teams use them together?
- **Traceability:** Link Jira issues to Confluence specs, runbooks, and decision records.  
- **Visibility:** Confluence explains the “why”; Jira shows the “what/when/who”.  
- **Delivery flow:** Plan in Confluence → track in Jira → document results in Confluence.  
- **Onboarding:** New engineers get context quickly.

---

## Core Concepts & Keywords (Jira)
- **Issue:** A unit of work (Story, Task, Bug, Epic).  
- **Epic:** A large body of work composed of many issues.  
- **Story:** A user-facing requirement, often with acceptance criteria.  
- **Task:** A technical to-do item.  
- **Bug:** A defect that needs fixing.  
- **Backlog:** Ordered list of issues not yet in a sprint.  
- **Sprint:** A fixed timebox (e.g., 2 weeks) where a team commits to deliver items.  
- **Board:** Visual view (Scrum/Kanban) of issues by status/column.  
- **Workflow:** Statuses and transitions an issue follows.  
- **Assignee / Reporter:** Who works on it / who created it.  
- **Priority / Story Points:** Effort/urgency indicators.  
- **JQL:** Jira Query Language for searching issues.

---

## Core Concepts & Keywords (Confluence)
- **Space:** Top-level area grouping related pages.  
- **Page:** A document within a space.  
- **Templates:** Predefined structures (Requirements, Runbook, etc.).  
- **Hierarchy:** Pages with parent/child structure.  
- **Macros:** Dynamic content (TOC, Jira Issues list).  
- **Permissions:** Control access per space/page.  
- **Comments & History:** Collaboration and versioning.  
- **Labels & Attachments:** For organization and supporting files.

---

## Practical Demo: Jira

> Goal: Create a story, plan a sprint, and move it across statuses.  
> Prerequisite: Access to a Jira project.

1. **Create Story**
   - Title: `As a user, I can reset my password`  
   - Description:  
     - Acceptance Criteria: reset email sent, token expires in 15m.  
   - Priority: Medium, Story Points: 3.

2. **Plan in Backlog**
   - Place in Sprint `Sprint 1 (Demo)`.

3. **Start Sprint**
   - Duration: 1–2 weeks.

4. **Work the Issue**
   - Move across `To Do → In Progress → Done`.  
   - Assign to yourself, add a comment.

5. **Add Sub-task**
   - Example: `Implement password reset API`.

6. **Close the Story**
   - Transition to Done, add resolution.