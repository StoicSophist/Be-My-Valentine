# Will You Be My Valentine? 

## Overview

This HTML page is a simple Valentine's Day greeting, prompting the user with the question "Will you be my Valentine?" and providing response buttons for "Yes" and "No." The page features interactive elements such as confetti animation and randomized responses when the user clicks the "No" button.

## HTML Structure

- **Question Section:**
  - Displayed prominently with a purple color.
  - Font size is set to 40px.
  
- **Response Buttons:**
  - "Yes" button (`#yes`) with a green background.
  - "No" button (`#no`) with a red background.
  - Both buttons have a font size of 35px and are clickable.

- **Result Section:**
  - Initially hidden (`display: none`).
  - Displayed in purple with a font size of 40px.
  - Shows a special message when the user clicks the "Yes" button.

- **No Button Click Counter:**
  - Displayed below the result section (`#counter`).
  - Shows the number of times the "No" button has been clicked.
  - Font size set to 35px.

- **Yes Button Getting Bigger**
  - The Yes button will increase in size each time the "No" button is hit
  - It will increase by 130% each time it is hit on the "No" button

- **Confetti Animation:**
  - Utilizes the `js-confetti` library for a confetti effect when the "Yes" button is clicked.
  - A canvas element (`#confetti`) is used to render the confetti.

## Customizations

- The "No" button triggers random responses from an array when clicked.
- The "Yes" button triggers a confetti animation and displays a special message.
- The "Yes" button increases in size by 30% when clicked.
- The confetti animation is triggered using the `JSConfetti` library.

## Dependencies

- `js-confetti`: A JavaScript library for adding confetti to a web page.

## Usage

1. Open the HTML file in a web browser.
2. Click the "Yes" button to see a confetti animation and a special message.
3. Click the "No" button to receive random responses, increment the "No" button click counter, and to see the "Yes" button increase in size.
