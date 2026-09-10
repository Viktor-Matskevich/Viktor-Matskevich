# From Field Troubleshooting to AI-Assisted Engineering

Industrial connectivity work contains a large amount of tacit knowledge: which test to run next, what evidence is sufficient, how to distinguish network failure from protocol failure, and when a signal interpretation is still only a hypothesis.

The engineering opportunity is to make that knowledge explicit enough that software can assist with the process safely.

## Human-dependent workflow

```text
Engineer
  → recalls prior experience
  → searches manuals
  → checks network
  → tries candidate interfaces
  → interprets results
  → chooses next action
  → documents only part of the reasoning
```

## Structured workflow

```text
Equipment context
      ↓
Capabilities / constraints
      ↓
Permitted diagnostic actions
      ↓
Structured evidence
      ↓
Evaluation rules
      ↓
Recommended next action
      ↓
Human verification where required
```

## What an AI-assisted system should eventually be able to do

- select the next safe diagnostic step from equipment context and current evidence;
- execute read-only checks through permitted tools;
- distinguish verified facts from assumptions;
- explain why a conclusion was reached;
- identify missing evidence;
- produce a reproducible diagnostic report;
- reuse procedures learned from previous machine families without putting vendor-specific logic into the general core.

## What it should not do

- perform writes to industrial equipment by default;
- hide uncertainty behind a single confidence score;
- infer semantic mappings from one observation and treat them as facts;
- require customer-specific credentials or network information in shared knowledge;
- replace verification with model intuition.

## Core design principle

**The AI agent should operate over explicit capabilities, contracts, evidence and permitted actions — not over undocumented tribal knowledge.**

This is the difference between adding a chatbot to an engineering workflow and designing an agentic engineering system.
