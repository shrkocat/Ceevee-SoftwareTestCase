# Job Description URL Import — Test Cases

**Test IDs:** TC-001 to TC-012
**Feature:** JD URL Import Handling

---

| Test ID | Test Title | Description | Steps | Expected Output | Status |
|---------|-----------|------------|-------|----------------|--------|
| TC-001 | Import JD from LinkedIn URL | Verify system imports job description from LinkedIn job link | 1. Open CV AI 2. Go to JD URL Import 3. Paste LinkedIn job URL 4. Click Import | Job title, company name, and full job description are extracted successfully | Pending |
| TC-002 | Import JD from External Job Website | Verify system imports JD from non-LinkedIn job posting | 1. Paste Indeed/Jobstreet job link 2. Click Import | Job details extracted correctly | Pending |
| TC-003 | Empty URL Field | Verify system handles empty input | 1. Leave URL field empty 2. Click Import | Import button cannot be clicked | Pending |
| TC-004 | Invalid URL Format | Verify system rejects incorrect URL | 1. Enter random text 2. Click Import | Error: "Invalid URL format" | Pending |
| TC-005 | Broken URL | Verify system handles dead links | 1. Paste broken link 2. Click Import | Error: "Invalid URL format" | Pending |
| TC-006 | Unsupported Website | Verify system handles unsupported job sites | 1. Paste unsupported job link 2. Click Import | Error: "Invalid URL format" | Pending |
| TC-007 | URL Redirect | Verify system handles redirected URLs | 1. Paste redirecting job link 2. Click Import | System successfully extracts job data | Pending |
| TC-008 | Slow Internet Connection | Verify system behavior under slow network | 1. Paste URL 2. Simulate slow connection 3. Click Import | Loading indicator appears and job data loads | Pending |
| TC-009 | Very Long Job Description | Verify system handles large JD content | 1. Paste long job posting URL 2. Click Import | Full job description extracted without truncation | Pending |
| TC-010 | Multiple Import Attempts | Verify system handles repeated imports | 1. Import URL 2. Import again | System processes correctly without crash | Pending |
| TC-011 | URL with Authentication Required | Verify system handles protected job pages | 1. Paste login-required job link 2. Click Import | Error: Unable to access job posting | Pending |
| TC-012 | Refresh Page During Import | Verify system stability during page refresh | 1. Begin importing URL 2. Refresh page | System resets safely without crash | Pending |
