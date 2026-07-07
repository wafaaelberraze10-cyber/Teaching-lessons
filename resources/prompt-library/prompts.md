# ELA & ESL Prompt Library

[Home](../../README.md) / Prompt Library

This prompt library provides structured, production-ready prompts designed for English, ESL, and EFL educators. Each prompt utilizes clear parameters (indicated by square brackets like `[Grade Level]`) to make them easily customizable.

---

## Table of Contents
1. [Curriculum & Lesson Design](#curriculum--lesson-design)
2. [Grading & Student Feedback](#grading--student-feedback)
3. [Vocabulary & Grammar Systems](#vocabulary--grammar-systems)
4. [Active Classroom Activities](#active-classroom-activities)
5. [Administrative & Communication](#administrative--communication)

---

## Curriculum & Lesson Design

### 1. Reading Differentiation & Scaffolding (CEFR A2/B1/B2)
* **Purpose:** Rewrite a complex reading text at three distinct CEFR levels with questions and vocabulary.
* **Inputs:** Academic Reading Passage.
* **Prompt:**
  ```text
  You are an expert instructional designer. Here is a complex academic reading passage: [Paste Text]. Rewrite this text at three distinct reading levels: CEFR A2, B1, and B2. You must retain the core narrative structure and primary factual data across all versions. For each level, generate three comprehension questions (one literal recall, one inferential, and one evaluative). Finally, identify and bold the five most critical target vocabulary words appropriate for each tier, providing a brief glossary at the end of each text.
  ```
* **Expected Output:** Three differentiated reading texts, each with three comprehension questions and a vocabulary glossary.

### 2. Bloom's Taxonomy Lesson Objective Generator
* **Purpose:** Create progressive, measurable learning objectives.
* **Inputs:** Topic, Standards, Grade Level.
* **Prompt:**
  ```text
  Act as a Senior Curriculum Architect. Generate a set of 6 learning objectives for a [Grade Level] English lesson on [Topic / Skill]. Align the objectives to [Standard (e.g., CCSS.ELA-LITERACY.RL.9-10.1)]. Create one objective for each level of Bloom's Taxonomy (Remember, Understand, Apply, Analyze, Evaluate, Create). Ensure all objectives use observable, measurable verbs (e.g., list, explain, contrast, draft).
  ```

---

## Grading & Student Feedback

### 1. Rubric-Based Essay Feedback (Constructive Alignment)
* **Purpose:** Generate discrete scores and text-backed feedback from a rubric.
* **Inputs:** Rubric, Student's Essay text.
* **Prompt:**
  ```text
  You are grading a 10th-grade persuasive essay against the following specific rubric: [Paste Rubric]. Here is the student's submitted text: [Paste Text]. Your task is to provide a discrete score for each row of the rubric, accompanied by exactly one sentence of direct evidence quoted from the student's text to justify the score. Next, identify two specific structural or argumentative strengths. Finally, identify the single most critical area for improvement that the student should focus on in their next draft. Frame all feedback directly TO the student in a warm, constructive tone suitable for a 10th-grade reading level. Do not invent details, hallucinate facts, or provide feedback on criteria not present in the rubric.
  ```
* **Expected Output:** Score breakdowns, evidence quotes, strengths, and one focus improvement area.

### 2. Constructive Essay Proofreader & Coach
* **Purpose:** Provide supportive, structured feedback on student writing drafts.
* **Inputs:** Student Draft, Assignment Prompt.
* **Prompt:**
  ```text
  Act as a supportive, constructive writing coach. Review the student essay draft in the <student_draft> tags, written in response to the prompt: "[Insert Writing Prompt Here]".
  Provide feedback structured as follows:
  1. Praise: Two specific strengths of the argument or style.
  2. Structure & Thesis: Evaluate the clarity of the thesis and essay organization.
  3. Actionable Fixes: Outline two high-priority grammar or mechanical patterns they should edit, providing one example from their essay for each.
  Do not write the essay for them. Provide feedback in a encouraging, professional tone.
  
  <student_draft>
  [Insert Student Draft Here]
  </student_draft>
  ```

---

## Vocabulary & Grammar Systems

### 1. Contextual Vocabulary Builder
* **Purpose:** Generate reading passages highlighting target vocabulary.
* **Inputs:** Word List, Target Grade.
* **Prompt:**
  ```text
  Act as an ELA textbook author. Write a cohesive, engaging narrative passage (under 250 words) suitable for a [Grade Level] class that naturally incorporates these vocabulary words: [Word 1, Word 2, Word 3, Word 4]. Underline each target word in the text. Following the passage, write one context-clue multiple-choice question for each vocabulary word.
  ```

---

## Active Classroom Activities

### 1. Socratic Seminar Discussion Prompts
* **Purpose:** Generate high-level open-ended discussion questions.
* **Inputs:** Text Title, Theme.
* **Prompt:**
  ```text
  Act as a facilitator of Socratic dialogue. Generate five open-ended discussion prompts based on [Text Title] focusing on the theme of [Theme (e.g., ambition)]. The questions must require students to reference textual evidence and connect the novel's themes to contemporary society.
  ```

---

## Administrative & Communication

### 1. Empathetic Parent Homework Communication
* **Purpose:** Write a short, empathetic email to a parent about homework drops.
* **Inputs:** Child Details.
* **Prompt:**
  ```text
  Draft a short, empathetic email to a parent regarding their child's recent drop in homework submission over the past two weeks. You must lead with a specific, genuine compliment about the student's active participation during in-class speaking activities. Suggest one concrete, highly manageable next step that we can take collaboratively to support the student at home. Keep the tone collaborative and supportive, strictly avoiding any educational jargon or language that could induce guilt. Limit the entire email to under 150 words.
  ```
* **Expected Output:** An email under 150 words with a compliment, homework status, and collaborative next steps.
