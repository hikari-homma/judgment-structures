# Judgment Structure

Experimental UI for decision visibility.

## What this is
This is a long-term personal research project.

Judgment Structure is an experimental UI that visualizes **when judgment becomes possible, impossible, or silently deferred**—rather than attempting to “fix” ambiguous requests.

Its purpose is to observe what actually happens during linguistic communication, particularly **instructions and requests within hierarchical relationships**, such as corporate environments or client–worker dynamics.

In the early stages of this research, I assumed that communication problems were primarily caused by **abstract request words** (e.g. “make it feel right,” “from a user perspective”).

However, through iterative observation up to v0.3, I found that **abstract words themselves are not the root cause**.

Instead, the effect of a word emerges from the interaction between:

**word × domain × phase**

Here, *domain* refers to contexts such as product development, meetings, video production, or writing.

*Phase* refers to stages such as planning, design, implementation, or adjustment.

I also realized that **explicit requests**—often assumed to be safer or clearer—produce their own distinct problems.

In other words, the impact of a request is not inherent to whether it is abstract or explicit, but depends on how it interacts with domain and phase.

This project does not attempt to resolve these problems directly.

Instead, it visualizes **where judgment breaks down**, **who is forced to judge**, and **what kind of next action is realistically available**—such as continuing to ask questions, proposing a hypothesis, or stopping observation altogether.

On the other hand, problems caused by external constraints—such as **budget, time, or organizational power structures**—are treated as **structural preconditions**, not communication failures.

These fall outside the scope of this UI and are intentionally not “solved” here.

### **An Experimental UI for Visualizing Where Judgment Breaks**

<p align="center">
<img src="assets/judgment-structure-v1.png" width="720">
</p>

## Judgment Types (v1)

| Type | Name | State | UI Rescue |
|------|------|-------|-----------|
| A | Reference Missing | No reference or comparison axis; judgment cannot be formed | Yes |
| B | Reference-Resolved | Judgment is possible with references, but comparison needs structuring | Yes |
| C | Immediate Comprehension | Judgment is formed directly from the input | Not required |
| D | Structural Mismatch | Structural constraints prevent judgment from being formed | No |
| E | Authority Override | Judgment is overridden by authority or hierarchy | No |
| F | Explanation Avoidance | Judgment exists but explanation is avoided or suppressed | No |
| G | Surface Compliance | Superficial compliance without owning judgment | Partial |

Judgment Types (V1)

A｜Reference Missing

State
Judgment cannot be formed because no reference, comparison axis, or evaluation criteria exist.

Description
The request is abstract, but the core issue is not vagueness itself.
Without any reference point, judgment has no place to anchor and stalls completely.

UI Rescue
Yes — UI can surface missing references and prompt comparison axes.

⸻

B｜Reference-Resolved

State
Judgment is possible because references exist, but clarity can still be improved.

Description
Examples or precedents are provided, enabling judgment to occur.
However, additional comparison or hypothesis framing can reduce cost and ambiguity.

UI Rescue
Yes — UI can organize references and make comparison explicit.

⸻

C｜Immediate Comprehension

State
Judgment is immediately formed from the input alone.

Description
The intent is clear at the moment of input.
No additional reference, clarification, or intervention is required.

UI Rescue
No (Not Required) — Judgment already succeeds without support.

⸻

D｜Structural Mismatch

State
Judgment is blocked by structural constraints rather than language.

Description
Even when intent is understood, constraints such as budget, time, or the nature of the task itself prevent judgment from being meaningfully resolved.

UI Rescue
No — Constraints exist outside the UI layer.

⸻

E｜Authority Override

State
Judgment is overridden by authority, hierarchy, or power relations.

Description
A judgment is formed, but cannot be acted upon because authority enforces a different outcome regardless of reasoning.

UI Rescue
No — This is a power-structure issue, not an information problem.

⸻

F｜Explanation Avoidance

State
Judgment is deliberately not explained.

Description
Explanation is avoided because it is expected to fail, cause conflict, or be emotionally costly.
The decision proceeds without shared understanding.

UI Rescue
No — Rooted in trust, emotion, or relational dynamics.

⸻

G｜Surface Compliance

State
Superficial agreement without taking ownership of judgment.

Description
The responder avoids becoming the judgment主体 and instead offers minimal, surface-level responses to move the situation forward.

UI Rescue
Partial — UI may help clarify roles and responsibility boundaries.


## What this is not

- Not a tool to resolve vague requests
- Not a UX best-practice framework
- Not a decision automation system

## Current status

- Judgment Structure — V1 (Prototype)
- Observational / exploratory
- Structural model of judgment types established
- UI sketches and structure in progress

## Project Materials

This repository also contains supplementary materials:

- `note/` – Personal notes and case observations
- `template/` – Templates used for judgment extraction
