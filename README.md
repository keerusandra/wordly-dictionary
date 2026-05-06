### Lab: Single Page Application (SPA)- Wordly
url - https://keerusandra.github.io/wordly-dictionary/

**Estimate Completed Time:** ~60 min.

#### Overview
As a developer for Wordly, you are tasked with building a Single Page Application (SPA) for the dictionary. You will build an SPA that enables users to search for a word and retrieve information such as pronunciation, definitions, synonyms, and source details.

- Search for Words: Allow users to input a word into an HTML form and fetch its definition from an external dictionary API.
- Display Definitions: Dynamically show the word’s definition, part of speech, and example usage on the same page without a reload.
- Style the Page: Use JavaScript to dynamically update the CSS, highlighting saved words or changing themes for better readability.
- Error Handling: Display an error message if a word is not found or if the API request fails.

#### Tools and Resources
- VSCode (or any code editor)
- Web browser for testing
- GitHub repository (https://github.com/wordly-dictionary.git)
- Node.js installed

**Instructions:**

**Fork and Clone the Repository**
- Fork the provided GitHub repository to your account.
- Clone the forked repository to your local machine.
- Navigate to the project directory and run `npm install` to set up the project dependencies.
- Run `npm test` to test your code and open the `index.html` file in a web browser to view the changes. Save the file and refresh your browser to see the changes.


**Analyze and Plan**
- Review the provided HTML structure in the `index.html` file.
- Define your styling goals for the following elements:
   - Text container
   - Page layout
   - Responsive design

**Create and Link CSS File**
- Create a new file named `style.css` in the project directory.
- Link the CSS file in the `index.html` file within the `<head>` section.

**Style the Dictionary**
For the body section
- Set the margin to `0 `
- Set the display property to `flex`
- Set `min-height` to `100vh`
- Set `justify-content` to `center`
- Set `align-items` to `center`
- Set `background-color` to `aquamarine`
- Set the `font-family` to `Cambria, Cochin, Georgia, Times, 'Times New Roman', serif`

For the text container section
- Set `background-color` to `rgba(255, 255, 255, .3)`
- Set `padding` to `28px`
- Set border-radius: 7px`
- Set `box-shadow: 0 10px 10px rgba(0, 0, 0, .3);
- Set `width` to `90%`
- Set `margin` to `10px`
- Set `max-width` to `450px`
- Set `text-align` to `center`
- Set `font-size` to `18px`
- Set `font-weight` to `500`

For the heading section
- Set `font-size` as `28px`

For the input section
- Set `height` to `53px`
- Set `width` to `300px`
- Set `background-color` to `rgba(255, 255, 255, .6)`
- Set `border-color` to `rgba(255, 255, 255, .4)`
- Set `font-size` to `16px`
- Set `padding` to `0 42px`
- Set `border-radius` to `5px`

**Create and Link JS File**
- Create a new file named `script.js` in the project directory.
- Link the js file in the `index.html` file within the `<script>` section.


**Organize and Test**
- Save your CSS and JS files.
- Open the `index.html` file in a web browser to view the changes.
- Ensure all elements are styled correctly and the layout is responsive.
- Run `npm test` to test your code and ensure all tests are passing.
