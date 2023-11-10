## #1 Synchronize voice and text in Chat

**ID:** IS-01

**Title:** The character's speech and text animation are not synchronous  

**Module/Feature:** Chat with the Character  

**Severity:** High

### 1.1. Description

**Current Behavior:** In a character's messages, when chatting, the character's voice and the message they are typing are not synchronized.

The desynchronization starts from the beginning. While the character's message typing is simulated starting with the character's behavior description, the voice begins to speak the character's text at once, jumping over the character's reaction. Therefore, the character's speech runs far ahead, and the typed text in the message lags far behind.

The scenario is demonstrated in the screen recording: [VIDEO](Chat_Unsynchronized_voice_and_text.mp4)

**Expected Behavior:** The character's voice should say the exact words as it types.

**Reason for Suggestion:** The behavior is unpleasant. When voice and text are not synchronized, it makes the user uncomfortable. It is unclear what is going on. The user is hearing information that is not already on the screen.

The user faces it each time when it interacts with the character. It is an important part of the product.

### 1.2. Steps to Reproduce

1. On the Characters page, select any character and click “Chat”.
2. Turn on the sound in the chat by pressing the “Unmute” button.
3. Write any message to the character.
4. The character will start to respond. You will see that the character's behavior description is typed first, for example, "*The tiny insect hovers in mid-air, its translucent wings fluttering softly*", and only then the character's text. The character's speech will start immediately. That is, the voice will run forward.

### 1.3. Possible Solutions

It is possible not to animate the character's behavior description typing but to immediately display this text on the screen and start animating just the character's text.