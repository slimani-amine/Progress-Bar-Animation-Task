# Progress Bar Animation Task

## Objective

Complete the implementation of a progress bar animation with the following features:

- **Progress Bar Animation:**
  - Create a progress bar that animates from 0% to 100% within a specified duration (e.g., 3 seconds).
  - The progress bar animation should start when a button is clicked.

- **Queue Handling:**
  - If the button is clicked multiple times, queue the progress bars so that each one starts animating only after the previous one finishes.

## Getting Started

1. **Fork the Repository:**
   - Click the "Fork" button on the top right of this repository page to create your own copy.
   - Clone your forked repository to your local machine using:
     ```bash
     git clone <your-forked-repository-url>
     ```
   - Navigate to the repository directory:
     ```bash
     cd <repository-directory>
     ```

2. **File Structure:**
   - `index.html`: Contains the base HTML structure.
   - `styles.css`: Contains the base CSS styles.
   - `script.js`: JavaScript file to be completed.

3. **JavaScript Implementation:**
   - Open `script.js` and implement the following functionality:
     - **Progress Bar Creation:** When the "Start Loading" button is clicked, dynamically create and add a new progress bar to the DOM.
     - **Animation:** Each progress bar should animate from 0% to 100% over a duration of 3 seconds.
     - **Queue Management:** Ensure that each progress bar starts animating only after the previous one has completed. Implement a queue mechanism to handle this.

4. **HTML and CSS:**
   - The provided `index.html` and `styles.css` files contain the basic structure and styles for the progress bar. You do not need to modify these files but ensure your JavaScript code integrates seamlessly with them.

5. **Testing:**
   - Open `index.html` in a web browser.
   - Click the "Start Loading" button and observe the progress bar animation.
   - Click the button multiple times and verify that each progress bar starts animating only after the previous one finishes.

6. **Considerations:**
   - **Code Structure:** Ensure that your JavaScript code is well-organized and easy to read.
   - **Modularity:** Write modular code to make it easy to extend or modify in the future.
   - **Performance:** Optimize your solution to handle multiple progress bars efficiently.
   - **Error Handling:** Include any necessary error handling to ensure smooth execution.

## Example Usage

1. Open `index.html` in a web browser.
2. Click the "Start Loading" button.
3. Observe the progress bars animating sequentially from 0% to 100%.
4. Click the button again to see additional progress bars being added and animated one after the other.

## Submission

- Once you have completed the task, make sure to test your solution thoroughly.
- Commit and push your changes to your forked repository.
- Submit the repository link as instructed.

## Additional Resources

- [MDN Web Docs - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [MDN Web Docs - CSS Transition](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions)
- [MDN Web Docs - HTML DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)

Good luck, and happy coding!
