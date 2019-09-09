# Calculator

### Description

Create an in-browser calculator

For this project we will be using math

### Table of contents

<!--ts-->

- [Project/Exercise Name](#Calculator)
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

By default, you should create a working responsive calculator that can perform the basic operations described in the requirements

#### Wireframe

![wireframe-js-calculator.png](../wireframes/calculator.png)

#### Tech Stack

1. HTML
2. CSS
3. JS

### Process

##### Setup:

1. Create repo, for example: `my-app`
2. Locally, navigate to your `sites` folder in the terminal
3. `git clone` + `your-repo-name` into your Sites folder
4. Create necessary files for application and view in VS Code
   - Run shell script to expedite process unless you are using a framework
   - _If you are using a framework, disregard the "Application File Structure" section_
5. Import and route necessary css/js files (E.g. Bootstrap)
6. Save all and create your first commit to `master`

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

##### Deploy:

1. Create a Pull Request from `dev` into `master`
2. Confirm code is up to date and works correctly
3. Post links to your GitHub repo to the Projects Slack channel

---

### Requirements

To complete the assignment, you must complete the following:

1. You must not use eval()
2. The calculator should have a display area at the top.
3. The display should show `0` by default.
4. The calculator should have 6 function buttons:
   - Division `/`
   - Multiplication `*`
   - Subtraction `-`
   - Addition `+`
   - Calculate `=`
   - Clear `c`
5. The calculator should have 10 number buttons, `0-9`.
6. The calculator should have a decimal button `.`
7. The calculator should store three values internally:
   - The first number entered by the user (possibly multi-digit and decimal)
   - The operator selected by the user `/`, `x`, `-`, `+`
   - The second number entered by the user (possibly multi-digit and decimal)
8. The display area should update as a user presses number buttons.
9. When the user clicks a function button after the first and second values are entered (instead of `=`), the result of the calculation should be saved and the calculator should allow for a new number input (for example: `1` then `+` then `3` then `-`, etc.)
10. When the calculate button `=` is pressed, the calculator should apply the operation to the two stored numbers in the appropriate order (important for subtraction and division) and update the display.
11. When the clear button `c` is pressed, all stored data should be erased and the display should show `0` again.

#### Additional Requirements

- Website must be responsive
- Style your app as you wish
- Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Repo](https://github.com/bootcamp-students/Resources).
- Your repo should be public so that others can see your code and comment on it.
  - _**Remember to push to GitHub!**_
  - Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

- Show all buttons that were pressed until `c` in the display area.

```
Example:

  12 + 34
```

- Continue to store two numbers and the operator; only the display
  should change.
- Allow an arbitrary amount of numbers and operators to be stored. (running log)
- Accept keyboard input
- Undo button
- Button that holds a value or function of choice (for example: button that automatically calculates the tip)
- Use recursion to calculate the results
- Turn it into a graphing calculator

#### If you finish early...

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
3. Add links and resources from this week to the [Class Resources Repo](https://github.com/bootcamp-students/Resources) by forking the repo and then initiating a pull request with your additions to the .md file.

### Additional Resources

- Ask questions :-)
- [Class Resources Repo](https://github.com/bootcamp-students/Resources)
- Learn more about [Good GitHub Practices](https://guides.github.com)
- [Learn JS](https://www.w3schools.com/js/)

For more information about computer math, see these articles:

- [eval() is Evil](https://stackoverflow.com/questions/86513/why-is-using-the-javascript-eval-function-a-bad-idea)
- [Computer math article](https://medium.com/swlh/how-computers-do-math-11af23139db)
- [Computer math examples](https://www.w3schools.com/js/js_numbers.asp)
- [Computer math common problem example](https://0.30000000000000004.com/)
- [Why do computers suck at math](https://blog.codinghorror.com/why-do-computers-suck-at-math/)
