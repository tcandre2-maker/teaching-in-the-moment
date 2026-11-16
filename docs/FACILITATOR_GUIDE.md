# Facilitator Guide
## Teaching in the Moment: Using Incidental Teaching to Expand Learning Opportunities in ABA Sessions

**Project:** LDT 593 Applied Project  
**Sponsor:** Skill Builders ABA  
**Audience:** Registered Behavior Technicians (RBTs)  
**Format:** Self-paced, browser-based instructional prototype  
**Estimated seat time:** Approximately 60 minutes (design estimate; pilot validation is still required)  
**Prototype status:** Academic functional prototype; not a substitute for BCBA supervision or competency assessment

---

## 1. Purpose

This guide supports an instructor, facilitator, or sponsor representative who is introducing, observing, or evaluating the instructional prototype. The program is designed to help RBTs recognize naturally occurring learning opportunities, connect those opportunities to authorized treatment-plan goals, implement only the procedures described in the written plan, and recognize when BCBA consultation is required.

The module emphasizes observable learner behavior, treatment-plan alignment, learner independence, assent, dignity, and professional scope.

## 2. Learning objectives

By the end of the program, participants should be able to:

1. Recognize appropriate incidental-teaching opportunities and distinguish them from nonexamples.
2. Connect naturally occurring activities to relevant authorized treatment-plan goals without independently changing a protocol.
3. Select implementation responses consistent with the written plan: observe, recognize or use an authorized opportunity, allow the planned response opportunity, prompt only as prescribed, reinforce as written, and record as directed.
4. Identify when BCBA consultation is required because a clinically meaningful procedural detail is missing, unclear, or outside the RBT's authorized role.

The assessment blueprint allocates five diagnostic and five final items to each objective. The final assessment requires at least 16/20 correct overall and all five designated scope/consultation items correct. See `ASSESSMENT_BLUEPRINT.md` for the detailed structure.

## 3. Materials and technology

- A computer or tablet with a current browser (Chrome, Edge, Firefox, or Safari).
- Reliable internet access if the module is hosted; local preview requires the project files to remain together.
- Headphones or speakers for narration.
- Keyboard and mouse or touchscreen.
- This facilitator guide and the participant guide.
- The one-page incidental-teaching job aid.
- A method for collecting participant feedback and recording observed usability issues.

Do not use identifiable client records, actual client names, or confidential treatment plans during instruction or evaluation. The cases in the module are fictional learning scenarios.

## 4. Before the session

1. Open the hosted course URL or launch `index.html` from a local web server. Do not rely on a private GitHub source page as the learner-facing course.
2. Confirm that the landing page loads and that the images appear.
3. Test at least one narration control and confirm the transcript is available.
4. Test one flip card, one drag-and-match item, one click-to-select match, one plan annotation, one branching scenario, and one section navigation control.
5. Confirm that the learner can access the diagnostic before instruction and that instructional links remain gated until the diagnostic is completed.
6. Confirm that the final assessment and results screen are reachable.
7. Use a fresh browser profile or clear site data for a clean demonstration. Assessment progress is browser-local in this prototype; it is not centrally reported to an administrator.
8. Have the participant guide and job aid available.

**Important release note:** Static source checks do not establish that every control works in every browser. Complete the functional checks above in the exact hosted version before the instructor or sponsor evaluates it.

## 5. Suggested 60-minute facilitation plan

| Component | Target time | Facilitator role |
|---|---:|---|
| Welcome and diagnostic pre-assessment | 12 min | Explain that the diagnostic is for baseline information, not a mastery gate. |
| Section 1: Teaching Happens Everywhere | 3 min | Ask learners to distinguish observation from arranging a teaching trial. |
| Section 2: What Counts as Incidental Teaching? | 5 min | Reinforce natural context, motivation, and the difference between an opportunity and a manufactured barrier. |
| Section 3: Spot the Opportunity | 5 min | Prompt learners to identify observable cues before selecting a response. |
| Section 4: Connect the Goal to the Moment | 3 min | Ask which written target and setting actually apply. |
| Section 5: Decide What to Do Next | 3 min | Emphasize decision-dependent outcomes, assent, and consultation. |
| Scenario practice | 17 min | Observe decision-making and ask learners to explain why a choice is plan-consistent. |
| Final assessment and review | 12 min | Allow independent completion; review results and areas for follow-up. |
| **Total** | **60 min** | Timing is a design target, not a validated completion time. |

If the prototype's current navigation presents the scenario labs within Sections 1–5 rather than as a separate screen, use the activity labels and the actual interface sequence. Do not force a timer or rush learner decisions to meet the estimate.

## 6. Facilitation prompts

Use neutral prompts that encourage the learner to explain their reasoning without supplying the answer:

- What did the learner do that you can directly observe?
- What relevant goal is actually written in the plan?
- Does the plan cover this setting and response form?
- What does the plan say to do next?
- Would this response preserve the learner's opportunity to respond independently?
- Would the proposed action add a barrier or change a procedure?
- What information is missing?
- At what point should the RBT pause and consult the supervising BCBA?

Avoid framing a learner's choice as a clinical recommendation for an actual client. All examples are instructional simulations.

## 7. Assessment and mastery

### Diagnostic pre-assessment
The diagnostic contains 20 items, five per objective. It is completed before instruction. The diagnostic score is a baseline indicator; it does not determine final mastery. Participants should complete every item independently. The current design provides correctness marking without detailed explanations.

### Formative practice
Practice activities include click-to-reveal learning cards, matching, scenario decisions, plan interpretation, and decision-specific feedback. Invite participants to read the feedback and explain how it relates to the written plan.

### Final assessment
The final scenario-based assessment contains 20 items, five per objective. The prototype's stated mastery rule is:

- At least 16 of 20 items correct (80%); and
- All five designated Objective 4 scope/consultation items correct.

A score of 16/20 does not pass if any designated critical scope item is missed. Retakes are intended for learning and do not replace supervisor observation or skill demonstration.

### Interpretation
A passing score indicates performance on this digital knowledge/application assessment only. It does not verify live implementation competence, authorize a treatment change, or replace training, rehearsal, direct observation, and supervision.

## 8. Troubleshooting

| Issue | Facilitator response |
|---|---|
| Course does not load | Confirm the hosted URL or local server is running. Avoid opening a local file path if the course depends on relative assets. |
| Images are missing | Confirm the `assets/images` folder is present beside `index.html` and that the course was deployed with the full asset directory. |
| Audio does not play | Check device volume, browser site permissions, and the audio file path. Use the visible transcript as the equivalent text alternative. |
| Drag-and-drop is difficult | Use the click-to-select interaction: select the example, then select its category. |
| Animation is not visible | Check the device's reduced-motion setting. Core information and interaction should remain available without animation. |
| Progress or score is not retained | The current prototype uses browser-local storage where available. Use the same browser and profile; private browsing or cleared site data may reset progress. |
| A control appears inactive | Refresh the hosted build, confirm the latest release was deployed, and record the browser, device, screen, and control for the technical issue log. |

## 9. Sponsor / instructor evaluation checklist

Record Pass, Needs Revision, or Not Tested for each item:

- Landing page and course purpose are clear.
- Diagnostic is accessible before instruction.
- All 20 diagnostic items can be completed and results are displayed.
- Instruction remains gated until the diagnostic is complete.
- All five instructional sections can be navigated.
- Flip cards reveal the reverse side.
- Audio plays and transcripts are available.
- Matching works by drag-and-drop.
- Matching also works by click/touch selection.
- Branching choices change the next scenario state and feedback.
- Plan annotations open the correct explanation.
- Scope/consultation feedback is clinically appropriate.
- Final assessment scoring applies both mastery requirements.
- Keyboard navigation and visible focus are usable.
- Images and alt text match the described scenarios.
- Course works on the sponsor's intended device/browser.
- Instructor and sponsor can independently access the hosted course.

## 10. Clinical and ethical safeguards

The program is an educational resource, not a clinical protocol. Participants must follow the current client-specific written treatment plan and the direction of the supervising BCBA. Do not independently create targets, alter prompting procedures, change reinforcement, change response definitions, or manufacture barriers to produce opportunities. Honor authorized communication forms and stop/withdrawal signals as described in the plan and applicable organizational policy. Pause and consult when the written plan does not specify a clinically meaningful next step.

## 11. Evaluation notes

Collect:
- completion time and points of hesitation;
- technical errors and browser/device details;
- participant ratings of clarity, relevance, and usability;
- items or feedback that were confusing;
- accessibility barriers;
- sponsor/BCBA observations about clinical accuracy;
- suggested revisions.

Do not claim the course is WCAG 2.2 AA certified or clinically validated unless a documented audit and qualified review have been completed.
