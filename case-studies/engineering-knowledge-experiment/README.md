# Engineering Knowledge Experiment

This is a sanitized proof-of-work example.

It does **not** expose the underlying knowledge base, source corpus, internal architecture, prompts, indexing strategy, customer information, proprietary code, or product names.

The experiment asks a simple question:

> What changes when years of accumulated engineering material become machine-readable, comparable and reusable with AI?

---

## Example engineering question

How can data from heterogeneous industrial equipment be collected and exposed through a normalized interface?

## Patterns recovered from engineering material

### Pattern 1 — Direct protocol adapter

```text
Equipment
   ↓
Protocol
   ↓
Adapter
   ↓
Normalized data
```

Useful when direct access is available and protocol behavior is understood.

Typical trade-offs:
- vendor-specific implementation;
- protocol differences stay inside the adapter;
- maintenance grows as equipment families grow.

### Pattern 2 — Gateway abstraction

```text
Equipment
   ↓
Protocol
   ↓
Gateway
   ↓
Standard interface
   ↓
Consumers
```

Useful when several consumers need the same equipment data and protocol details should be hidden behind a stable interface.

### Pattern 3 — Edge normalization

```text
Equipment
   ↓
Multiple adapters
   ↓
Edge normalization
   ↓
Canonical model
   ↓
Analytics / enterprise systems / AI
```

Useful when downstream systems should not need to understand individual machine protocols.

---

## What AI changes

The engineering material originally exists in different places:

```text
projects
source code
documentation
product architectures
engineering notes
field observations
```

AI can turn this into another form:

```text
Problem
   ↓
Known approaches
   ↓
Implementation patterns
   ↓
Trade-offs
   ↓
Relevant technologies
   ↓
Evidence
   ↓
Missing knowledge
```

The important point is not that AI invents a new industrial protocol.

It changes the cost of accessing engineering experience.

Knowledge accumulated over years can become searchable, comparable and reusable in seconds.

---

## Gap analysis example

```text
KNOWN
-----
Direct adapters
Gateway architectures
Standardized interfaces
Message-based transport
Edge processing
Canonical data models

PARTIALLY COVERED
-----------------
Schema evolution
Store-and-forward
Device identity
Semantic normalization
Quality metadata

RESEARCH / MISSING
------------------
Cross-vendor semantic mapping
Automated capability discovery
Knowledge provenance
Confidence scoring
```

The exact list is less important than the mechanism: the archive is no longer only storage. It can show what is known, what is weakly supported and what still needs research.

---

## Validation principle

AI-generated engineering knowledge is not automatically treated as fact.

Extracted conclusions should be classified as:

```text
VERIFIED
SUPPORTED
INFERRED
UNKNOWN
```

Where possible, conclusions should trace back to evidence such as:
- documentation;
- source code;
- configuration;
- observed system behavior;
- field evidence.

This matters because fast retrieval without provenance can make wrong engineering knowledge spread faster too.

---

## Before / after

```text
BEFORE

Problem
   ↓
"I remember seeing a solution somewhere..."
   ↓
Folders → documentation → source code → old projects → manual comparison


AFTER

Problem
   ↓
Known approaches → trade-offs → evidence → gaps
```

**Same engineering experience. Different access to it.**

---

## Public boundary

This repository intentionally shows only a generalized output pattern.

Not published:
- names of internal projects;
- names or inventory of analyzed systems;
- source corpus;
- internal taxonomy;
- retrieval/indexing implementation;
- prompts and orchestration;
- proprietary implementation details;
- customer or field information.

The purpose of this page is only to demonstrate the engineering idea and the validation discipline behind it.
