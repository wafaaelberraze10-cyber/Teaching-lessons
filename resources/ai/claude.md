# Claude for English Educators

[Home](../../README.md) / [AI Tools](notebooks.md) / Claude

---

## Table of Contents
1. [Overview](#overview)
2. [Use Cases in the English Classroom](#use-cases-in-the-english-classroom)
3. [Strengths & Weaknesses](#strengths--weaknesses)
4. [Pricing & Free Plan](#pricing--free-plan)
5. [Official Link & Access](#official-link--access)
6. [Best Practices for Teachers](#best-practices-for-teachers)
7. [Example Prompts](#example-prompts)
8. [Classroom Examples](#classroom-examples)
9. [References & Further Reading](#references--further-reading)

---

## Overview
Claude, developed by Anthropic, is a state-of-the-art AI model known for its advanced reasoning, command of linguistic nuances, and massive context window. For English and literature teachers, Claude excels at analyzing long texts, grading complex essays, and designing creative writing activities.

---

## Use Cases in the English Classroom
* **Literary Analysis Assistance:** Processing entire chapters or short stories to extract themes, character arcs, and literary devices.
* **Qualitative Essay Grading:** Analyzing students' analytical essays against a rubric to provide actionable, encouraging feedback.
* **Curriculum Design & Mapping:** Processing curriculum standards to generate aligned unit plans.
* **Creative Writing Models:** Generating high-quality exemplar essays or poetry to demonstrate writing techniques.

---

## Strengths & Weaknesses
### Strengths
* Highly natural, empathetic, and professional writing style (less robotic than standard LLMs).
* Large context window (200k tokens) allows uploading complete student essays, syllabi, or novels.
* Excellent logical reasoning and consistency when matching rubrics.

### Weaknesses
* Free tier usage limits can be restrictive during high-traffic times.
* Lacks a direct, built-in search engine in the core chatbot interface.
* No native image generation capabilities.

---

## Pricing & Free Plan
* **Free Tier:** Access to Claude 3.5 Sonnet with daily rate limits.
* **Claude Pro ($20/month):** 5x more usage capacity, priority access, and early feature releases.
* **Claude Team:** For departments and schools requiring shared workspace environments.

---

## Official Link & Access
* **Official Website:** [https://claude.ai](https://claude.ai)

---

## Best Practices for Teachers
1. **Use XML Tags:** Claude responds exceptionally well to structured parameters. Group your data using tags like `<rubric>` and `<student_essay>`.
2. **Utilize Artifacts:** When generating lesson plans or templates, Claude's "Artifacts" feature displays them in a separate sidebar for easy editing.
3. **Encourage Iterative Feedback:** Ask Claude to first outline its critique before drafting the final response.

---

## Example Prompts

### 1. Rubric-Based Essay Evaluator
* **Purpose:** Grade a student's essay based on standard rubric criteria.
* **Inputs:** 
  * Rubric criteria: Content, Structure, Grammar
  * Student Essay: `Insert text`
* **Prompt:**
  ```text
  Act as an expert high school English teacher. Grade the student essay inside the <student_essay> tags based on the rubric in the <rubric> tags. Provide detailed feedback:
  1. Score for each category with rationale.
  2. Three specific strengths.
  3. Two actionable steps for improvement.
  4. A revised paragraph of their essay demonstrating how to implement your feedback.

  <rubric>
  [Insert Rubric Criteria Here]
  </rubric>

  <student_essay>
  [Insert Essay Here]
  </student_essay>
  ```
* **Expected Output:** Structured evaluation with scoring, actionable feedback, and an exemplar revision.
* **Customization Tips:** Add custom grading styles (e.g., "gentle encouraging tone" or "rigorous AP prep feedback").

---

## Classroom Examples
* **Collective Diagnostic Tool:** Upload five anonymous student essays from a recent assignment. Ask Claude to identify the top three grammatical errors or stylistic issues common across all samples. Use this analysis to design a 10-minute mini-lesson targeting these specific gaps.

---

## References & Further Reading
* Anthropic Portal: [https://anthropic.com](https://anthropic.com)
* Teaching with Claude Guide.
