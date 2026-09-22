# Today Todo List

A simple, responsive todo list built as a single HTML page. It helps you capture tasks, track progress, and keep a small daily list organized.

## Features

- Add new tasks
- Mark tasks as complete or open
- Delete tasks
- Filter tasks by all, open, or done
- View remaining task count and completion percentage
- Persist tasks in browser `localStorage`
- Responsive layout for desktop and mobile screens
- No build tools or external dependencies

## Run Locally

Open `index.html` in a web browser.

You can also use the **Five Server** or **Live Server** extension in VS Code for automatic browser refresh while editing.

## Usage

1. Enter a task in the input field.
2. Select **Add task** or press Enter.
3. Select the circle beside a task to mark it complete.
4. Use **All**, **Open**, or **Done** to filter the list.
5. Select the `x` button to remove a task.

Tasks are stored locally in the browser for this page. Clearing the browser's site data removes the saved tasks.

## Project Structure

```text
todo-list/
├── index.html
└── README.md
```

## Technology

- HTML
- CSS
- Vanilla JavaScript
- Browser `localStorage` API
