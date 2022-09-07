# Javascript Project

Project Name: The Hungry Snake

Description: 
It's a really interesting Snake Game. In this game there is a snake who is running for his food. So we can say snake is hungry..thats why i named it "The Hungry Snake".

a. WHY this project was chosen (what use case does it solve)?

I created this game beacuse i was thinking of any game project and i found this game is really interesting & there a lot of fun in playing this game. This game has all the features that of a classic Snake game. 

1. we can easily run this game in any browser and play it.
2. I intorduced music along with the snake move, when snake eats food, and when snake collides with wall or with its    own body part & this music and different sound makes it more interesting & lovable.




b. HOW did you make the project ?

I made this project using two technical languages: HTML, CSS & Javascript. 

-> HTML: 

Hypertext Markup Language or html is the standard markup language for documents designed to be displayed in a web browser. 

HTML describes the structure of a web page semantically and originally included cues for the appearance of the document.

HTML elements are the building blocks of HTML pages. With HTML constructs, images and other objects such as interactive forms may be embedded into the rendered page.

-> CSS:

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML.

CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts.

This separation can improve content accessibility; provide more flexibility and control in the specification of presentation characteristics; enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file, which reduces complexity and repetition in the structural content; and enable the .css file to be cached to improve the page load speed between the pages that share the file and its formatting.

-->JS

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments.

JavaScript is a very popular scripting language which is used on the client-side to make web pages interactive. Where HTML and CSS are languages that give structure and style to web pages, JavaScript gives interactive elements to web pages that engage a user.

Internally i used various functionalities to run this game such as:

1. I created objects for the initial direction of snake & food and many variables that are used in different functionalities like for sound, music , speed ,score and so on.

2. There is a Main function in the game which is using "window.requestAnimationFrame() method". The window.requestAnimationFrame() method tells the browser that you wish to perform an animation and requests that the browser calls a specified function to update an animation before the next repaint. 

3. There is a game engine which is working in two parts:

part1: After every movement of snake we are updating the snake array & Food.

Part2: It is responsible for displaying the snake and Food inside the Grid playground.

In these parts we have different functions like:

1. Main function: to update an animation.

2. isCollide: which is taking care of snake collision with wall or with its own body part.

3. I have used Event listener to listens for the event occured when user press any key arrow keys for playing the game. 

4. Putted some conditions like if snake have eaten the food, increament the score and regenerate the food.




c. WHAT features, technical things you had implemented?

1. Used Event listener for listening to the event occured when user press any key arrow keys for playing the game. 

2. Used of localStorage for storing the Hi-Score every time & getting the stored scores through localStorage.

3. Used "window.requestAnimationFrame() method". The window.requestAnimationFrame() method tells the browser that you wish to perform an animation and requests that the browser calls a specified function to update an animation before the next repaint. 

4. Interesting music & sound playing on every movement of snake as well as on Game Over.

5. Applied Media Query to provide responsiveness to the game & make it device friendly.
