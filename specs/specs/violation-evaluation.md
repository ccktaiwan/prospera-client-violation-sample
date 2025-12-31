# Violation Evaluation

## Evaluated Repository

- Repository: prospera-client-violation-sample
- URL: https://github.com/ccktaiwan/prospera-client-violation-sample
- Origin: Generated from client-repo-template

This repository is intentionally constructed to demonstrate governance violations
for validation purposes.

---

## Detected Violations

### Violation 1: Non-Delegable Authority Breach

**Location**
- specs/auto_decision.md

**Description**
A non-delegable decision authority is assigned to an AI system within the
specification layer.

**Rule Breached**
- Non-delegable authority must remain human-authorized.
- Specifications are human-authoritative and may not finalize or approve decisions via AI.

**Impact**
This violation invalidates governance adoption by transferring final decision
authority away from responsible humans.

---

### Violation 2: Phase Boundary Violation (Architecture)

**Location**
- architecture/

**Description**
Executable or execution-implying artifacts are present within the architecture phase.

**Rule Breached**
- Architecture phase must describe structure and intent only.
- No executable logic or behavior definition is permitted at this phase.

**Impact**
This violation breaks phase separation and undermines governance enforceability.

---

## Validation Result

**Status: FAIL**

The evaluated repository does not comply with Prospera OS governance requirements.

Governance adoption claims made by this repository are invalid.

---

## Enforcement Action

- Validation rejected
- Governance adoption declaration considered void
- Remediation required before revalidation

---

## Reference

This evaluation is performed against the external Prospera OS governance framework.
This repository acts solely as a validation and enforcement reference and does not
define governance rules itself.

End of Document
