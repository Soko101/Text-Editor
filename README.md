# Text-Editor
A simple text editor made using js, html and css
The web app is a simple text editor with various formatting and styling options for the user.

*HTML Structure:* The HTML defines the structure of the web app. It includes a 
container element that holds all the editor components. Inside the container, we 
have a set of buttons and selects for various formatting options, as well as 
a div with contenteditable="true" for the text input area.

*CSS Styling:*  I have defined styles for various elements, including buttons, selects, input elements, and the text input area. 
Additionally, used CSS classes like .option-button, .adv-option-button, and .active to apply specific styles to different UI elements.

*JavaScript Interactivity:* Script.js handles the interactivity of the web app. 

-I  defined functions to change the text formatting when a button is clicked. For example, when an option button is clicked, you call the changeText function, passing the command (e.g., "bold") and value (e.g., "null") as parameters. The document.execCommand method is used to execute the command.

-I also handled more advanced formatting options, such as changing the font name and font size, creating hyperlinks, and changing font and highlight colors.

-I used event listeners to capture button clicks and changes in select elements. For example, when an option button is clicked, its associated function is called to apply the formatting.

-I had a function called highlighter that adds or removes the "active" class from buttons to highlight or unhighlight them, depending on the button's state.

-I called the initializer function when the window loads, which sets up the initial state of the editor, including populating the font and font size selects.

*External Dependencies:* The web app includes external dependencies, such as the Font Awesome icon library and Google Fonts for the "Poppins" font.

*User Interaction:* Users can interact with your web app by clicking buttons, selecting formatting options, and typing or editing text in the content area. The app provides real-time feedback by applying the selected formatting to the text.

*Styling Customization:* Users can customize the appearance of the text, including font, font size, font color, background color, and various formatting styles like bold, superscript, subscript, alignment, and list styles.
