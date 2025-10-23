# TODO: Implement CRUD Operations for Quiz App

- [x] Edit App.js: Add useState for questions, useEffect to fetch questions on mount, define handleAddQuestion (POST), handleDelete (DELETE), handleUpdate (PATCH) functions, pass props to components
- [x] Edit QuestionList.js: Accept questions, onDelete, onUpdate props, map over questions to render QuestionItem components
- [x] Edit QuestionForm.js: Accept onAddQuestion prop, update handleSubmit to POST new question and call onAddQuestion, reset form
- [x] Edit QuestionItem.js: Accept onDelete, onUpdate props, add onClick to delete button, add onChange to select for update
- [x] Test the application: Run npm run server and npm start, verify GET, POST, DELETE, PATCH operations
