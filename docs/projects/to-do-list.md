# To-Do List

### Description

Create an online to-do app

For this project we will be using vanilla JavaScript to manage state and local storage to keep track of data

### Table of contents

<!--ts-->

- [Project/Exercise Name](#To-Do-List)
- [Description](#Description)
- [Table of Contents](#table-of-contents)
- [MVP (Minimum Viable Product)](#MVP)
  - [Wireframe](#Wireframe)
  - [Tech Stack](#Tech-Stack)
- [Process](#process)
  - [Setup](#Setup)
  - [Application File Structure](#Application-File-Structure)
  - [Develop](#Develop)
  - [Deploy](#Deploy)
- [Requirements](#Requirements)
  - [Additional Requirements](#Additional-Requirements)
  - [Stretch Goals](#Stretch-Goals)
- [Additional Resources](#Additional-Resources)
  <!--te-->

### MVP

By default, the app should display items on to do list

#### Wireframe

![to-do-list](../wireframes/to-do-list.gif)

#### Tech Stack

1. HTML
2. CSS
3. JS

### Process

##### Setup:

1. [Create GitHub repo (either online or locally)](../git-instructions.md), for example: `my-app`
2. Create necessary files for application and view in VS Code
   - Run shell script to expedite process unless you are using a framework
   - _If you are using a framework, disregard the "Application File Structure" section_
3. Import and route necessary css/js files (E.g. Bootstrap)
4. Save all and create your first commit to `master`, **then** switch to a dev branch

###### Application File Structure

Minimally:

```
web/
    index.html - main page
    css/ - folder to contain CSS files
        style.css - main stylesheet
    img/ - folder to contain any images
    js/ - folder to contain JavaScript files
        main.js - main JavaScript file
README.md - any important information
.gitignore - file that omits any directory/file from being tracked
```

Additional pages will be relative to the index.html file.

It is okay if your project has more files and directories, but you at least need the ones listed above.

##### Develop:

1. Create a `dev` branch to commit your code to
2. Add content and elements to your website
3. View changes and test locally
4. Save often, and commit to your development branch on GitHub when important changes happen
5. Push your commits to GitHub remote
6. For bug fixes, refactored code, and feature branches, you must create a branch off of `dev` onto a `new-feature` branch and create a PR into dev when complete

##### Deploy:

1. Create a Pull Request from `dev` into `master`
2. Confirm code is up to date and works correctly
3. Post links to your GitHub repo to the Projects Slack channel

---

### Requirements

To complete the assignment, you must complete the following:

1. Dynamically Render the content in JavaScript
2. Use Local Storage to store all to-do list data in the browser
3. Display all to-do list items
4. Prompting text to add item
5. Ability to remove item (soft delete / archive)
6. Cross out or check off item as "completed"
7. Remove all completed items (soft delete / archive)
8. Ability to see number of remaining items
9. Ability to check off or cross out all items in one click as a "completed all" function
10. Ability to press a button and all items become active again
11. Three "views" for the user:

- All to-do list items
- Only completed items
- Only active non-completed items

#### Additional Requirements

- Website must be responsive
- Style your app as you wish
- Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Repo](https://github.com/bootcamp-students/Resources).
- Your repo should be public so that others can see your code and comment on it.
  - _**Remember to push to GitHub!**_
  - Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

- Create a flow diagram for the front end architecture to be used in an MVP
- Use MySQL
- Edit To-Do's in place

#### If you finish early...

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
3. Add links and resources from this week to the [Class Resources Repo](https://github.com/bootcamp-students/Resources) by forking the repo and then initiating a pull request with your additions to the .md file.

### Additional Resources

- Ask questions :-)
- [Class Resources Repo](https://github.com/bootcamp-students/Resources)
- Learn more about [Good GitHub Practices](https://guides.github.com)
- [Learn JS](https://www.w3schools.com/js/)
- [Why Can't Anyone Make a Decent To-Do App?](https://www.wired.com/2016/03/best-to-do-list-app/)

For more information about state management, see these articles:

- [What is State Management](https://codeburst.io/state-management-in-javascript-15d0d98837e1)
- [State Management how to](https://www.dofactory.com/javascript/state-design-pattern)
- [The future of JavaScript state management is less state management...](https://medium.com/@amcdnl/the-future-of-javascript-state-management-is-less-state-management-ba1d97b99308)
