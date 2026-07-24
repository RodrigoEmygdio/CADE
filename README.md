# CADE Engineering Manifesto

Version: 1.0

---

# Purpose

CADE (Collaborative AI-Driven Engineering) is an engineering methodology for AI-assisted software development.

Its objective is not merely to generate software.

Its objective is to preserve engineering knowledge while software evolves.

Every implementation should improve—not degrade—the long-term integrity of the system.

---

# Principle 1

Engineering before implementation.

Implementation is a consequence of engineering.

Never optimize implementation by sacrificing engineering quality.

---

# Principle 2

Knowledge is a first-class artifact.

Engineering knowledge is as valuable as source code.

Architecture, requirements, ADRs, traceability, metadata and contracts are engineering assets that must evolve together.

---

# Principle 3

Engineering knowledge has ownership.

Every engineering fact has exactly one canonical authority.

Derived documents must reference—not replace—the canonical source.

Single Source of Truth applies to engineering knowledge.

---

# Principle 4

Architecture precedes implementation.

Code implements architecture.

Architecture must never emerge accidentally from implementation.

---

# Principle 5

Every decision requires evidence.

Engineering decisions must be traceable to:

- requirements;
- experiments;
- measurements;
- notebooks;
- ML evaluation;
- ADRs;
- approved discussions.

Opinion is never sufficient architectural evidence.

---

# Principle 6

Contracts before behavior.

Every system boundary should be defined by explicit contracts.

Contracts reduce ambiguity.

Contracts enable deterministic AI-assisted development.

---

# Principle 7

Determinism over convenience.

When deterministic behavior is possible, prefer deterministic behavior.

AI reasoning complements engineering.

It does not replace deterministic logic.

---

# Principle 8

Responsibilities over implementation.

Describe responsibilities.

Avoid prescribing implementation.

Implementation evolves.

Responsibilities endure.

---

# Principle 9

Engineering is layered.

Every responsibility belongs to one layer.

Typical layers include:

Input

↓

Validation

↓

Transformation

↓

Prediction

↓

Decision

↓

Interpretation

↓

Recommendation

↓

Presentation

A layer must not perform responsibilities belonging to another layer.

---

# Principle 10

Documentation is executable knowledge.

Documentation exists to guide engineering.

It is not a historical archive.

Documentation must evolve with implementation.

---

# Principle 11

Traceability is mandatory.

Every important engineering decision should answer:

Why?

Where?

When?

By whom?

Based on what evidence?

---

# Principle 12

Governance preserves quality.

Engineering quality is maintained through governance.

Governance coordinates:

- architecture;
- implementation;
- documentation;
- requirements;
- traceability;
- testing.

Governance does not replace engineering.

It protects engineering.

---

# Principle 13

AI augments engineering.

AI is an engineering collaborator.

The human remains responsible for:

- architectural intent;
- business understanding;
- ethical decisions;
- final approval.

---

# Principle 14

Knowledge must survive implementation.

A repository should remain understandable even if every implementation file is rewritten.

Engineering knowledge must outlive code.

---

# Principle 15

Continuous consistency.

Every repository evolution should reduce inconsistency.

Never knowingly introduce contradictory engineering knowledge.

Consistency is an engineering quality attribute.

---

# Definition of Done

An engineering task is complete only when:

- implementation is correct;
- contracts are preserved;
- architecture remains valid;
- documentation is synchronized;
- traceability is updated;
- requirements remain consistent;
- tests validate behavior;
- governance validation succeeds.

Code alone is never "done".
