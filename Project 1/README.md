# Nicholas Malone - *CIS3110 Project 1*
### [YouTube Demonstration](https://upload.wikimedia.org/wikipedia/commons/6/67/Learning_Curve_--_Coming_Soon_Placeholder.png)
## Deliverable Requirements
#### 1. Dropdown Navigational Menu
The navigation bar and dropdown menu can be found on *lines 18-43* of the [project1.html](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.html#L18) file. These elements are directly borrowed from Bootstrap through the JSDelivr CDN. The three links in the dropdown menu are the three possible links generated as an outcome of a number guessing game. The guessing game based on user input is described in Requirement 5.
#### 2. Inputs with Label Text
The labeled input fields can be found in *lines 49-63* of [project1.html](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.html#L49). Each input field is surrounded by an appropriate label element. The first input field requests a numerical value from 1 to 10 and has the appropriate min and max attributes to restrict input if user interacts with up and down arrows on the right side of the textbox. The second input asks for the user's name, which will be directly referenced again when satisfying Requirement 5.
#### 3. Button
The button requirement is satisfied with a Bootstrap submit button created on *line 65*, and the button's input collection and console.log functionality can be found on *lines 80-82* of the [project1.html](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.html#L80) file.
#### 4. Div for Output
The div which shows output for the guessing game is created and given attributes and an appended child paragraph with JavaScript on *lines 100-112* of [project1.html](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.html#L100). The .outputText CSS class (*lines 41-43* of [project1.css](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.css#L41)) makes the plain text of the output paragraph a different color than the rest of the page's headers and text.
#### 5. Output Paragraph for Guessing Game
The output paragraph for the guessing game is created alongside the div previously mentioned in Requirement 4. JavaScript on *lines 100-141* of [project1.html](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.html#L100) was used to retrieve user input for name and create the output paragraph and link. More specifically, the generateText method creates the div and appends a paragraph that uses the name input as part of a "Thanks for playing" sentence, and the generateLink method creates an anchor to append to the body that varies depending on if the user's number guess was lower than, higher than, or the same as a random number from 1-10 generated in the guessingGame function on *lines 89-96* of [project1.html](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.html#L89).
#### 6. Link CSS Values
The separate hover, visited, and unvisited values for the generated link are on *lines 31-39* of [project1.css](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.css#31).
#### 7. Div Frame CSS Values
The frame for non-header divs is detailed in the .borderedDiv class on *lines 56-58* of [project1.css](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.css#56). 
#### 8. Unified CSS File
The single unified CSS file used by all HTML pages in this project can be found at the following link: [project1.css](https://github.com/nrmalone/Nicholas-Malone-CIS3110/blob/main/Project%201/project1.css)
### Screenshot of project1.html
![Screenshot showing user input and generated HTML element output on project1.html page](https://raw.githubusercontent.com/nrmalone/Nicholas-Malone-CIS3110/main/Project%201/screenshot%20of%20page.png)
