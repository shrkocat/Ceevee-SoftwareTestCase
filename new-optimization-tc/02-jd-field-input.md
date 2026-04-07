# Job Description Field Input — Test Cases

**Test IDs:** TC-013 to TC-022
**Feature:** Job Description Field Input Handling

---

| Test ID | Test Title | Description | Steps | Expected Output | Status |
|---------|-----------|------------|-------|----------------|--------|
| TC-013 | Submit After Clearing Required Field | Verify system re-validates cleared required fields | 1. Fill all fields 2. Remove job title 3. Click Submit | Error appears for missing job title | Pending |
| TC-014 | Job Description Below 50 Characters | Verify minimum character requirement is enforced | 1. Enter less than 50 characters in job description 2. Click Submit | Error: Job description must be at least 50 characters | Pending |
| TC-015 | Job Description Exactly 50 Characters | Verify system accepts minimum valid input | 1. Enter exactly 50 characters in job description 2. Click Submit | Job description accepted successfully | Pending |
| TC-016 | Job Description Above 50 Characters | Verify system accepts valid job description | 1. Enter more than 50 characters 2. Click Submit | Submission successful | Pending |
| TC-017 | Job Description Very Long Input | Verify system handles large job descriptions | 1. Enter 100+ characters 2. Click Submit | System processes job description successfully | Pending |
| TC-018 | Job Description Empty | Verify empty job description is rejected | 1. Leave job description empty 2. Click Submit | Error message displayed | Pending |
| TC-019 | Job Description with Spaces Only | Verify whitespace-only job description is rejected | 1. Enter spaces in job description 2. Click Submit | Validation error displayed | Pending |
| TC-020 | Job Description with Line Breaks | Verify multi-line job description is supported | 1. Enter multiple paragraphs 2. Click Submit | Job description accepted properly | Pending |
| TC-021 | Job Description with Special Characters | Verify system handles symbols in job description | 1. Enter symbols in job description 2. Click Submit | System accepts or sanitizes input safely | Pending |
| TC-022 | Job Description with HTML or Script Tags | Verify system prevents malicious input | 1. Enter script or HTML tags 2. Click Submit | System sanitizes or blocks input | Pending |
