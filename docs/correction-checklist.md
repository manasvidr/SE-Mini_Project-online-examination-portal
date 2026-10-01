# Phase-1 Correction Checklist

This checklist records the cross-document issues identified during the Phase-1 audit. It is a coordination checklist for the team documents; it does not silently change other members' files.

## SRS — Sravya

- [ ] Ensure the updated use-case diagram is visibly rendered in the final DOCX/PDF.
- [ ] Correct actor-to-use-case association lines so Student, Teacher, Administrator, and supporting services connect only to their intended use cases.
- [ ] Include SEC-01 through SEC-10 in the SRS RTM.
- [ ] Include administrator product functions corresponding to FR-22, FR-23, and FR-24 in the product-functions summary.
- [ ] Keep FR-22/23/24 and their UC/validation mappings consistent with the final requirements handoff.

## Architecture & Design — Neha Sachin

- [ ] Correct the use-case diagram actor associations.
- [ ] Ensure UC-X01 — Authenticate User is represented consistently in the diagram and use-case model.
- [ ] Change security traceability from SEC-01–SEC-08 to SEC-01–SEC-10.
- [ ] Add API coverage for FR-22 Administrator Login, FR-23 System Settings, and FR-24 Access Management.
- [ ] Correct the examination sequence so evaluation and score calculation occur after submission/timeout, not before.
- [ ] Show the configured result-release stage in the examination lifecycle/sequence.
- [ ] Represent persistence of the selected question set explicitly (for example through an ExaminationQuestion/SelectedQuestionSet relationship).
- [ ] Explain or align the grouping between the component diagram and the detailed component table.

## Test Plan — Nehaa Joshi

- [ ] Correct the Section 3 administrator-functions mapping so it refers to FR-22–FR-24 rather than FR-19/FR-20.
- [ ] Align NFR-01 traceability with the actual test case(s) and VAL-N01.
- [ ] Align NFR-02 traceability with the actual test case(s) and VAL-N02.
- [ ] Add SEC-01, SEC-02, SEC-03, SEC-05, SEC-06, SEC-07, and SEC-08 to the SRS/test traceability table.
- [ ] Resolve the orphaned VAL-F17 mapping by linking it to the relevant lifecycle test case(s).
- [ ] Clean up TC-10 so its precondition does not say the examination is already submitted before the submission step.
- [ ] Make TC-06 verify membership/completeness/no-duplicates in addition to comparing displayed order when validating shuffled questions.
- [ ] Remove any blank table rows or layout artifacts.
- [ ] Keep the NFR-06 five-minute criterion explicitly conditional on team approval.

## Manasvi Requirements & RTM

- [x] FR-01 through FR-24 represented.
- [x] FR-21 resolves UC-S02.
- [x] FR-22 resolves UC-A06.
- [x] FR-23 resolves UC-A03.
- [x] FR-24 resolves UC-A05.
- [x] NFR-03 has a measurable 3-second target.
- [x] NFR-06 is explicitly marked as proposed and approval-dependent.
- [x] Functional, non-functional, and security RTM mappings included.
