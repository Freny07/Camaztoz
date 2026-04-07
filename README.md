# Camazotz -- Design Documentation Template

Team Name: Error 404  
Team Members: 
1. Freny Kansagra
2. Damarla Rohit Phani Datta
3. Nayan Gupta
4. Prabal Verma
5. Anshuma
              

# Phase 1 (Design Disaster)

## Objective
Explain the intent behind your intentionally flawed design.

Brief Description:
> The app is a Tic Tac Toe Android game where two users must log in before playing. The user flow includes multiple login steps followed by the game screen.
The design intentionally introduces usability issues to confuse users, increase friction, and demonstrate poor UX practices.


## Intentional UX Issues Introduced

### Issue 1

Type: CTA, Visibility

What was done:
> One important button is not clearly visible on the screen and doesn’t stand out much from the background.

Why this was done:
> To see how users behave when the main action is not easily noticeable.

Expected User Difficulty:
> Users might not find the button quickly and may think they are stuck or the app is not working properly.

### Issue 2

Type: Navigation / Flow

What was done:  
> Some pages are connected in a way that users can end up going back to previous pages without realizing it.

Why this was done: 
> To check how users handle navigation when the flow is not very clear.

Expected User Difficulty:  
> Users may feel like they are stuck in the same steps and get confused about how to move forward.

### Issue 3

Type:  Interaction / Consistency

What was done: 
> There is a way to enter the game, but it is not noticeable. It is not very obvious and may require users to explore before figuring them out.

Why this was done: 
> To observe how users react when actions are not clearly defined or easy to identify.

Expected User Difficulty: 
> Users may take time to understand how to exit properly or may try different options before finding the correct one.

### Issue 4

Type: CTA / Navigation

What was done: 
> Among multiple available buttons, only one leads to the next step, but it is not clearly distinguishable from the others.

Why this was done:
> To observe how users identify the correct action when multiple options appear similar.

Expected User Difficulty: 
> Users may try different buttons before finding the correct one, leading to confusion and extra effort.

### Issue 5

Type: Semantics / Cognitive Load

What was done: 
> Input fields use placeholder text that is not easily understandable.

Why this was done:
> To see how users handle input when clear instructions are not provided.

Expected User Difficulty: 
> Users may not understand what to enter or may input incorrect data.

### Issue 6

Type:  Navigation / Flow / Cognitive Load

What was done:
> User input is divided across multiple separate screens instead of being grouped together, increasing the number of steps required to complete the process.

Why this was done:
> To explore how breaking a simple flow into multiple steps affects user patience and understanding.

Expected User Difficulty: 
> Users may feel the process is unnecessarily long and may lose track of progress.

### Issue 7

Type:  Navigation / Consistency / Cognitive Load

What was done:
> The login process spans across multiple screens , with similar layouts but slight differences in element placement and actions.

Why this was done:
> To test how users adapt to repeated but slightly changing interfaces.

Expected User Difficulty: 
> Users may get confused between screens, feel repetitive friction, or miss important actions.

### Issue 8

Type:  Feedback / Consistency / Semantics

What was done: 
> Game elements and labels are not always aligned with expected meaning. Symbols and messages may not always correspond correctly to the actual game state.

Why this was done:
> To observe how users rely on visual and textual feedback during gameplay.

Expected User Difficulty: 
> Users may misinterpret what is happening in the game or lose trust in the displayed information.

### Issue 9

Type:  Semantics / Communication

What was done:
> Some instruction titles and result messages have been altered in a way that does not clearly match their actual purpose.

Why this was done:
> To test how users respond when system messages are unclear or misleading.

Expected User Difficulty: 
> Users may misunderstand outcomes or instructions, leading to confusion during gameplay.

### Issue 10

Type:  Logic Feedback / Consistency

What was done:
> The turn-based system does not always clearly differentiate between players, causing similar symbols or patterns to appear repeatedly.

Why this was done:
> To explore how users track turns and game state when feedback is not fully reliable.

Expected User Difficulty: 
> Users may lose track of turns or become unsure about which player is currently playing.

### Issue 11

Type:  Navigation / Flow / Consistency

What was done:
> The game section includes multiple related screens, but transitions between them are not clearly defined. Certain actions intended to move forward may lead back to the same screen instead of progressing.

Why this was done:
> To observe how users interpret navigation when screen transitions are not clearly distinguishable.

Expected User Difficulty: 
> Users may feel like they are not progressing, repeat the same action multiple times, or assume the feature is not working.

### Issue 12

Type:  Input / Validation / Semantics

What was done:
> Input fields do not enforce strict format or length constraints, allowing flexible entries without clear boundaries.

Why this was done:
> To observe how users behave when validation is minimal or not immediately enforced.

Expected User Difficulty: 
> Users may enter inconsistent or unexpected data, leading to confusion during later stages.

### Issue 13

Type:  CTA / Cognitive Load

What was done:
> Additional buttons are present in the interface that do not contribute directly to the main flow.

Why this was done:
> To explore how extra options affect user focus and decision-making.

Expected User Difficulty: 
> Users may get distracted, try irrelevant actions, or take longer to complete tasks.




# Functional Bugs / Issues 

Bug 1:
- Description: A key actionable element is not easily noticeable on the screen
- Impact: Users may struggle to proceed
- Workaround : Careful exploration of UI

Bug 2:
- Description: Some navigation paths may take users back to previously visited screens
- Impact: Creates confusion in flow progression
- Workaround : Try alternative navigation options

Bug 3:
- Description: Certain actions are not clearly discoverable and may require exploration
- Impact: Slows down interaction
- Workaround: Interact with different elements

Bug 4:
- Description: Only specific buttons trigger forward navigation while others appear similar
- Impact: Users may press incorrect options
- Workaround: Try different buttons

Bug 5:
- Description: Input fields contain unclear or unfamiliar placeholder content
- Impact: Incorrect or delayed input
- Workaround: Guess expected input

Bug 6:
- Description: Input flow is distributed across multiple screens
- Impact: Increased steps for simple tasks
- Workaround: Continue through all steps

Bug 7:
- Description: Game symbols may not always align with expected positions
- Impact: Misinterpretation of game board
- Workaround: Track moves manually

Bug 8:
- Description: Game result messages may not match the actual outcome
- Impact: Confusion after game completion
- Workaround: Verify result from gameplay

Bug 9:
- Description: Turn representation may not clearly alternate between players
- Impact: Difficulty tracking turns
- Workaround: Observe move sequence carefully

Bug 10:
- Description: Some navigation actions do not lead to new screens and may reload the same page
- Impact: Blocks access to certain features
- Workaround: Retry or explore other paths

Bug 11:
- Description: Input fields accept unrestricted or unexpected formats
- Impact: May lead to inconsistent data entry
- Workaround: Enter data carefully

Bug 12:
- Description: Some buttons do not perform any noticeable action
- Impact: Confuses users and interrupts flow
- Workaround: Ignore non-responsive buttons

# Design Anti-Patterns Used

Hidden / Low Discoverability Actions
→ Important actions are not easily visible

Ambiguous CTAs
→ Multiple buttons appear similar but behave differently

Poor Visual Hierarchy
→ No clear distinction between primary and secondary actions

Confusing Navigation
→ Loops and unclear transitions between screens

Fragmented User Flow
→ Inputs and steps split across multiple pages

Inconsistent Interaction Patterns
→ Similar actions behave differently

Unclear Semantics
→ Placeholder text and labels are not easily understandable

Misleading Feedback
→ Messages and results do not match actual system state

Broken System Feedback
→ Users cannot rely on visual/game indicators

Cognitive Overload
→ Multiple steps, unclear inputs, and repeated screens increase effort

Lack of Input Validation
→ Fields allow unrestricted input

Irrelevant / Redundant Actions
→ Extra buttons increase confusion
- Confusing navigation  
- Cognitive overload  
- Inconsistent components
- Unnecessary buttons
