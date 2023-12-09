# Task-List
A Javascript Task List

# What is it
An Application built in JavaScript. a Task List or in other words a to do list. 
The idea of the application is for a user to write tasks they need complete, and this will help organize the users life.
The application also comes with a built in music player, which plays music from the music.mp3 file. This music helps the user 
keep their attraction and focus on the application.

# How to use the application
A user writes a chosen task in the text box, then the user will need to press the box with the plus sign in order to add 
the chosen task. The user can also click the play button in order to play music. To remove completed or unwanted tasks the user
can click the task two times.

# How to run the app
Just double click on the html file, and a new tap will open in your chosen browser


![Screenshot 2023-12-08 at 10 57 59 PM](https://github.com/had2020/Task-List/assets/59424667/528ff575-0b17-4875-adb4-1f61bbf76924)

------------------------------------

# How does the code work 

HTML
The HTML file contains the basic structure and content of the web page It consists of the following elements

A head element that contains metadata and links to the external CSS and JavaScript files
A body element that contains the visible content of the web page
A h1 element that displays the title of the web page as Task List
A div element with the class container that wraps the input field the button and the todo list
An input element with the id inputField and the type text that allows the user to enter a task
A button element with the id addToDo and the text  that allows the user to add a task to the list
A div element with the class todos and the id toDoContainer that contains the list of tasks
A script element that links to the external JavaScript file that contains the logic of the application
An audio element with the controls and autoplay attributes that plays a music file in the background It has a source element that specifies the path and the type of the music file and a fallback text for browsers that do not support the audio element

Some Docs for you - https://developer.mozilla.org/en-US/docs/Web/HTML

------------------------------------

CSS
The CSS file contains the styles of the web page It consists of the following rules

A rule that applies to the html and body elements and sets their width to 70 of the viewport width centers them horizontally uses a different font family and sets the background color to a light gray
A rule that applies to the element with the class container and sets its width to 70 of its parent elements width
A rule that applies to the element with the id inputField and sets its width to 60 of its parent elements width its height to 20 of its parent elements height removes the default border and outline adds a custom border of 4 pixels solid red sets the font size to 16 pixels and aligns it vertically with the middle of its parent element
A rule that applies to the element with the id addToDo and sets its height and width to 20 of its parent elements height adds a custom border of 4 pixels solid red sets the font size to 18 pixels and aligns it vertically with the middle of its parent element
A rule that applies to the elements with the class paragraphstyling and removes the default margin changes the cursor to a pointer and sets the font size to 14 pixels
A rule that applies to the element with the class todos and adds some margin on top of the element to create some space
JavaScript
The JavaScript file contains the logic of the application It consists of the following steps

Get the elements by their ids and store them in variables addToDoButton toDoContainer and inputField
Add an event listener to the button that triggers a function when clicked The function does the following
Create a paragraph element and store it in a variable paragraph
Add the class paragraphstyling to the paragraph element
Set the inner text of the paragraph element to the value of the input field
Append the paragraph element to the todo container element
Clear the value of the input field
Add an event listener to the paragraph element that triggers a function when clicked The function does the following
Add a linethrough style to the paragraph element
Add an event listener to the paragraph element that triggers a function when doubleclicked The function does the following
Remove the paragraph element from the todo container element

some Docs for you - https://developer.mozilla.org/en-US/docs/Web/CSS

and some more Docs - https://developer.mozilla.org/en-US/docs/Web/JavaScript
------------------------------------


https://github.com/had2020/Task-List/assets/59424667/ff9f6f16-d7c0-4d49-82fb-eb087b1f22e8

-------------------------------------------------------------
Have a Wonderful Day!
