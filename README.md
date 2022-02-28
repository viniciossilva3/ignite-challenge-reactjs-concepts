<h1 align="center">to.<strong>do</strong></h1>

<p align="center">Solution - Ignite ReactJS Challenge 01 </p>

<br>

<p align="center">
  <img alt="Gif" src="https://user-images.githubusercontent.com/56976328/154355775-2a9bb441-09ff-4b6f-84bc-25a5cfe122b5.gif" />
</p>

# 💻 About the challenge

In this challenge, you must create an application to train what you have learned so far in ReactJS

This will be an application where your main objective is a small to-do application, to train a little more about state manipulation in React.

- Add a new task
- Remove a task
- Mark and unmark a task as complete

<br>


## About the challenge :open_file_folder::

In this challenge, you will have to create an application to train what you have learned so far in ReactJS

This will be an application where your main objective is a small application of activities to do, to train a little more about state manipulation in React.

- Add a new task
- Remove a task
- Mark and unmark a task as completed

Below we will see in more detail what and how it needs to be done 🚀

## Test specification :dart::

In each test, there is a brief description of what your application must comply with in order for the test to pass.

For this challenge, we have the following tests:

### Test TaskList.spec.tsx

- **should be able to add a task**

For this test to pass, you must allow the task to be created and, with that, displayed on the screen. The created taks must contain attributes following the interface pattern, which is:

```ts
interface Task {
  id: number;
  title: string;
  isComplete: boolean;
}
```

- **should not be able to add a task with an empty title**

For this test to pass, before creating a new task, you must validate if something was typed in the input and not allow the creation of the task if the value is empty, if the value entered is empty, you must prevent the creation of the task.

- **should be able to remove the task**

For this test to pass, you must allow that, when clicking on the button with a trash can icon, the task related to that button is removed from the application state, consequently being removed from the screen.

- **should be able to check a task**

In order for this test to pass, you must allow by clicking on the checkbox next to the task, it is marked as completed or not completed according to its current state, changing its `isComplete` value from `false` to `true` or rather, from `true` to `false`.

## Getting started :desktop_computer::

**Clone the project and access the folder**

```bash
$ git clone https://github.com/viniciossilva3/ignite-challenge-reactjs-concepts.git && cd ignite-challenge-reactjs-concepts
```

**Follow the steps below**

```bash
# Install the project dependencies
$ yarn

# Start the application
$ yarn dev
```

## How to contribute :thinking::

**Make a fork of this repository**

```bash
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.

$ gh repo fork viniciossilva3/ignite-challenge-reactjs-concepts
```

**Follow the steps below**

```bash
# Clone your fork
$ git clone your-fork-url && cd ignite-challenge-reactjs-concepts

# Create a branch with your feature
$ git checkout -b my-feature

# Make the commit with your changes
$ git commit -m 'feat: My new feature'

# Send the code to your remote branch
$ git push origin my-feature
```

After your pull request is merged, you can delete your branch

## License :memo::

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

# Author :man_technologist::

Made with :heart: by **Vinícios** meu :point_right: [Linkedin](https://www.linkedin.com/in/vinicios-batista-da-silva/)





