# STEP 2: IMPACT METRIC

## Impact Metric

Time required to draft a client response for one technical support query.

## Unit

Minutes per support query

## Baseline Measurement

Two users, Shilpa and Neha, were given different technical support tickets to draft client responses. The same tickets were also tested using a plain LLM to establish the AI-only baseline.

| Method              | Ticket                   | Time to Draft Response |
| ------------------- | ------------------------ | ---------------------: |
| Shilpa – Human      | Technical support ticket |          6 minutes     |
| Neha – Human        | Technical support ticket |         10 minutes     |
| Plain LLM – AI Only | Same support tickets     |          5 seconds     |

## Measurement Method

The timer was started when the response-drafting task began and stopped when the response was ready.

The support tickets given to the users were also provided to the plain LLM so that the response-drafting time could be compared using the same type of input.

For the human runs, the time represents the time taken by the user to prepare the response. For the AI-only baseline, the time represents the time taken by the plain LLM to generate the response.

## Initial Finding

For the tested support tickets, ## Shilpa took 6 minutes ## and ## Neha took 10 minutes ## to draft their responses.

When the same tickets were tested with a plain LLM, the response was generated in approximately ## 5 seconds ##.

This shows a substantial difference in response-drafting speed between the human-only and AI-only approaches.

However, speed alone does not determine the quality or usefulness of the response. The human users provide context, judgement, verification, and responsibility for the final response, while the LLM provides much faster initial generation.

## Purpose of the Metric

This metric will be used to determine whether a collaborative human + AI workflow can reduce the time required to prepare a client response while maintaining human judgement, verification, and response quality.

The later experiment will compare:

Human Alone → AI Only → Human + AI

and measure whether the collaborative approach performs better than both individual approaches.

## Supporting Evidence

The support tickets were shared with the users through WhatsApp and Linkedin, and the conversations are retained separately as contact evidence.

* User 1 contact evidence: `05_Contact_Artefacts/user1_chat.md`
* User 2 contact evidence: `05_Contact_Artefacts/user2_chat.md`

