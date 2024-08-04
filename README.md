# React Todo List with Router

In this exercise I want you to create a todo list with React Typescript. The todo list is will be simple, not any fancy functionalities or animations _(unless you relly want to get creative)_. The purpose is to solve as much as possible with React and apply a react mindset while also adding a router. I have created a React TS application to you that is ready to be used.

**Before you start, you must run a `npm install` in this folder in order to install all the dependencies. Then you do a `npm run dev` in order to start the application. NO "Live Server" usage here as Vite will fire up a development server for you.**

The exercise comes in different steps that you must follow. Each step comes with a set of user stories. A user story is basically just a requirement of your application but it comes like a description of a feature.

Read the instructions carefully and and don't try to do everything at the same time. Work user story for user story.

### Step 1 - _(No router)_

Remember here to use state und utilize props. Also place the state(s) in the appropriate component(s).

- As a user I want to be able to view all my todos in the same place, to get a good overview of what I have to do.

- As user I want to be able to add new todos to my todo list so I can update my todo list when I find something else that I need to do.

- As a user I want to mark a todo as completed so I can see which todos I have left to do.

- As a user I want to remove a todo from the list so I can keep my list as clean and short as possible.

- As a user I want a timestamp to be added to my new todos in order better se how old all the todos are.

- As a user I want to be able to put my name _(author of a todo)_ on a todo, so everyone in my family can add their own todos to the todo list.

### Step 2 - Add router

When adding a router, handling state becomes more challenging. Consider using useOutletContext - see the docs on [React Router](https://reactrouter.com/en/main) for more documentation - or use the regular built-in context in React.

- As user I still want to be able to add new todos but I would like to do it on a different page so the UI becomes more clean.

- As a user I want an about page that describes the purpose of the todo list and displays the number of todos currently in the list. This must also be on its own page seperated from the others.

### Step 3 - Advanced features

- As a user I want to be able to edit existing todos in case I remember something that has to do with a specific todo.

- As a user I want to be able to move todos up and down in order to prioritize what I have to do.

- As a user I want to be able to sort my todos after either timestamp or author.
