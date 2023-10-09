# Exercise 6: Coding Best Practices

## Objectives
This exercise is designed to help you put into practice many of the skills you have learned so far in this course. You must build and style a simple 4-page website that documents the performance of a website of your choice.

See examples of what your finished pages could look like in the repo's images folder.


## Instructions

### Get set up
* Clone your remote exercise repository onto your local machine.
* Add a comment in the head element of the homepage including: the course code and your section number - your name - Coding Best Practices. Example:
```
<!-- DGL 103 CVS1 - your name - Coding Best Practices -->
```
### Step 1: Practice some testing
Choose any live website you like, and try out the three launch tasks below:
1. Go to https://wave.webaim.org and enter your chosen website's URL in the web address field to check the accessibility of the website. Check out all the accessibility errors and alerts in the Details tab. Take a screenshot and save it in a folder called images in your repo. 
2. Let's check to see if the website is mobile-friendly (if it isn't then search engines will penalise it and visitors will have a poor experience). Go to https://search.google.com/test/mobile-friendly and enter your chosen website in the URL field. Take a screenshot of the results and save it in the images folder.
3. Now let's see how quickly the homepage of the website loads. Go to https://developers.google.com/speed/pagespeed/insights/ and enter the URL. Take a screenshot of the Mobile results and save it. Click on the Desktop results, are they better than the mobile results?

### Step 2: Build a website to document the testing
Create a 4-page website from scratch, no HTML code has been provided. Make sure that your HTML is clean, error-free and semantic (don't use any div elements unless you absolutely have to)! Your website will include the following content:

**Page 1: Homepage:**
1. Header with navigation
2. Link to the website
3. Brief explanation of the what the website is and why you chose it
4. A screenshot of the homepage of the website that opens a full-size image of the website in a new browser tab when the user clicks on it
5. Summary of the test results
6. Links that take the visitor each individual test page
7. Footer

**Page 2: Accessibility Test:**
1. Header with navigation
2. Definition of what accessibility testing is IN YOUR OWN WORDS
3. Description of what you found out from the testing results
4. A screenshot of the testing results that opens a full-size image in a new browser tab when the user clicks on it
7. Footer

**Page 3: Responsiveness Test:**
Same content as for page 2.

**Page 4: Speed Test:**
Same content as for page 2.

Remember to:
* Regularly save your files and check out what your web page looks like in a web browser.
* Make regular commits and label them appropriately to document your progress.

As you code, make the most of the tools available to you:
1. Highlight any errors. Note: If the debugger is not working then you may be in restricted mode and need to turn on Workspace Trust. Click on the Manage Gear button at the bottom of the screen on the left-hand side, then select Manage Workspace Trust to switch between Trusted and Restricted modes.
2. Use the Prettier extension to help you format your code.
3. Use the Chrome Developer Tools: Open index.html in Chrome, right-click > Inspect.

### Step 3: Style your website
Put some effort into styling your content and make your content look well-structured and easy to read. All your CSS must be in one external stylesheet, it must be organized into sections using comments, and it must be efficient. Use element type selectors as much as possible. At the very least, you must include the following:
* a Google font
* the 62.5% trick
* display properties: (inline, inline-block or block)
* box model properties: padding, margin, border, background, border-radius, box-shadow, width
* text formatting properties: font-family, font-weight, font-size, text-decoration, color

### Step 4: Format, add comments, and check for errors
* Use the Prettier VSCode extension to format HTML and CSS code.
* Add a few comments to explain your HTML and CSS code and highlight anything of interest.
* Validate each HTML page to make sure that it is correct: https://validator.w3.org/#validate_by_upload. Take screenshots of the results.
* Validate your CSS code to make sure that it is correct: https://jigsaw.w3.org/css-validator/ for CSS. Take a screenshot of the results.

**You have now completed your exercise but you still need to push your edits to GitHub and submit it in Brightspace. Make sure to follow the instructions in the How to Complete Your Exercises Guide.**