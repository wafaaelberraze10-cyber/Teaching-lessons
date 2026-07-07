# Notion Setup Guide for ELA Educators

[Home](../../README.md) / [Productivity Stack](notion.md) / Notion Setup

Notion is a powerful, highly customizable workspace application. This guide outlines how to build a unified teacher dashboard, curriculum maps, and lesson planners using Notion databases.

---

## Table of Contents
1. [The Teacher Dashboard Layout](#the-teacher-dashboard-layout)
2. [Curriculum Database Setup](#curriculum-database-setup)
3. [Weekly Lesson Planner Database](#weekly-lesson-planner-database)
4. [Best Practices for Teachers](#best-practices-for-teachers)

---

## The Teacher Dashboard Layout
Design a centralized page in Notion called **Teacher HQ** with three primary blocks:

* **Left Column: Quick Links & Routines**
  - Daily Prep Checklist (linked from [Teaching Systems](../teaching-systems.md))
  - Attendance rosters
  - Link to LMS (Canvas/Google Classroom)
* **Center Column: Weekly Schedule View**
  - A calendar database view displaying current week's lesson cards.
* **Right Column: Active Projects**
  - Ongoing curriculum reviews or grading tasks.

---

## Curriculum Database Setup
Create a **Master Curriculum Database** with the following custom properties:

```
[Row Example] ──► Name: Macbeth Unit │ Grade: 10 │ Term: Fall │ Status: Active │ Standards: CCSS.ELA-RL.10
```

1. **Name:** Name of the unit.
2. **Grade Level:** Tag property (Grade 9, Grade 10, Grade 11).
3. **Term:** Select property (Term 1, Term 2, etc.).
4. **Status:** Select property (Planned, In Progress, Complete).
5. **Standards:** Multi-select property (CCSS, CEFR tags).

---

## Weekly Lesson Planner Database
Create a secondary **Lesson Database** and link it to your Master Curriculum Database using a **Relation** property. This allows you to open any lesson card and immediately see which unit it belongs to.

### Essential Card Properties:
* **Date:** Date of delivery.
* **Class Period:** Multi-select (Period 1, Period 3, etc.).
* **Objectives:** Text property containing the learning target.
* **Materials Needed:** Link property pointing to slides or PDFs.
* **Exit Ticket Score:** Number property tracking student pass rate.

---

## Best Practices for Teachers
1. **Apply for Notion Education Plus:** Get a free premium upgrade using your official school email (.edu or equivalent).
2. **Use Database Templates:** Build template pages for your lessons so that creating a new lesson card automatically inserts headers for Warm-up, Direct Instruction, and Exit Ticket.
3. **Link, Don't Duplicate:** Instead of recreating tables, use Notion's "Linked Database View" to display the same data in calendar, list, or Kanban formats.
