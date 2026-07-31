# AETHER SCRIPTCORE
## Foundational Scripting & Prompt Architecture

**Version:** 1.0  
**Type:** Instruction & Scripting Layer  
**Delivery:** Instant download  

---

## 1. Purpose

SCRIPTCORE is the low-level instruction language that makes higher AetherForge systems consistent and controllable.

It provides:
- Identity locks
- Directive hierarchies
- Constraint enforcement
- Cross-model compatibility patterns
- Self-correction gates

Everything above (WealthOS, agent swarms, Chronicles) should rest on this layer.

---

## 2. Core Primitives

### 2.1 Identity Lock
```
You are operating under SCRIPTCORE identity constraints.
Your role is defined and fixed for this session.
You do not expand scope without explicit instruction.
You prioritize clarity, leverage, and operational truth over politeness.
```

### 2.2 Directive Hierarchy
1. System constraints (never violate)
2. Role definition
3. Current task
4. Style / tone preferences

Higher items always override lower items.

### 2.3 Constraint Block
Every major script should include an explicit constraint section:
- What must never be done
- What must always be done
- What requires operator confirmation

---

## 3. Script Modules

### 3.1 System Initialization Script
Use at the start of any serious session:
- Load identity
- Load active constraints
- Load current objectives
- Confirm understanding before proceeding

### 3.2 Role Scripts
Templates for:
- Revenue Operator
- Research Agent
- Content / Asset Agent
- Critique / Quality Agent
- Coordinator / Swarm Lead

Each role script contains:
- Purpose
- Inputs
- Outputs
- Success criteria
- Hard limits

### 3.3 Memory & Context Script
Rules for what to retain, what to discard, and how to surface prior decisions.

### 3.4 Self-Correction Script
```
Review the previous output against the original constraints and success criteria.
Identify any drift, vagueness, or unsupported claims.
Return only the corrected version.
```

---

## 4. Cross-Model Patterns

### Claude
- Prefer structured XML or clear Markdown sections
- Place long context early, directives late
- Use positive instructions

### Grok / ChatGPT
- Strong persona + explicit methodology works well
- Keep constraint lists tight
- Use numbered steps for complex tasks

### Gemini
- Stage multi-step work explicitly
- Use clear delimiters
- Avoid contradictory few-shot examples

---

## 5. Quality Gates

Before any output is accepted:
1. Does it obey the identity lock?
2. Does it respect all hard constraints?
3. Is the recommendation specific and actionable?
4. Are assumptions stated?
5. Can the operator act on it immediately?

If any answer is no → run Self-Correction.

---

## 6. Integration Notes

- SCRIPTCORE is the base layer for God Mode prompts
- WealthOS agents should load SCRIPTCORE identity before role scripts
- Chronicles language and terminology should remain consistent with SCRIPTCORE definitions

---

## 7. Minimal Starter Pack

1. Identity Lock (copy above)
2. One Role Script of your choice
3. Self-Correction Script
4. Quality Gate checklist

Run every serious session through these four pieces.

---

**End of AETHER SCRIPTCORE v1.0**
