Overview:-
This is a simple Todo app built using React that allows users to perform CRUD (Create, Read, Update, Delete) operations on todos. It uses functional components, React hooks (useState, useEffect), and integrates with an external API.

Key Features:-
1. Add Todos: Users can create new todos.
2. Edit Todos: Users can modify existing todos.
3. Delete Todos: Users can remove todos from the list.
4. Todo List Display: Displays all the todos in a table format.

Design Decisions:-
1. Component Structure: Divides the app into ViewBox (state management) and presentational components (InputForm, TodoTable).
2. State Management: Uses React’s useState for managing input, todo list, and edit status.
3. API Integration: Communicates with backend using async API functions (fetchTodos, createTodo, updateTodo, deleteTodo).


Optimizations:-
1. Efficient state updates using immutability.
2. Conditional rendering to handle adding and updating todos.
3. Uses useEffect for data fetching on mount.
4. Potential Improvements
5. Add error handling and loading states for better user experience.

Limitations:-
1. Error Handling: Basic error handling exists but is not robust. There is no user-friendly display of errors when something goes wrong with API calls.
2. No Validation: There is no input validation, so users can add empty todos, which may not be ideal.
3. No User Feedback: There is no feedback mechanism (e.g., loading spinner, success/error messages) while API calls are being processed.
4. Limited Styling: The app lacks advanced styling or UI components to make the experience more polished.


Potential Improvements:-
1. Error Handling: Improve error handling to show user-friendly messages when API requests fail.
2. Input Validation: Add validation to prevent empty todos from being submitted.
3. Loading Indicators: Show loading indicators while fetching or updating todos.
4. Optimistic UI Updates: Implement optimistic updates for faster user interactions, particularly for adding and deleting todos.
5. Pagination/Filtering: For large todo lists, implement pagination or filtering to improve performance and usability.
6. User Authentication: Integrate user authentication to allow different users to manage their own todo lists.

Setup instructions:-
1. After opening link download zip folder amd unzip folder
2. After Unzip folder open folder in visual studio code editor 
3. After opening folder in terminal type 'npm i' and wait for few minutes
4. After installing start project by command 'npm start'
5. Porject will start in few minutes.
