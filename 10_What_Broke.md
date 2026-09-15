# STEP 10: WHAT BROKE

## Purpose

This file records the main problems, limitations, and weaknesses observed during the technical support response-drafting experiment.

---

## Human-Only Run

### User 1 — Shilpa

* Response drafting took **6 minutes**.
* Time was required to read and understand the issue before writing the response.
* The response also needed to be reviewed before finalizing.

### User 2 — Neha

* Response drafting took **10 minutes**.
* The task required careful understanding of the support issue before preparing the response.
* Additional time was required to review the final response.

### What Broke in the Human-Only Process

The main bottleneck was **writing a clear and professional response**, especially because similar response-writing work is repeated for different support queries.

Shilpa specifically identified writing the response clearly and professionally as the most time-consuming part and said that writing similar responses repeatedly can feel repetitive.

---

## A Specific Quality Problem Observed

During the Human Alone run for Shilpa's ticket, the drafted response stated that the authentication issue had been **investigated and resolved**.

However, the ticket itself only provided the customer's symptoms and the troubleshooting steps already attempted. It did not provide evidence that the account or authentication configuration had actually been investigated or that the issue had been resolved.

This showed that a response can sound professional while still containing an **unsupported claim**.

This is an important weakness because a support response should not claim that an issue was investigated or fixed unless that action has actually been performed or confirmed.

---

## AI-Only Run

The same support tickets were also tested using a plain LLM.

### Observed Result

The plain LLM was able to generate complete initial response drafts very quickly.

### AI-Only Limitation

Although the plain LLM can produce a response quickly, the generated response still needs to be checked against the original support ticket.

The human needs to verify:

* Whether the response is supported by the available information.
* Whether important information is missing.
* Whether the response asks for the right additional information.
* Whether unnecessary technical terminology is used.
* Whether the response is appropriate for the client.

Therefore, the plain LLM cannot be treated as the final decision-maker.

---

## Main Problems Identified

### 1. Manual Drafting Takes Time

The Human Alone process took **6 minutes for Shilpa** and **10 minutes for Neha**.

The repeated work of understanding the query, deciding what to include, drafting, and reviewing adds manual effort.

### 2. Professional Writing is Repetitive

Users may need to repeatedly write similar responses in a clear and professional manner.

This was identified by the users as an area where an initial AI draft could reduce manual writing effort.

### 3. AI Can Produce Unsupported or Inappropriate Content

A fast AI-generated response is not automatically a reliable response.

The output must be checked against the actual support ticket to prevent unsupported claims, missing information, or inappropriate wording.

### 4. Human Judgement is Still Required

The human needs to verify the technical details, correct the AI draft, decide whether additional information is required, and approve the final response.

---

## What the Collaborative System Needs to Solve

The experiment showed that neither approach is sufficient by itself.

**Human Alone → More manual drafting effort**

**Plain LLM → Faster drafting but requires verification**

The collaborative system should therefore use:

**AI → Generate the initial draft**

**Human → Verify, correct, and approve**

The goal is to reduce repetitive drafting work while keeping human judgement responsible for the final client response.

---

## Key Learning

The main learning from the experiment is that the problem is not simply about making response generation faster.

The system must reduce the repetitive writing effort **without allowing unsupported claims or incorrect information to reach the client**.

Therefore, the proposed Human + AI workflow should use AI for the initial draft while keeping the human in the loop for verification, correction, and final approval.
