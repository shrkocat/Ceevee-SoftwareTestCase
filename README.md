# CV AI — Manual Test Suite

**Feature Under Test:** Billing & Subscription Usage (Primary)
**Platform:** [https://cv-ai.work](https://cv-ai.work)
**Submission Type:** Manual Test Suite (Markdown)

---

## Overview

This repository contains a comprehensive manual test suite for [CV AI](https://cv-ai.work), an AI-powered resume optimization platform. The **primary feature** selected for in-depth testing is **Billing & Subscription Usage**, which governs how monthly optimization quotas are enforced, tracked, and reset across the platform's four subscription tiers.

The suite also covers all supporting features that interact with billing and core platform flows:

| File | Feature Area | Test IDs |
|------|-------------|----------|
| `01-jd-url-import.md` | Job Description URL Import | TC-001–TC-012 |
| `02-jd-field-input.md` | Job Description Field Input | TC-013–TC-022 |
| `03-ai-model-selection.md` | AI Model Selection | TC-023–TC-030 |
| `04-submission-scenarios.md` | Form Submission Scenarios | TC-031–TC-036 |
| `05-network-session.md` | Network, Session & Concurrent Usage | TC-037–TC-045 |
| `06-editor-tab.md` | Optimization Editor – Live Markdown | TC-046–TC-050 |
| `07-keyword-heatmap.md` | Keyword Heatmap Tab | TC-051–TC-055 |
| `08-diff-view.md` | Diff View Tab | TC-056–TC-060 |
| `09-interview-prep.md` | Interview Prep Tab (Pro+) | TC-061–TC-065 |
| `10-salary-tab.md` | Salary Tab (Pro+) | TC-066–TC-070 |
| `11-follow-up-email.md` | Follow-Up Email Tab (Pro+) | TC-071–TC-075 |
| `12-billing-subscription.md` | **Billing & Subscription Usage** | TC-076–TC-083 |

---

## Repository Structure

```
Ceevee-SoftwareTestCase/
│
├── README.md                        
│
├── new-optimization-tc/
│   ├── 01-jd-url-import.md             # TC-001–TC-012
│   ├── 02-jd-field-input.md            # TC-013–TC-022
│   ├── 03-ai-model-selection.md        # TC-023–TC-030
│   ├── 04-submission-scenarios.md      # TC-031–TC-036
│   ├── 05-network-session.md           # TC-037–TC-045
├── optimization-editor-tc/
│   ├── 06-editor-tab.md                # TC-046–TC-050
│   ├── 07-keyword-heatmap.md           # TC-051–TC-055
│   ├── 08-diff-view.md                 # TC-056–TC-060
│   ├── 09-interview-prep.md            # TC-061–TC-065
│   ├── 10-salary-tab.md                # TC-066–TC-070
│   ├── 11-follow-up-email.md           # TC-071–TC-075
├── billings-tc/
│  └── 12-billing-subscription.md      # TC-076–TC-083

```

---

## How to Run the Tests Locally

This is a **manual test suite** — no build tools or dependencies are required.

### Prerequisites

- A modern web browser (Chrome or Firefox recommended)
- CV AI accounts at each subscription tier to cover all test cases:
  - Free tier
  - Pro tier
  - Premium tier
  - Ultra tier
- Access to [https://cv-ai.work](https://cv-ai.work)

### Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/shrkocat/Ceevee-SoftwareTestCase.git
   ```
   
2. **Execute each test case manually**

   Follow the **Steps** column row by row. Compare what actually happens against the **Expected Output** column.

3. **Record your results**

   Update the **Status** column for each test case using one of the following values:

   | Status | Meaning |
   |--------|---------|
   | `Pass` | Actual output matches expected output |
   | `Fail` | Actual output does not match; note the deviation |
   | `Pending` | Test case is still to be tested |
   | `N/A` | Not applicable in the current environment |

4. **Save results**

   Copy the updated table into `test-results/` which will be created, like:
   ```
   test-results/results.md
   ```

---
