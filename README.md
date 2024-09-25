# GUI Task

## Goal/Objective

Create a basic To-Do List component using React (A JavaScript framework). The component should allow users to add, delete, and mark tasks as completed.

## Prerequisites

1. **HTML:** HTML (HyperText Markup Language) is the standard markup language for documents designed to be displayed in a web browser. You should understand how to create and manipulate HTML elements, as they form the backbone of any web page.
2. **CSS (optional if you use Bootstrap):** CSS (Cascading Style Sheets) is a stylesheet language used for describing the look and formatting of a document written in HTML. It is used to style the layout of web pages. You should understand how to apply styles to HTML elements, work with classes and IDs, and use selectors.
3. **JavaScript:** JavaScript is a high-level, interpreted scripting language that is a core technology of the World Wide Web, alongside HTML and CSS. It is essential for creating interactive web pages and is an integral part of web applications. You will need to have a solid understanding of JavaScript fundamentals such as variables, data types, functions, control structures, and the Document Object Model (DOM).
4. **React:** React is a JavaScript library for building user interfaces, especially single-page applications. You'll need to understand how to create components, manage state and props, and handle events. Knowledge of hooks, such as useState and useEffect, is also beneficial. These hooks allow you to use state and other React features without writing a class.
5. **Node.js and npm (Optional for now):** Node.js is a runtime environment that executes JavaScript code outside a web browser. npm (Node Package Manager) is a package manager for Node.js. You will need these tools to create a new React project and manage its dependencies.
6. **Git/GitHub:** Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. You should understand how to create a repository, make commits, push changes, and pull updates.
7. **JavaScript ES6 features (optional):** ES6, also known as ECMAScript 2015, is a version of JavaScript that includes a variety of new features like arrow functions, class declaration, let and const, destructuring assignment, etc. These features are commonly used in modern JavaScript development, including React.
8. **React Bootstrap (optional):** React Bootstrap is a front-end framework that replaces the Bootstrap JavaScript. Each component has been built from scratch as true React components, without unneeded dependencies like jQuery. It allows you to use Bootstrap as the theme of your React applications.
9. **Strapi (optional):** Strapi is an open-source headless CMS (short for Content Management Systems) that allows you to quickly create and maintain RESTful JavaScript APIs. Strapi helps create both simple and complex backends for both individuals and organizations.
10. **React Hooks (optional):** React Hooks were introduced in React 16.8; they allow the use of state and other React features by using functional components. For a To-do List project, you might need to use useState hook.

## Task Outline

Make a new local GitHub repository using `git init`. This is the repo that you'll be submitting as a compressed file (ZIP) when you are done. Make sure that you regularly commit to this repository.

Within the git repo, make a new React app that follows the [Project Structure Outline](https://www.notion.so/GUI-Task-902f3ab43f304b319428e18c0dc91a66?pvs=21). Make sure that you make a new directory in `src/components` called `TaskList` that contains all code for that component (such that your implementation is modular to the React app). Additionally, your component must be added to `App.js` which should act as the main page.

NOTE: You may either use `.js`, `.jsx`, `.ts`, or `.tsx` – I do not mind any.

Your goal is to create a React component that acts as a Todo list with the following functionality:

1. **Task List** - A list of all tasks.
2. **TODO Page and Completed Page** - Two different pages to display tasks you have left and the ones that are completed.
3. **Task Description** - Provides a description and/or notes for tasks.
4. **Due Dates** - Lets you specify due dates for tasks (if they have one).
5. **Add Task** - Lets you add a new task to the task list. This is where the user would input all the task information (due dates, description, tags, etc.).
6. **Task Completed** - Functionality to complete a task.
7. **Delete Task** - This lets you delete a task such that it is neither on the TODO Page nor the Completed Page.
8. **Export List** (Optional) - A button that lets you download all the current tasks as a JSON object.

### Unique Feature:

You must implement one of the following features based on the last digit of your student number:

- **0-2:** If you click on the task, it opens up a card view. This card view should include an almost pop-up view of the task you have clicked on.
- **3-5:** Add a tag feature to tasks. Each task can contain up to 3 tags. You must create a way to add new tags and include adding tags during task creation.
- **6-7:** Similar to `1`, add the tag feature to tasks (up to 3 tags per task). However, you can predefine the tags so that the user does not have to add new tags. Additionally, create a tag-based view filter for tasks (e.g., filtering for the “Homework” tag shows only tasks with the “Homework” tag).
- **8-9:** Add a Start Date and an End Date for each task and add a Gantt Chart View. This lets you view all tasks that have not yet been completed within a Gantt chart, allowing you to see completion timelines for tasks.

## Project Structure

What you will be submitting is a React app that contains one main page with the component on it. The workspace should follow a structure similar to this:

- `node_modules`
- `src/`
    - `components/`
        - `TaskList/`
            - `TaskList.js` - the main component that is added to App.js
            - `...` - add as many sub-components as you need. For example, this could include something like AddTask.js or TaskCard.js (for viewing all information about tasks)
            - `TaskList.module.css` (optional) - All your CSS for the TaskList component
    - `App.js` - The page that gets rendered
    - `App.css`
- `package-lock.json`
- `package.json`

## Requirements

- [ ] Create a new React App.
- [ ] Make the React App directory into a Git repository.
- [ ] Make a Task List View.
- [ ] TODO Tasks Page.
- [ ] Completed Tasks Page.
- [ ] Add Tasks Feature.
- [ ] Due Dates Feature.
- [ ] Task Completion Feature.
- [ ] Delete Task Feature.
- [ ] Make at least one commit for each component (modular commits).
- [ ] Implement the unique feature based on the last digit of your student number (If you like a challenge, do all of them 😈).

## Submission

Once you have completed the task, you must submit your solution to the task by filling out the following form: [YURS Software Entrance Task Submission](https://forms.gle/rt4sNMuXR9Ve1uSS7).

### Submission Deliverables:

- A link to a zip file (compressed file) that contains the repository holding your solution to the task (must have your changes organized as commits). The repo should follow the project structure outlined above.
- A link to a video that demonstrates the React component and all its features.
