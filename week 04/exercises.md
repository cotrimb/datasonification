# Data Sonification — Week 3: JavaScript Music Exercises

## Setting Up Live Server in VS Code  

***Live Server*** *is a popular extension for VS Code that enables real-time, live reloading of your HTML, CSS, and JavaScript files in a web browser. This means whenever you save changes in your code, the browser automatically updates, avoiding any need to refresh manually. It's useful for web development projects, making it easy to see immediate results as you edit your code “on the fly.”*
   
1. Open Visual Studio Code.
2. Click on the **Extensions** icon (or press `Ctrl + Shift + X`).
3. Search for the **Live Server** extension by **Ritwick Dey** and install it.
4. Open your HTML file (e.g., `index.html`).
5. Click the **"Go Live"** button at the bottom right of the VS Code window.
6. Your HTML file will open in a browser, and changes will update automatically as you save the file.

## Rendering LaTeX Equations in Markdown in VS Code  

***Markdown*** *is a lightweight markup language used to format text, often for writing documentation, README files, or web content. It allows you to use plain text with simple syntax to create headings, lists, links, and more*. 

***LaTeX*** *equations are a powerful way to write complex mathematical expressions and symbols. By embedding LaTeX into Markdown, you can format professional-looking mathematical formulas alongside regular text, making it ideal for academic and technical writing.*
  
1. Open Visual Studio Code.
2. Click on the **Extensions** icon (or press `Ctrl + Shift + X`).
3. Search for the **Markdown Preview Enhanced** extension by **Yiyi Wang** and install it.
4. Write LaTeX equations in your Markdown file:
   - For **inline equations**, use single dollar signs: $ equation $.
   - For **block equations**, use double dollar signs: $$ equation $$.
   
   Example for converting **BPM** to **beat duration**:  
   The formula is:  
   $$ \text{beat duration (ms)} = \frac{60,000}{\text{BPM}} $$
   
5. To preview the Markdown file with rendered LaTeX equations:
   - Press **`Ctrl + Shift + V`** (Windows/Linux) or **`Cmd + Shift + V`** (Mac) to open the preview.
   - Alternatively, right-click your Markdown file and select **"Markdown Preview Enhanced: Open Preview"** from the context menu.
   
6. If you want the preview to automatically update as you edit the file:
   - Open the command palette with **`Ctrl + Shift + P`** (Windows/Linux) or **`Cmd + Shift + P`** (Mac).
   - Search for **"Markdown Preview Enhanced: Toggle Auto Preview"** and enable it.

7. The preview window opens up in a separate tab in VS Code.   
   - Just click the `x` in the tab to close it!  
   
*This setup will allow you to view your Markdown content with real-time LaTeX equation rendering directly in VS Code.*

---

## Exercise Questions (to be completed in JavaScript)    

1. Declare a MIDI note **variable** for middle C (MIDI note 60) and print it.
2. **Concatenate** two musical phrases using solfège syllables and print the result.
3. Declare two note durations (quarter and eighth notes), **calculate the total duration**, and print the result.
4. **Round a floating-point** note duration to the nearest whole number and print the result.
5. Create an **array** containing the MIDI notes for a C major triad and print it.
6. Declare three MIDI notes, **calculate the average** and print it.
7. **Round the average** of three MIDI notes and print the result.
8. **Concatenate** two solfège phrases into a full musical scale and print it.
9. Declare two floating-point note durations, **add them, round the total**, and print the result.
10. Create an **array** of solfège syllables representing a full musical scale, **randomize the order**, and print the result.
11. **Input a MIDI note** number from the user and print it.
12. **Input two note durations** from the user, calculate and print the total duration.
13. **Input two solfège syllables** from the user, concatenate them into a phrase, and print it.
14. **Input a tempo (in BPM)** from the user, calculate the duration of four beats in milliseconds, and print the result.
15. **Input a beat duration** (in milliseconds) from the user, calculate the corresponding tempo (in BPM), and print the result.
16. **Use `setTimeout()`** to create a simple metronome that ticks 4 times. The user inputs a tempo in BPM, which is converted to milliseconds.

---

## LaTeX Formulas

1. The formula for converting **BPM** to **beat duration** (in milliseconds) is:
   $$ \text{beat duration (ms)} = \frac{60,000}{\text{BPM}} $$

2. The formula for converting **beat duration** (in milliseconds) to **BPM** is:
   $$ \text{BPM} = \frac{60,000}{\text{beat duration (ms)}} $$

---

### Additional Notes

- For **Live Server**: You’ll be able to view your HTML file in the browser with real-time updates. This is useful for seeing how your JavaScript and MathJax work in combination.
  
- For **Markdown Preview Enhanced**: This extension allows you to view LaTeX equations inside your Markdown files. You’ll be able to see the equations rendered as you type.

---
