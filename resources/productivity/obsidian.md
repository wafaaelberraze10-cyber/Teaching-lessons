# Obsidian Setup Guide for ELA Educators

[Home](../../README.md) / [Productivity Stack](notion.md) / Obsidian Setup

Obsidian is a private, offline-first markdown editor that uses bi-directional linking. For curriculum designers and literature teachers, Obsidian acts as a personal wiki, connecting authors, historical themes, literary devices, and daily lesson plans.

---

## Table of Contents
1. [The Local Vault Folder Structure](#the-local-vault-folder-structure)
2. [Leveraging Bi-directional Links](#leveraging-bi-directional-links)
3. [Essential Community Plugins](#essential-community-plugins)
4. [Example Obsidian Markdown Note](#example-obsidian-markdown-note)

---

## The Local Vault Folder Structure
Set up your Obsidian Vault using the PARA method folder layout (from [Second Brain](../second-brain.md)):

```
Vault/
  1-Projects/
  2-Areas/
  3-Resources/
    Literature-Notes/
    Vocabulary-Banks/
    Lesson-Components/
  4-Archives/
```

---

## Leveraging Bi-directional Links
The core strength of Obsidian is the double bracket link `[[Page Name]]`. Use this to cross-reference concepts:

* **Author Note:** Create a note `[[George Orwell]]` describing his life.
* **Book Note:** Create a note `[[1984 Novel]]` and link it back to `[[George Orwell]]`.
* **Theme Note:** Create a note `[[Propaganda in Literature]]` and link both `[[1984 Novel]]` and `[[Animal Farm]]` to it.
* **Lesson Note:** When planning a class on propaganda, simply reference `[[Propaganda in Literature]]` to immediately see all connected materials.

---

## Essential Community Plugins
1. **Dataview:** Use queries to display automatic lists of lessons. For example, write a script to show all lessons matching `#grade-10` and `#term-1`.
2. **Templater:** Automate insertion of dates, titles, and structural headings when creating new lecture files.
3. **Canvas:** A visual whiteboard to map out unit connections, plot timelines, or character relationships.

---

## Example Obsidian Markdown Note

```markdown
---
tags: [literature, author, modernism]
created: 2026-07-07
---
# F. Scott Fitzgerald

* **Born:** 1896 | **Died:** 1940
* **Movement:** [[Modernism (Literature)]] | [[The Lost Generation]]

## Major Works
* [[The Great Gatsby Novel]] (1925)
* [[Tender is the Night]] (1934)

## Themes
* The American Dream, Wealth, Decadence
```
