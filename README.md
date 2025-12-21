# Shared Professional Guidelines

A collection of comprehensive workplace guidelines covering feedback, managing up, leadership, strategic thinking, and written communication. These guidelines are designed to be used as Cursor rules or reference materials for professional interactions and decision-making.

## Overview

This repository contains evidence-based frameworks and principles for effective workplace communication, management, and strategic thinking. Each guide synthesizes best practices from industry leaders and provides actionable frameworks with examples, checklists, and key takeaways.

## Guidelines

### 1. [Feedback: Giving and Receiving](feedback.md)
**When to apply:** When giving feedback to anyone (upward to managers or downward to direct reports)

**Core principle:** Strategy, not self-expression. Only say what will encourage behavior change.

**Key topics:**
- Giving feedback upward to senior leaders (the "even more" technique, using yourself as an example, diplomatic language)
- Giving feedback downward to direct reports (strategy vs self-expression, framing weaknesses as shadow side of strengths, task-relevant maturity)
- Universal feedback principles (timing, context, being concrete and concise)

### 2. [Managing Up: Principles and Practices](managing-up.md)
**When to apply:** When working with or communicating to managers and senior leaders

**Core principle:** Managing up means being a competent operator who follows through, communicates appropriately, and drives toward business goals.

**Key topics:**
- 15 core principles (focus on punchline, show thought process, flag issues proactively, bring solutions)
- Understanding power dynamics (structural relationships, assessing leverage)
- Techniques for giving feedback upward

### 3. [Management and Leadership: Leading Direct Reports](management-leadership.md)
**When to apply:** When managing, coaching, or leading direct reports

**Core principle:** Be both empathetic and real with your people.

**Key topics:**
- Empathetic management without becoming a therapist
- Creating a culture of rigorous thinking
- Performance reviews and feedback (strategy vs self-expression, taking responsibility, framing feedback)

### 4. [Strategic Thinking: Assertions and Rigorous Thinking](strategic-thinking.md)
**When to apply:** When developing ideas, making recommendations, or thinking through problems

**Core principle:** An insight is just a starting point. The rare, courageous thing to do is to develop an assertion—a hypothesis and point of view that answers "so what?"

**Key topics:**
- Moving from insights to suggestions to assertions
- Rigorous thinking frameworks (18 questions to promote rigorous thinking)
- Creating a culture of rigorous thinking
- Why assertions take courage

### 5. [Writing Guide: Concise and Clear Communication](writing-guide.md)
**When to apply:** When a document is intended for internal stakeholders

**Core principle:** The goal of being concise is to create understanding as quickly and easily as possible.

**Key topics:**
- Preparation and structure (main point above, context below)
- Rigorous thinking in writing (questioning assumptions, anticipating objections)
- What to avoid (chronological narratives, too much technical detail, being too concise)
- Techniques for clarity (signposting, offering to elaborate, situational awareness)
- Fixing limbo writing (clarifying ideas, finishing thoughts, stating assumptions)

## How to Use These Guidelines

Each guideline file contains:
- **Frontmatter** with description and `alwaysApply` flag for Cursor rules
- **Core principle** that guides all recommendations
- **Detailed frameworks** with examples of what to do and what to avoid
- **Quick reference checklists** for practical application
- **Key takeaways** for quick review
- **Sources** documenting where principles come from

### As Cursor Rules

These files are formatted to work as Cursor rules. The frontmatter includes:
- `description`: When to apply the guideline
- `alwaysApply`: Whether to always apply (currently `false` for all, meaning they should be applied contextually)

### As Reference Materials

Each guide can be used as a standalone reference when:
- Preparing for difficult conversations
- Writing stakeholder communications
- Conducting performance reviews
- Making strategic recommendations
- Managing up or managing down

## Adding New Guidelines

When adding a new guideline to this repository:

1. **Create the guideline file** (e.g., `new-topic.md`) in the root directory
2. **Include frontmatter** with:
   ```yaml
   ---
   description: When to apply this guideline
   alwaysApply: false
   ---
   ```
3. **Follow the structure** of existing guidelines:
   - Title and brief description
   - Core principle
   - Detailed sections with examples
   - Quick reference checklist
   - Key takeaways
   - Sources (if applicable)
4. **Update this README** by:
   - Adding a new entry in the "Guidelines" section above
   - Following the same format (number, filename, when to apply, core principle, key topics)
   - Maintaining the numbered list

### Example: Adding a New Guideline

If you add `conflict-resolution.md`, update the README like this:

```markdown
### 6. [Conflict Resolution: Principles and Practices](conflict-resolution.md)
**When to apply:** When navigating disagreements or conflicts in the workplace

**Core principle:** [Core principle here]

**Key topics:**
- [Topic 1]
- [Topic 2]
- [Topic 3]
```

## Project Structure

```
shared-rules/
├── README.md                    # This file
├── feedback.md                  # Feedback: Giving and Receiving
├── managing-up.md              # Managing Up: Principles and Practices
├── management-leadership.md    # Management and Leadership: Leading Direct Reports
├── strategic-thinking.md       # Strategic Thinking: Assertions and Rigorous Thinking
└── writing-guide.md            # Writing Guide: Concise and Clear Communication
```

## Sources

These guidelines synthesize principles primarily from:
- **Wes Kao's Newsletter** - Articles on management, communication, and strategic thinking
- Industry best practices and frameworks
- Evidence-based approaches to workplace effectiveness

Each individual guide includes detailed source citations at the end.

---

*Last updated: When new guidelines are added, update this README to reflect the current state of the repository.*

