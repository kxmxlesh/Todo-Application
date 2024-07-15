### Project Description: Todos Application

The Todos Application is a fully functional, interactive to-do list application built using HTML, CSS, and JavaScript. This application allows users to add, manage, and persist their to-do items efficiently. It utilizes local storage to maintain the state of the to-do list even after the page is reloaded.

#### Features:
1. **Adding Todo Items:**
   - Users can add a new todo item using an HTML input element.
   - The input element includes a placeholder text to guide the user on what to do.
   - A new todo item is added when the user input is not empty, and the "Add Todo" button (with id `addTodoButton`) is clicked.
   - An alert is shown if the user attempts to add a todo item with an empty input field.

2. **Checkbox and Label:**
   - Each todo item includes a checkbox and a label.
   - The label text is struck through when the checkbox is checked, indicating that the item is completed.

3. **Delete Functionality:**
   - Each todo item has a delete icon.
   - Clicking the delete icon removes the todo item from the list.

4. **Adding Multiple Todo Items:**
   - Multiple todo items can be added using an array of todo objects and a `for...of` loop to iterate through the array.

5. **Persisting Todos:**
   - The todo list is stored in the local storage, ensuring that the list persists even after the page is reloaded.
   - On reloading, the application retrieves the todo list from local storage and displays it.

6. **Updating and Persisting Checked Status:**
   - The checked status of each todo item is updated in the local storage.
   - The checked status is persisted even on reloading the page.

7. **Deleting Todos from Local Storage:**
   - When a todo item is deleted, it is also removed from the local storage.
   - The application uses the `findIndex` method to locate the todo item in the list and the `splice` method to remove it.

#### How It Works:
1. **Adding a Todo Item:**
   - Users enter a todo item in the input field and click the "Add Todo" button.
   - The application checks if the input is not empty and adds the todo item to the list.
   - If the input is empty, an alert is shown.

2. **Managing Todos:**
   - Each todo item is displayed with a checkbox, label, and delete icon.
   - Checking the checkbox strikes through the label text.
   - Clicking the delete icon removes the todo item from the list.

3. **Persisting Data:**
   - The application stores the todo list and the checked status of each item in the local storage.
   - On page reload, the todo list and checked statuses are retrieved from local storage and displayed.

#### Technologies Used:
- **HTML:** Structure of the application.
- **CSS:** Styling of the application.
- **JavaScript:** Functionality for adding, deleting, and persisting todo items.

#### Setup Instructions:
1. Clone the repository from GitHub.
2. Open `index.html` in a web browser to run the application.

This project is an excellent practice for understanding and implementing DOM manipulation, event handling, and local storage in web development.

# Refer To Below Image :

https://nkb-backend-media-static-tenxiitian.s3.ap-south-1.amazonaws.com/tenxiitian_prod/programs/Tech+Programs/frontend-content/ccbp/coding-practice-questions/dynamic-webapps/todo-application-part-5-v1.gif
