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

### 1. Bloom's Taxonomy Lesson Objective Generator
* **Purpose:** Create progressive, measurable learning objectives.
* **Inputs:** Topic, Standards, Grade Level.
* **Prompt:**
  ```text
  Act as a Senior Curriculum Architect. Generate a set of 6 learning objectives for a [Grade Level] English lesson on [Topic / Skill]. Align the objectives to [Standard (e.g., CCSS.ELA-LITERACY.RL.9-10.1)]. Create one objective for each level of Bloom's Taxonomy (Remember, Understand, Apply, Analyze, Evaluate, Create). Ensure all objectives use observable, measurable verbs (e.g., list, explain, contrast, draft).
  ```
* **Expected Output:** Six bulleted objectives categorized by Bloom's Taxonomy levels.
* **Customization Tips:** Request a secondary list of formative checks mapping to each objective.

### 2. Differentiated Reading Text Scaffolder
* **Purpose:** Level a text and generate comprehension aids.
* **Inputs:** Target Text, Student CEFR Levels (e.g., A2, B2).
* **Prompt:**
  ```text
  Act as an expert ESL support teacher. Read the text inside the <source_text> tags. Rewrite this text to make it accessible to a CEFR [CEFR Level] student without losing the key plot points or arguments. Below the rewritten text, provide a vocabulary matching glossary containing 5 high-frequency academic words from the text, with simplified English definitions.
  
  <source_text>
  [Insert Original Text Here]
  </source_text>
  ```
* **Expected Output:** A leveled version of the text followed by a clean vocabulary glossary table.

---

## Grading & Student Feedback

### 1. Constructive Essay Proofreader & Coach
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
* **Expected Output:** Structured evaluation sheet detailing strengths, thesis assessment, and mechanical corrections.

### 2. Analytical Rubric Generator
* **Purpose:** Create custom rubrics for assignments.
* **Inputs:** Assignment Type, Grade Level, Criteria.
* **Prompt:**
  ```text
  Act as a measurement and evaluation specialist. Create a 4-point analytic rubric for a [Grade Level] [Assignment Type (e.g., Persuasive Letter)]. Evaluate the following criteria: [Criteria List (e.g., Claim Development, Evidence, Structure, Mechanics)]. Ensure the descriptors for levels 4 (Exemplary), 3 (Proficient), 2 (Developing), and 1 (Beginning) are detailed, objective, and measurable. Format as a table.
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

### 2. Gamified Retrieval Practice Builder
* **Purpose:** Build game questions for vocabulary or reading checks.
* **Inputs:** Reading Assignment.
* **Prompt:**
  ```text
  Act as a game show designer. Generate 10 multiple-choice questions for a quick reading check on [Chapter/Section]. Each question must have one correct answer and three plausible distractors. Add an "Explanation" field explaining the correct answer referencing the text. Format as a table.
  ```

---

## Administrative & Communication

### 1. Constructive Parent Update Email
* **Purpose:** Draft emails communicating academic or behavioral progress.
* **Inputs:** Student Name, Progress/Behaviors, Call to Action.
* **Prompt:**
  ```text
  Act as an empathetic, professional teacher. Write an email to the parents of [Student Name] discussing [Brief Behavior / Academic Progress Details]. Maintain a collaborative tone. Highlight one positive asset of the student first, state the academic/behavioral area requiring attention, and propose a joint plan of action. Ask for their feedback or a phone meeting.
  ```
* **Expected Output:** An email template ready to send.
