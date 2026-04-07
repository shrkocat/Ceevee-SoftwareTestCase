# AI Model Selection — Test Cases

**Test IDs:** TC-023 to TC-030
**Feature:** AI Model Selection

---

| Test ID | Test Title | Description | Steps | Expected Output | Status |
|---------|-----------|------------|-------|----------------|--------|
| TC-023 | Select Haiku Model | Verify user can select Haiku AI model | 1. Open CV AI platform 2. Go to AI Model selection 3. Choose Haiku 4. Submit | Haiku model is selected and used for processing | Pending |
| TC-024 | Select Sonnet Model | Verify user can select Sonnet AI model | 1. Open AI Model selection 2. Choose Sonnet 3. Submit | Sonnet model is selected and used for processing | Pending |
| TC-025 | Select Opus Model (Ultra Tier) | Verify Opus model is available for Ultra tier users | 1. Login as Ultra tier user 2. Select Opus 3. Submit | Opus model is available and processing starts | Pending |
| TC-026 | Select Opus Model Without Ultra Tier | Verify Opus model is restricted to Ultra tier | 1. Login as regular user 2. Try selecting Opus | System blocks selection and shows upgrade prompt | Pending |
| TC-027 | Default AI Model Selection | Verify default model is selected when no selection is made | 1. Open model dropdown 2. Do not select a model 3. Submit | Default AI model (Haiku or system default) is used | Pending |
| TC-028 | Change AI Model Before Submission | Verify user can change AI model before submitting | 1. Select Haiku 2. Change to Sonnet 3. Submit | Sonnet model is used for processing | Pending |
| TC-029 | AI Model Selection Persistence | Verify selected AI model remains selected after refresh | 1. Select Sonnet 2. Refresh page | Selected model remains or resets correctly based on design | Pending |
| TC-030 | AI Model Selection During Processing | Verify model cannot be changed during processing | 1. Select Haiku 2. Start processing 3. Attempt to change model | System disables model selection during processing | Pending |
