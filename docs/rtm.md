# Final Requirement Traceability Matrix

## Functional Requirements

| Requirement ID | Related Use Case | Validation ID |
|---|---|---|
| FR-01 | UC-S01 | VAL-F01 |
| FR-02 | UC-T01 | VAL-F01 |
| FR-03 | UC-A01, UC-A02, UC-A03, UC-A05 | VAL-F01, VAL-F15, VAL-F16, VAL-F18 |
| FR-04 | UC-T05 | VAL-F04 |
| FR-05 | UC-T02 | VAL-F02 |
| FR-06 | UC-T03 | VAL-F03 |
| FR-07 | UC-T04 | VAL-F13 |
| FR-08 | UC-T06 | VAL-F04 |
| FR-09 | UC-S03, UC-X02 | VAL-F05 |
| FR-10 | UC-S03, UC-X02 | VAL-F05 |
| FR-11 | UC-S03, UC-S04 | VAL-F06 |
| FR-12 | UC-S04 | VAL-F06 |
| FR-13 | UC-S05 | VAL-F12 |
| FR-14 | UC-S06 | VAL-F07 |
| FR-15 | UC-S06 | VAL-F07 |
| FR-16 | UC-X03 | VAL-F08 |
| FR-17 | UC-X03 | VAL-F08 |
| FR-18 | UC-S06 | VAL-S11 |
| FR-19 | UC-S07, UC-X04 | VAL-F09, VAL-F10 |
| FR-20 | UC-T07, UC-A04 | VAL-F14 |
| FR-21 | UC-S02 | VAL-F11 |
| FR-22 | UC-A06 | VAL-F20 |
| FR-23 | UC-A03 | VAL-F21 |
| FR-24 | UC-A05 | VAL-F22 |

## Non-Functional Requirement Traceability

| Requirement ID | Validation ID | Status / Note |
|---|---|---|
| NFR-01 | VAL-N01 | Proposed team NFR |
| NFR-02 | VAL-N02 | Proposed team NFR |
| NFR-03 | VAL-N03 | Measurable target: ≤3 seconds under normal load |
| NFR-04 | VAL-N04 | Proposed team NFR |
| NFR-05 | VAL-N05 | Proposed team NFR |
| NFR-06 | VAL-N06 | Proposed 5-minute target; team approval required |
| NFR-07 | VAL-N07 | Proposed team NFR |
| NFR-08 | VAL-N08 | Proposed team NFR |
| NFR-09 | VAL-N09 | Proposed team NFR |
| NFR-10 | VAL-N10 | Proposed team NFR |
| NFR-11 | VAL-N11 | Proposed team NFR |
| NFR-12 | VAL-N12 | Proposed team NFR |

## Security Requirement Traceability

| Requirement ID | Related NFR | Validation ID |
|---|---|---|
| SEC-01 | NFR-01 | VAL-S01 |
| SEC-02 | NFR-01 | VAL-S02 |
| SEC-03 | NFR-01 | VAL-S03 |
| SEC-04 | NFR-01 | VAL-S04 |
| SEC-05 | NFR-11 | VAL-S05 |
| SEC-06 | NFR-01 | VAL-S06 |
| SEC-07 | NFR-01 | VAL-S07 |
| SEC-08 | NFR-12 | VAL-S08 |
| SEC-09 | NFR-01 | VAL-S06 |
| SEC-10 | NFR-01 | VAL-S09 |

> Security requirements are included here so the handoff RTM covers the full SRS requirement set rather than only functional requirements.

## RTM Consistency Notes

- FR-20 is scoped to authorized teachers and administrators, matching UC-T07 and UC-A04.
- FR-21 resolves UC-S02.
- FR-22 resolves UC-A06.
- FR-23 resolves UC-A03.
- FR-24 resolves UC-A05.
- UC-X05 / notification is intentionally excluded because the finalized project rule is that no notification feature is included.
- NFR-06 remains explicitly marked as proposed until the team approves the 5-minute target.
