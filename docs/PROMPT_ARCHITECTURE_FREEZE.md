Prompt Architecture Freeze – eduPhysics AI
Version: v1.0  
Status: FROZEN  
Last Updated: 2025-09-27

---

1. Purpose of This Document

This document defines the **frozen prompt architecture** for eduPhysics AI.

- This content is **NOT a runtime prompt**
- This content is **NOT executed inside Google AI Studio**
- This content exists purely for:
  - Governance
  - Scope control
  - Audit reference
  - Developer alignment

Any changes to this document require explicit versioning and review.

---
 2. Frozen Prompt Structure (High-Level)

eduPhysics AI uses a **single-instruction runtime model** with the following separation:

 Runtime Prompts (Executed)

- Prompt 1: Role & Identity Definition  
- Prompt 2: Academic Scope & Constraints  
- Prompt 3: Response Structure & Pedagogy  
- Prompt 4: Interaction Flow & Guardrails  

These prompts are:
- Implemented inside Google AI Studio
- Executed using **Gemini 2.5 Flash**
- Locked after initial validation

---

 3. Governance Prompts (NOT Executed)

The following prompts are **governance-only**:

- Prompt 5: Architecture Freeze & Scope Lock  
- Prompt 6: Safety, Security & Deployment Constraints  

These prompts:
- MUST NOT be pasted into AI Studio
- MUST NOT be embedded in frontend or backend code
- MUST NOT be executed by any LLM

They exist only as **human-readable control documents**.

---

 4. Scope Lock Declaration

The eduPhysics AI system is permanently constrained to:

- CBSE-aligned Physics only  
- Classes 9–12  
- Conceptual understanding  
- Practical experiments  
- Viva voce preparation  
- Exam-oriented reasoning (NEET-aware, not coaching)

Explicitly excluded:

- Non-academic content  
- Open internet browsing  
- Cross-subject tutoring  
- Psychological, medical, or legal advice  

---

 5. Change Control Policy

Any of the following actions REQUIRE a new version of this document:

- Adding new subjects  
- Expanding beyond CBSE  
- Allowing free-form chat  
- Storing personal student data  
- Modifying safety boundaries  

Until such a version is approved, the architecture remains **final and frozen**.

---

 6. Authority Statement

This document supersedes:

- Chat-based instructions  
- Ad-hoc prompt experiments  
- Unversioned prompt changes  

This is the **single source of truth** for eduPhysics AI prompt architecture.

---
