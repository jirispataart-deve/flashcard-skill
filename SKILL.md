---
name: "flashcard"
description: "Condenses a term or topic that was already discussed in the conversation into a one-page flashcard: question, core definition, goal, image, examples. Use when the user asks for a flashcard or a short summary of a term from the current context."
---

# Flashcard

Condenses a term or topic that has already been covered in the conversation (or in material the user provided) into a one-page flashcard. The skill does not research or invent content on its own: it distills what is already in the context window. One page, only the essentials: not too little, not too much.

## When to use

- The user asks for a flashcard on a term or topic that came up earlier in the conversation ("Flashcard for X", "Sum up X on a card", "Make a card from this").
- The user gives just a keyword that matches a term from the current context, with no further instruction.

Do not use when the user explicitly asks for a detailed explanation, a comparison, or an analysis, or when the term has not been discussed in the context at all (see special cases).

## Structure of the card

Exactly this order, each as its own paragraph:

1. **Flashcard** (bold heading, always this word)
2. **Question:** the term as a question, in bold. Example: **What is a CRM?**
3. **Core definition:** 1 to 2 sentences. First the expansion or classification of the term (spell out the abbreviation, name the category), then what it does or bundles. Concrete components may go in parentheses.
4. **Goal:** one sentence, starting with "Goal:". What is it for, what should be achieved in the end?
5. **Image:** one sentence with a fitting analogy ("Like a ..."). Only if the analogy truly makes the term more tangible. Otherwise leave it out, never force it.
6. **Examples:** starts with "Examples:" and names 2 to 3 concrete, real representatives, cases or applications, separated by commas. For terms without tangible representatives, use a single "Example:" with one sentence.

## Length and tone

- Roughly 40 to 70 words in total. Better to cut a detail than to pad the card.
- Factual, precise, in plain language. No buzzwords, no filler, no jargon that is not explained on the spot.
- Plain running text in short paragraphs. No bullet points, no tables, no subheadings except the two bold lines at the top.
- Nothing before or after the card: no introduction, no conclusion, no follow-up question, no offer of more.

## Special cases

- **Ambiguous term:** choose the most common meaning. If the second meaning is almost as common in everyday use, set it apart with a short clause in the core definition ("Here in the sense of ...").
- **Several terms at once:** one card per term, each with the heading "Flashcard", separated by a blank line.
- **Term not found in the context:** do not guess or fill the gap with outside knowledge. Say in one sentence that the term has not been covered here and ask which part of the conversation or material it refers to.
- **Context is incomplete or contradictory:** base the card only on what the context supports and leave out the rest.
- **Current or changing facts** (prices, legal status, market leaders): use only what the context states. Do not add new facts unless the user asks for research.

## Example (this is how it should look)

**Flashcard**

**What is a CRM?**

Customer Relationship Management: software that bundles all customer data and contacts of a company in one place (master data, conversation history, offers, sales opportunities).

Goal: Everyone on the team knows who the customer is and what has happened so far. Like a memory of the company that forgets no one, even when staff change.

Examples: Salesforce, HubSpot, Pipedrive.

## Self-check before output

- Does everything fit on one page without scrolling?
- Could someone with no prior knowledge explain the term in one sentence afterwards?
- Is every statement backed by the context? If not: remove it.
- Is every sentence necessary? If not: cut it.
