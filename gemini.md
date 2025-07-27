# Gemini Instructions: Fire Safety Training HTML App

## Objective
Create a single-page, interactive HTML application to educate and train workers on fire safety procedures and emergency exits. The application must be visually engaging, using graphics and animations to explain each key point effectively.

## Core Requirements
- **Single-Page Application:** All content should be on one `index.html` file, using JavaScript to show/hide different sections.
- **Interactive Navigation:** Users should be able to navigate through training modules sequentially (e.g., using "Next" and "Previous" buttons).
- **Visual First:** Every major concept must be illustrated with a graphic or an animation.
- **Responsive Design:** The layout should adapt to different screen sizes (desktop, tablet, mobile).
- **Quiz:** A simple multiple-choice quiz at the end to reinforce learning.

---

## Development Plan

### 1. File Structure
Create the following file and directory structure:
```
/
|-- index.html
|-- style.css
|-- script.js
|-- /assets/
    |-- fire-alarm.svg
    |-- rescue.svg
    |-- confine.svg
    |-- evacuate.svg
    |-- exit-route.svg
    |-- blocked-exit.svg
    |-- clear-exit.svg
    |-- assembly-point.svg
    |-- extinguisher-pull.svg
    |-- extinguisher-aim.svg
    |-- extinguisher-squeeze.svg
    |-- extinguisher-sweep.svg
```

### 2. HTML (`index.html`)
- Set up the basic HTML5 boilerplate.
- Link `style.css` and `script.js`.
- Create a main container `<div id="training-container">`.
- Inside the container, create a series of `<section>` elements, one for each training module. Only the active section will be visible at a time.
- Add a navigation area with `<button id="prev-btn">Previous</button>` and `<button id="next-btn">Next</button>`.

### 3. Training Modules (Sections in `index.html`)

**Section 1: Introduction**
- **Content:** "Welcome to Fire Safety Training. Your safety is our priority. This training will guide you through the essential steps to take in a fire emergency."
- **Graphic:** A general safety shield icon.

**Section 2: Recognizing the Alarm**
- **Content:** "Know the sound of the fire alarm. Upon hearing it, you must act immediately."
- **Graphic/Animation:** Create an animated SVG of a fire alarm bell ringing, with soundwave lines emanating from it.

**Section 3: The R.A.C.E. Protocol**
- **Content:** "Remember to R.A.C.E. - Rescue, Alarm, Confine, Evacuate."
- **Graphic:** Create four small icons for each letter.
- **Animation:** As the user clicks "Next" through the following 4 points, highlight the corresponding letter and icon.

**Section 4: R - Rescue**
- **Content:** "RESCUE anyone in immediate danger from the fire, if it does not endanger your own life."
- **Graphic:** An icon showing one person assisting another away from a flame symbol (`rescue.svg`).

**Section 5: A - Alarm**
- **Content:** "ALARM: Activate the nearest fire alarm pull station and call emergency services."
- **Animation:** An animation of a hand pulling a fire alarm lever (`fire-alarm.svg`).

**Section 6: C - Confine**
- **Content:** "CONFINE the fire by closing all doors and windows as you leave."
- **Animation:** An animation showing a door closing, trapping a fire icon inside a room (`confine.svg`).

**Section 7: E - Evacuate**
- **Content:** "EVACUATE the building immediately. Do not use elevators."
- **Graphic:** An icon of a person walking quickly towards an exit sign (`evacuate.svg`).

**Section 8: Evacuation Routes**
- **Content:** "Follow the designated primary evacuation routes. If blocked, use a secondary route."
- **Animation:** An animated floor plan layout (`exit-route.svg`) where a primary path glows green. If the user clicks a "Show Secondary" button, the primary path turns red and a secondary path glows green.

**Section 9: Emergency Exits**
- **Content:** "Emergency exits must always be kept clear. Never block them."
- **Animation:**
    1. Show an exit door blocked by boxes (`blocked-exit.svg`) with a red "X" over it.
    2. Animate the boxes moving away and the "X" changing to a green checkmark (`clear-exit.svg`).

**Section 10: Assembly Point**
- **Content:** "Proceed to the designated assembly point after evacuating. Wait for instructions."
- **Graphic:** A map pin icon over a group of people icons (`assembly-point.svg`).

**Section 11: Using a Fire Extinguisher (P.A.S.S.)**
- **Content:** "For small fires only. Remember P.A.S.S: Pull, Aim, Squeeze, Sweep."
- **Animation:** A four-step animated sequence using the extinguisher SVGs:
    1. **Pull:** (`extinguisher-pull.svg`) Pin is pulled from the handle.
    2. **Aim:** (`extinguisher-aim.svg`) Nozzle is aimed at the base of a small fire icon.
    3. **Squeeze:** (`extinguisher-squeeze.svg`) Handle is squeezed and spray comes out.
    4. **Sweep:** (`extinguisher-sweep.svg`) The spray sweeps across the base of the fire, which then extinguishes.

**Section 12: Final Quiz**
- **Content:** Create a simple 3-question multiple-choice quiz.
- **Interactivity:**
    - Questions appear one at a time.
    - Provide immediate feedback (correct/incorrect) upon answering.
    - Show a final score at the end.

### 4. CSS (`style.css`)
- Implement a clean and professional design. Use a color palette with reds, grays, and whites.
- Style the main container, sections, and buttons.
- Use CSS to hide all sections by default (`display: none;`).
- Create a `.active` class to show the current section (`display: block;`).
- Add CSS transitions for smooth fading between sections.
- Ensure all animations and graphics are centered and sized appropriately.

### 5. JavaScript (`script.js`)
- Manage the display of training sections using the `.active` class.
- Implement the "Next" and "Previous" button logic to navigate between sections.
- Handle the quiz logic: displaying questions, checking answers, and calculating the final score.
- Trigger CSS animations as sections become active.