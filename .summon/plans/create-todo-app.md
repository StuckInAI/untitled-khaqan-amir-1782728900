---
status: pending
title: Create a Todo Application
---

1. Create the main layout and structure for the application in `/app/src/App.tsx`.
2. Define the data structure for a todo item in `/app/src/types/todo.ts`.
3. Create a custom hook for managing todos (adding, toggling, deleting) in `/app/src/hooks/useTodos.ts`.
4. Build the todo input component in `/app/src/components/TodoInput.tsx` to allow users to add new tasks.
5. Build the todo item component in `/app/src/components/TodoItem.tsx` to display individual tasks with options to mark as complete or delete.
6. Build the todo list component in `/app/src/components/TodoList.tsx` to render the collection of tasks.
7. Update the main entry point `/app/src/main.tsx` and global styles in `/app/src/styles/global.css` to ensure the app is styled correctly with Tailwind CSS v4.
8. Integrate all components into the main page in `/app/src/pages/Home.tsx` or `/app/src/App.tsx`.