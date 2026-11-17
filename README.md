# flashcard-skill

A learning aid for Claude. It turns a term or topic that has already been discussed in the conversation into a one-page flashcard: a question plus a clear, informative answer.

## What it does

The skill does not research or invent anything. It distills what is already in the context window into a compact card with a fixed structure: the question (the term, phrased as a question), a core definition in 1 to 2 sentences, the goal (what it is for), an optional image (a short analogy, only if it really helps), and 2 to 3 concrete examples.

A card is roughly 40 to 70 words, written in plain language, with nothing before or after it.

## Example

**Flashcard**

**What is a CRM?**

Customer Relationship Management: software that bundles all customer data and contacts of a company in one place (master data, conversation history, offers, sales opportunities).

Goal: Everyone on the team knows who the customer is and what has happened so far. Like a memory of the company that never forgets, even when staff change.

Examples: Salesforce, HubSpot, Pipedrive.

## Installation

Put the SKILL.md file into a folder named flashcard inside your Claude skills directory (or upload it as a skill in your Claude settings). Then ask for it, for example: "Flashcard for X".

## Notes

It works best after a topic has been explained in the chat or in material you provided. It is not meant for long explanations, comparisons or analyses.
