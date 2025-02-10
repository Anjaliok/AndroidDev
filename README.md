📌 Description of the To-Do List App

📌 Overview

This To-Do List App is a simple yet powerful web application that helps users add, prioritize, update, and delete tasks. It uses HTML, CSS, and JavaScript to provide an interactive and user-friendly experience.


---

📌 Features of the App

✅ 1. Add Tasks

Users can enter a task and assign a priority level (Low, Medium, High).

The task is displayed in a list with a colored priority indicator.


✅ 2. Mark Tasks as Completed

Clicking on a task strikes it out to show that it is completed.

Completed tasks automatically get deleted after 5 seconds.


✅ 3. Update/Edit Tasks

Users can edit a task by clicking the "Edit" button.

A prompt appears allowing the user to update the task name.


✅ 4. Delete Tasks

Tasks can be deleted manually using the "X" button.

Completed tasks are automatically removed after 5 seconds.



---

📌 Technologies Used

1️⃣ HTML (HyperText Markup Language)

Used to structure the app, including:

Input Field: For entering new tasks

Select Dropdown: For choosing priority levels

Buttons: To add, edit, and delete tasks

Unordered List (<ul>): To display tasks


2️⃣ CSS (Cascading Style Sheets)

Used for styling and enhancing the user experience:

Layout Styling: The app is centered and visually appealing

Priority Indicators:

Red Border = High Priority

Orange Border = Medium Priority

Green Border = Low Priority


Hover Effects: Buttons change color when hovered

Task Completion Styling: Completed tasks are gray with a line-through effect


3️⃣ JavaScript (JS)

Used to make the app interactive and functional:

Adding Tasks: Captures user input and displays it in the list

Marking Tasks as Completed: Adds a completed class when clicked

Auto-Deleting Completed Tasks: Removes completed tasks after 5 seconds

Editing Tasks: Prompts the user to update a task when they click "Edit"

Deleting Tasks: Removes tasks when clicking "X"



---

📌 How the Code Works

1️⃣ index.html (HTML File)

Contains the structure of the app

Includes input fields, buttons, and a task list (<ul>)

Links to CSS (styles.css) and JavaScript (script.js)


2️⃣ styles.css (CSS File)

Styles the entire app with a clean and modern look

Colors are used to differentiate task priorities

Buttons have hover effects for better usability


3️⃣ script.js (JavaScript File)

Defines the main functionality of the app

Listens for button clicks and task selections

Uses DOM manipulation to add, update, and delete tasks dynamically

Implements auto-delete for completed tasks



---

📌 How to Use the App

1️⃣ Enter a Task in the text input field
2️⃣ Choose a Priority from the dropdown (Low, Medium, High)
3️⃣ Click “Add” to add the task to the list
4️⃣ Click a Task to mark it as completed (auto-deletes after 5 seconds)
5️⃣ Click “Edit” to update the task name
6️⃣ Click “X” to delete a task manually


---

📌 Future Enhancements (Possible Upgrades)

Would you like me to add the following features?
✅ Local Storage (Save tasks even after page refresh)
✅ Due Dates & Reminders
✅ Dark Mode for better UI experience
