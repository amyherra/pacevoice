# PaceVoice — Accessible Voice Assistant Prototype

PaceVoice is an interactive prototype based directly on the proposed solution in the assignment.

## The three core parts of the proposed solution

### 1. A system trained for broken/atypical speech
The prototype includes **Patient Mode** to represent a future individualized speech-recognition layer. The production version would be trained/evaluated on atypical speech and designed to better tolerate pauses, repetitions, hesitation, uneven pacing, and disrupted speech.

### 2. Show the user's input
After the user speaks or types, PaceVoice visually identifies the input as **“What I think you said.”** This makes the system's interpretation visible instead of forcing the user to guess what the assistant heard.

### 3. Read previous conversations
PaceVoice now includes a **Previous Conversations** section. Each conversation can be selected and reopened so the user can read the previous exchange. This directly addresses the proposed idea that users should be able to see and review previous conversations rather than having to remember what the assistant said.

## Additional accessibility features
- User-controlled response time
- Repeat-on-demand
- Confirmation before actions
- Voice + visual text
- Slower/simple prompt option
- Text input as an alternative to speech

## Prototype limitation
The atypical-speech recognition component is represented by the interface and Patient Mode; this prototype does not claim to contain a clinically validated atypical-speech model. A production system would require an actual speech model trained/evaluated with representative speech data and accessibility research with disabled users.

## Evidence to record
Make a 45–60 second screen recording:
1. Select Patient Mode.
2. Increase response time.
3. Use “Set a reminder.”
4. Show the **What I think you said** result.
5. Wait without rushing.
6. Click Repeat.
7. Start a new conversation.
8. Perform another interaction.
9. Open **Previous Conversations** and click the first conversation.
10. Show that the earlier conversation can be read again.

## Publishing
Open `index.html` in a browser, or upload it to a static web host such as GitHub Pages or Netlify.
