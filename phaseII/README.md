# Phase II: Refining interaction and designing wireframes

## Introduction

The goal of Phase II was to evaluate the usability and clarity of our initial GymBuddy wireframes. In Phase I, we identified user needs, created personas and scenarios, and developed low-fidelity mobile-first wireframes based on heuristic assumptions.

However, several usability questions remained:
- Can users easily complete core tasks such as creating a profile or finding a gym partner?
- Is the layout clear enough to support first time users?
- Are labels, buttons, and page flows clear?

To address these, we conducted cognitive walkthroughs and collected informal feedback from SWE students. The outcome of these evaluations informed substantial updates to our design artifacts.

## Methods

!!! Describe research methods you used to discover new insights, which explains the purpose of each. Provide enough detail that someone would be able to faithfully reproduce your research. Only include research methods in here, not design documents/techniques/artifacts !!!

Throughout phase 2, we used two primary research methods – cognitive walkthroughs and informal feedback from the SWE team and other UX project members. Below, these methods and our findings are detailed.

### Cognitive Walkthroughs
We conducted three structured walkthroughs using Phase I’s personas and scenarios. Participants reviewed a wireframe and were asked to complete the following core task:

    “Find a compatible gym partner based on shared workout preferences.”

At each step, participants answered the following standard cognitive walkthrough questions:

1. Will the user know what to do at this step?​
2. If the user does the right thing, will they know they did the right thing and are making progress toward their goal?

These evaluations provided insights into the usability and clarity of our wireframes. We learned that we overlooked many steps in our process

### Informal Feedback from SWE Team Demo
In collaboration with the SWE team, we presented our prototype to a class of approximately 35 students. They were asked: "Does our design make sense, and are there any features you think could be improved?" This feedback offered a broader perspective on user expectations and potential areas for enhancement.

## Findings

Through the combination of our cognitive walkthroughs and informal feedback from the Software Engineering class, we were able to identify several usability issues with our current GymBuddy wireframes. These findings helped validate previous assumptions from Phase I while also uncovering new problem areas in layout, interaction flow, and content clarity. Below is a breakdown of specific issues identified from each method.

### From Cognitive Walkthroughs
- **Task Completion Issues**: All 3 users struggled to successfully complete the "find a gym partner" scenario due to missing links or unclear navigation cues.
- **Ambiguous Buttons**: Terms like “Get Started” and “Sign Up” caused confusion, as they were interpreted similarly.
- **Flow Disruptions**: Users did not always know where they were in the process; the flow between creating a profile and filtering matches was not obvious or easy to navigate.
- **Labeling and Feedback Gaps**: There was minimal indication of whether actions were successful or not, leaving users unsure if they had progressed.

### From SWE Class Feedback
- **Page Redundancy**: Several students noted pages felt repetitive and could be simplified or combined.
- **Navigation Confusion**: Icons and button placement were not well placed; users were not confident where buttons would take them.
- **Overall Support**: Despite the issues, the overall concept was well-received, indicating a strong foundation for further development.


## Conclusions

!!! Discoveries derived from the methods and their findings. Interpret how the findings translate into new insights into UX design recommendations. Describe those recommendations and how they should shape future work. In this section, include the new design recommendations based on the latest user insights. !!!

The key things we learned from this phase include the importance of clear and consistent labeling, logical navigation, and visible feedback in supporting user tasks. Based on our findings, we have made the following design changes:
- Revised the onboarding flow to clarify the difference between "Sign Up" and "Get Started."
- Reordered screens so that profile setup precedes match discovery, aligning with users’ expectations.
- Adapted the layout for a web-based experience rather than a mobile-first interface.
- Added feedback indicators (e.g., button states, success messages) to guide users through the interaction.
- Transition to Web-Based Layout: Adapt the design from a mobile-first approach to a web-based interface to align with project developments.

These changes aim to improve usability and align the application more closely with user needs and expectations.


## Caveats

!!! Considerations and/or limitations to the methods you chose and the findings/conclusions drawn from them. In other words, give warnings if there are limitations to your research such as not being able to find enough users of a particular demographic, the methods not being able to expose certain information, assumptions you made, etc. !!!

While this phase provided valuable insights that informed meaningful design improvements, there were several limitations to our research and testing approach. These caveats are important to acknowledge, as they may have influenced the depth and scope of our findings and the generalizability of our conclusions.

- Limited Participant Pool: The cognitive walkthroughs involved a small number of participants, which may not represent the broader user base.​

- Informal Feedback Constraints: Feedback from the SWE class was unstructured, potentially limiting the depth of insights.​

- Design Transition Challenges: Shifting from a mobile-first to a web-based layout introduced complexities that required significant adjustments to the wireframes.

- Time Constraints: Due to sprint timelines, we were unable to iterate as deeply as we would have liked before the next deliverable.

