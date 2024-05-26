# Todo List App

The Todo List App is a simple application built with React and the Context API. It allows you to manage your todos efficiently.

## Features

- Add new todos
- Mark todos as completed or active
- Filter todos by status (All, Active, Completed)
- Delete individual todos

## Getting Started

To get started with the Todo List App, follow these steps:

1. Clone the repository:

```bash
git clone  https://github.com/HamdiNur/Todo-List-App/upload/main
```

2. Navigate to the project directory:

```bash
cd react-todo-list-app
```

3. Install the dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

The app will be available at `http://localhost:5173/`.

## Usage

1. To add a new todo, simply enter the task in the input field and press Enter or click the "Add" button. This will add the todo to the list.
2. To mark a todo as completed or active, just click on the corresponding todo item. This action will toggle the status of the todo.
3.You can use the "All", "Active", or "Completed" buttons to filter the todo list based on their status. Selecting a specific filter will show only the todos that match that status.
4. If you want to remove a todo from the list, click on the Remove Button associated with that particular todo. This will delete the todo permanently.

## Project Structure

The project consists of the following files and directories:

- `src/`
  - `components/`
    - `TodoForm.jsx`
    - `TodoList.jsx`
    - `TodoFilter.jsx`
    - `TodoItem.jsx`
  - `TodoProvider/`
    - `TodoContext.jsx`
  - `hooks/`
    - `useInput.js`
    - `useLocalStorage.js`
  - `App.jsx`
  - `index.css`
  - `main.jsx`
- `README.md`
- `package.json`
- `tailwind.config.js`

## Dependencies

The Todo List App relies on the following dependencies:

- React
- React DOM
- Tailwind CSS

## Contributing

if you come across any issues or have suggestions for improvements, please don't hesitate to open a new issue or submit a pull request. Your input is valuable and greatly appreciated.

## Author

The Todo List App is developed by Hamdi Nur Moallim Ai. You can contact me at hamdoonur26@gmail.com.
