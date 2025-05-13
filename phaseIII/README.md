# Phase III: Prototypes and User Testing

## Introduction

GymBuddy is a web based application designed to help users find local workout partners based on shared fitness preferences and availability. The core problem it addresses is the difficulty some people face in finding reliable, compatible gym partners in their area.

This final phase of the project focused on conducting a structured usability evaluation of our interactive prototype. The goal was to identify areas of friction, validate our design choices from previous phases, and gather actionable feedback to refine the user experience. Using a formalized protocol and a mock testing audience, we piloted the test with participants representative of our target users and gathered both qualitative and quantitative data.

## Methods

### Study Approach
We conducted a formative usability study with a moderated, think-aloud protocol. This approach allowed us to observe real-time user interactions and collect deeper insights into participants’ mental models, expectations, and challenges. Participants were guided through a series of tasks in the GymBuddy prototype while verbalizing their thought process. Observations were recorded via notes and a standardized feedback form.

### Test Protocol & Tasks

The usability test consisted of the following four tasks:

1. **Create a GymBuddy Profile**
   - *Goal:* Assess users’ ability to complete the onboarding process and input fitness preferences.
   - *UX Component Evaluated:* Learnability, labeling clarity, and form usability.

2. **Search for a Gym Partner**
   - *Goal:* Determine if users can use filters and navigate search results effectively.
   - *UX Component Evaluated:* Efficiency and discoverability.

3. **Send a Match Request**
   - *Goal:* Evaluate clarity and confidence around initiating contact with a match.
   - *UX Component Evaluated:* Action feedback, error prevention.

4. **Edit Profile Information**
   - *Goal:* Observe whether users can locate and edit profile settings after initial setup.
   - *UX Component Evaluated:* Navigation and consistency.

Participants were prompted with realistic scenarios and encouraged to speak aloud as they interacted with the prototype. Observers noted time on task, error frequency, and comments related to confusion, satisfaction, and hesitation.

### Data Collection Tools

- Observational notes by facilitators  
- User quotes and behavioral notes  
- Task success/failure tracking  
- Google Sheets document for compiling qualitative feedback and session summaries


## Findings

### Quantitative Trends

- **Success Rate:** 3 out of 4 users successfully completed all core tasks.
- **Most Common Failure:** Editing a profile—users often struggled to locate the appropriate section in the current flow.
- **Time to Completion:** Task 1 (Profile Creation) was the fastest, averaging 1.5 minutes; Task 4 (Editing) was the slowest, averaging 3.5 minutes due to navigation issues.

### Qualitative Observations

- **Positive Feedback:**
  - Users found the visual layout intuitive and liked the bold, structured style of the interface.
  - The workout preference filters were described as “useful” and “easy to understand.”

- **Pain Points:**
  - Confusion between “Sign Up” and “Get Started” still lingered for some users.
  - The process of editing profile preferences after initial setup was not obvious.
  - Users wanted clearer indicators after sending a match request (e.g., a confirmation message or visual checkmark).
  - The prototype did not have proper match request functionality and was inconsistent.


## Conclusions

The usability test revealed critical insights that shaped final design recommendations:

### Recommended Design Changes

- **Clarify Button Language:** Consolidate or more clearly differentiate “Sign Up” vs. “Get Started” to prevent confusion.
- **Improve Navigation Flow:** Add a persistent "Edit Profile" button in the header or sidebar to improve accessibility.
- **Add Feedback Cues:** After user actions such as sending a request, provide a confirmation message or visual acknowledgment.

### Validated Design Choices

- The overall flow and design choices were well received after we made the major revisions in preparation for the walkthrough. 
- Users expressed satisfaction with the visual layout and found the categories within the settings section intuitive.

These findings will guide any future iterations of the GymBuddy app, with a continued focus on clarity, accessibility, and user confidence.

## Caveats

While the study yielded valuable insights, there are important limitations to consider:

- **Limited Participant Pool:** Due to time constraints, the pilot test included only a small number of participants. This limits generalizability to a broader population.
- **Demographic Narrowness:** Most users were college students; future tests should include working professionals and other potential gym-goers.
- **Prototype Fidelity:** As this was a mid-fidelity wireframe prototype, some interactions were not fully functional, which may have impacted user expectations and feedback.
- **Moderated Testing Bias:** Participants may have responded more positively in the presence of moderators, potentially reducing critical feedback.
- **Limited participant pool:** The participant pool was limited to 6 total.

Despite these limitations, the Phase III evaluation served as an effective pilot to validate the GymBuddy concept and surface usability priorities for improvement.
