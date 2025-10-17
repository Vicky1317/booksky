# booksky.com

1.	Objective
To design and develop a responsive To-Do List web application using HTML, CSS, and JavaScript that allows users to add, view, and delete tasks interactively.
2.	Tools & Technologies Used
HTML5 – For webpage structure CSS3 – For styling and layout
JavaScript – For interactivity and DOM manipulation Visual Studio Code – Code editor
3.	Project Description
The To-Do List project is a simple, user-friendly web application that helps users manage their daily tasks effectively. Users can add new tasks using a popup form, view them in a card layout, and delete them when completed. The app dynamically updates without page reloads using JavaScript event handling and DOM manipulation.
4.	Features Implemented
•	Add new tasks dynamically
•	Delete existing tasks
•	Popup overlay for adding tasks
•	Responsive and interactive interface
•	Smooth and clean user experience

5.	Code Explanation
The HTML file provides structure with containers for task display and popup forms. CSS handles the styling, layout, and popup effects. JavaScript manages interactivity—opening the popup, creating new task elements, and deleting them with event handlers.

Example Code Snippet:

addbook.addEventListener('click', function() { event.preventDefault();
var div = document.createElement('div'); div.setAttribute('class','book-container');
div.innerHTML = `<h2>${booktitleinput.value}</h2><h5>${bookau
 
thorinput.value}</h5><p>${bookdescriptioninput.value}</p><but ton onclick='deletebook(event)'>Delete</button>`; container.appendChild(div);
popupoverlay.style.display = 'none'; popupbox.style.display = 'none';
});

6.	Output
The application displays a neatly styled list of tasks on the screen. A '+' button opens a popup for adding new tasks, and each task can be deleted easily using the delete button.


7.	Learning Outcomes
•	Hands-on experience with DOM manipulation
•	Understanding of event handling in JavaScript
•	Practice with creating and removing HTML elements dynamically
•	Skills in CSS positioning and popup design
•	Improved UI/UX design sense

8.	Conclusion
The To-Do List Project successfully demonstrates the use of JavaScript to build dynamic and interactive web applications without external frameworks. It enhances productivity and strengthens understanding of front-end development principles.
