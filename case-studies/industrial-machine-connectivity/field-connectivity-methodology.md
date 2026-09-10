# Field Connectivity Methodology

This document describes a vendor-neutral method for investigating industrial machine connectivity without exposing production implementation or field-specific configuration.

## Objective

The objective is to move from an unknown or partially documented industrial interface to a reproducible, evidence-backed connection procedure.

## Investigation sequence

### 1. Establish equipment context

Record only the information required to guide the investigation:

- equipment/controller family;
- expected network interface;
- known standard or vendor interfaces;
- intended data use;
- safety and authorization constraints.

### 2. Verify network reachability

Confirm basic network conditions before protocol debugging:

- interface/link state;
- route/subnet correctness;
- host reachability when supported;
- expected service reachability;
- local firewall or endpoint restrictions.

A network failure and a protocol failure should never be reported as the same problem.

### 3. Discover candidate data sources

Prefer targeted discovery based on known equipment capabilities. Broader scanning should be explicit rather than the default.

Candidate sources may include standard industrial interfaces, controller APIs, local gateways or vendor services.

### 4. Acquire a read-only sample

The first successful acquisition should minimize risk and answer a narrow question: **is this a real, stable source of machine data?**

At this stage, receiving data is evidence of transport availability, not proof of semantic correctness.

### 5. Validate structure and timing

Evaluate:

- frame/message consistency;
- schema or field stability;
- timestamps;
- update frequency;
- missing values;
- obvious corruption or transport errors.

### 6. Evaluate completeness

Completeness is use-case dependent. A source can be technically valid but insufficient for production monitoring, diagnostics or analytics.

Define a requirement profile and evaluate whether the available signals satisfy it.

### 7. Validate semantics

Signal names, numeric values or vendor labels should not be trusted blindly. Compare candidate meanings with observable machine behavior and independent evidence.

### 8. Produce reproducible diagnostics

A useful report should contain:

- what was tested;
- what succeeded;
- what failed;
- evidence supporting each conclusion;
- unresolved assumptions;
- next recommended safe action.

### 9. Capture reusable knowledge

Convert successful steps into structured procedures, diagnostic rules and capability descriptions so future investigations start from accumulated knowledge rather than from zero.

## Key principle

**A field connection is complete only when another engineer can reproduce the result and understand the evidence behind it.**
