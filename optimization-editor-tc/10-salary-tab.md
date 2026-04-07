# Salary Tab — Test Cases

**Test IDs:** TC-066 to TC-070
**Feature:** Salary Tab (Pro+)

---

| Test ID | Test Title | Description | Steps | Expected Output | Status |
|---------|-----------|------------|-------|----------------|--------|
| TC-066 | Display Market Salary Estimate | Verify system shows estimated salary range based on JD, role level, location hints, and industry standards | 1. Open Salary tab 2. Enter target role 3. Click Generate | Estimated min/max salary, confidence level (low/medium/high), and key factors displayed | Pending |
| TC-067 | Update Salary on Role/Location Change | Verify salary estimate updates when role or location changes | 1. Change target role or location 2. Refresh Salary tab | Updated salary range, confidence level, and key factors displayed | Pending |
| TC-068 | Handle Missing Role | Verify system shows guidance when role is missing | 1. Leave target role empty 2. Open Salary tab | Error or guidance indicating role is required | Pending |
| TC-069 | Currency and Formatting | Verify salary estimate is displayed in correct currency and format | 1. Open Salary tab | Salary numbers correctly formatted with currency symbol | Pending |
| TC-070 | Non-Pro Access Restriction | Verify non-Pro users cannot view salary estimates | 1. Login as non-Pro user 2. Open Salary tab | System blocks access and shows upgrade to Pro prompt | Pending |
