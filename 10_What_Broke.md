# STEP 10: WHAT BROKE

## Purpose

This file records the problems, limitations, and weaknesses observed while testing the technical support response-drafting task.

## Human-Only Run

### User 1 – Shilpa

* Response drafting took **6 minutes**.
* Time was required to read and understand the issue before writing the response.
* The response also needed to be reviewed before finalizing.

### User 2 – Neha

* Response drafting took **10 minutes**.
* The task required careful understanding of the support issue before preparing the response.
* Additional time was required to review the final response.

### Human-Only Limitation

The main limitation of the manual process is that response drafting requires repeated human effort for every support query.

---

## AI-Only Run

The same support tickets were tested using a plain LLM.

### Observed Result

The plain LLM generated a response in approximately **5 seconds**.

### AI-Only Limitation

Although the plain LLM was much faster, speed alone does not guarantee that the generated response contains all the information required for the specific support situation.

A human may still be needed to check the response, identify missing or incorrect information, and make final corrections.

---

## Main Problems Identified

### 1. Manual Process is Time-Consuming

The human users took several minutes to prepare a response.

### 2. AI is Fast but Requires Verification

The plain LLM generated responses very quickly, but the output still needs to be checked for correctness and relevance.

### 3. Human Judgement Cannot Be Completely Removed

The final response may require context, judgement, and verification that should remain with the human.

---

## What the Collaborative System Needs to Solve

The Human + AI system should combine the strengths of both approaches:

**AI → Faster Initial Draft**

**Human → Verification, Correction, and Final Approval**

The system should therefore reduce drafting time without sacrificing the quality and reliability of the final client response.

## Key Learning

The experiment suggests that the main opportunity is not simply to replace the human with AI, but to use AI for the repetitive drafting work while keeping the human involved in reviewing and finalizing the response.
