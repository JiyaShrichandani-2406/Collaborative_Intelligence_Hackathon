# STEP 9: PROCESS MAP

## Legend

* **D — Deterministic:** A fixed or routine step that follows a defined process.
* **P — Probabilistic:** A step where the result depends on interpretation, generation, or variable input.
* **H — Human-in-the-room:** A step where human judgment, verification, correction, or approval is required.

---

## Current Human-Only Process

**Technical Support Query**

↓
**Receive Query — D**

↓
**Read and Understand the Query — H**

↓
**Identify the Customer's Issue — H**

↓
**Determine the Information Needed — H**

↓
**Draft the Response — H**

↓
**Review and Correct the Response — H**

↓
**Final Response — H**

### Where Human Judgment Enters

Human judgment is required when the support professional:

* Understands what the customer is actually asking.
* Identifies the reported issue.
* Decides what information should be included.
* Determines how the issue should be explained to the customer.
* Checks whether the response is correct and appropriate.
* Makes the final decision before the response is sent.

### Current Bottleneck

The most time-consuming part observed in the current process is **writing the response clearly and professionally**, along with the repeated effort of preparing similar responses.

This is consistent with Shilpa's feedback that writing the response clearly and professionally is the most time-consuming part and that writing similar responses repeatedly can feel repetitive.

---

## Observed Human Run

| User   | Manual Response Time |
| ------ | -------------------: |
| Shilpa |            6 minutes |
| Neha   |           10 minutes |

The two users completed their response-drafting tasks without AI assistance.

---

## Proposed Human + AI Process

**Technical Support Query**

↓
**Receive Query — D**

↓
**AI Generates Initial Draft — P**

↓
**Human Reviews AI Draft — H**

↓
**Human Checks Technical Details and Correctness — H**

↓
**Human Corrects / Adds Missing Information — H**

↓
**Human Approves Final Response — H**

↓
**Final Response — H**

### Human-in-the-Room Requirement

The human must remain involved after the AI generates the draft.

The human is responsible for:

* Checking whether the draft matches the customer's issue.
* Verifying technical details.
* Checking that the response is correct and relevant.
* Ensuring the language is clear and professional.
* Removing unnecessary technical terminology where appropriate.
* Adding missing information.
* Giving final approval before the response is sent.

### AI Responsibility

The AI is responsible for generating the **initial response draft**.

Based on the users' feedback, the draft should aim to:

* Use clear and professional language.
* Avoid unnecessary technical terms.
* Explain the issue from a functional/client perspective.
* Reduce repetitive manual writing.

The AI does not make the final decision about whether the response should be sent.

---

## Process Change

### Before

**Query → Human Understands → Human Identifies Issue → Human Decides Information → Human Drafts → Human Reviews → Final Response**

### After

**Query → AI Draft → Human Reviews → Human Verifies & Corrects → Human Approves → Final Response**

The proposed change moves the repetitive **initial drafting** work from the human to the AI while keeping human judgment at the verification and approval stages.
