# Form Submission Scenarios — Test Cases

**Test IDs:** TC-031 to TC-036
**Feature:** Submission Scenarios

---

| Test ID | Test Title | Description | Steps | Expected Output | Status |
|---------|-----------|------------|-------|----------------|--------|
| TC-031 | Submit Form Without Any Required Fields | Verify system prevents submission when required fields are empty | 1. Open CV AI 2. Go to JD URL Import form 3. Leave required fields empty 4. Click Submit | System highlights required fields and shows validation errors | Pending |
| TC-032 | Submit Without Target Role | Verify target role is required before submission | 1. Leave job title empty 2. Fill other fields 3. Click Submit | Error message displayed for missing job title | Pending |
| TC-033 | Submit Without Company Name | Verify company name field behavior on submission | 1. Leave company name empty 2. Fill other fields 3. Click Submit | Form proceeds without an error | Pending |
| TC-034 | Submit Without Job Description | Verify job description is required before submission | 1. Leave job description empty 2. Click Submit | Error message displayed for missing job description | Pending |
| TC-035 | Submit Required Fields with Spaces Only | Verify system rejects whitespace-only input | 1. Enter spaces in required fields 2. Click Submit | Validation error shown for invalid input | Pending |
| TC-036 | Submit Required Fields with Special Characters Only | Verify system validates required fields properly | 1. Enter symbols only in required fields 2. Click Submit | Validation error displayed | Pending |
