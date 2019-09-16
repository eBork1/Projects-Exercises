# Restaurant Website

### Description

You've been asked to design a website for a new restaurant opening at 348 E. Main St., Lexington, KY. The owners are busy working on their recipes and haven't picked a name yet, so they've asked you to suggest one and use it in your design.

The owners are still working on their recipes. They've populated an API with possible choices. You are to use the API to generate a sample menu to add to your website. The API URL is:[https://entree-f18.herokuapp.com/](https://entree-f18.herokuapp.com/).

### Table of contents

<!--ts-->

- [Project/Exercise Name](#Project-Exercise-Name)
- [Description](#Description)
- [Table of Contents](#table-of-contents)
- [MVP (Minimum Viable Product)](#MVP)
  - [Wireframe](#Wireframe)
  - [Tech Stack](#Tech-Stack)
- [Process](#process)
  - [Setup](#Setup)
  - [Develop](#Develop)
  - [Deploy](#Deploy)
- [Requirements](#Requirements)
  - [Additional Requirements](#Additional-Requirements)
  - [Stretch Goals](#Stretch-Goals)
- [Additional Resources](#Additional-Resources)
  <!--te-->

### MVP

A single page web app that serves as a restaurant splash page with menu

#### Wireframe

![wireframe](../wireframes/wireframe.png)

#### Tech Stack

- React.JS

1. HTML
2. CSS
3. JS

### Process

###### Setup:

1. [Create GitHub repo **Locally** via ](../git-instructions.md) `npx create-react-app`
2. NPM install and import/route necessary css/js libraries (E.g. Bootstrap)
3. Save all and create your first commit to `master`, **then** switch to a dev branch

###### Develop:

1. Create a `dev` branch to commit your code to
2. Add content and elements to your website
3. View changes and test locally via hot reload
4. Save often, and commit to your development branch on GitHub when important changes happen
5. Push your commits to GitHub remote
6. For bug fixes, refactored code, and feature branches, you must create a branch off of `dev` onto a `new-feature` branch and create a PR into dev when complete

###### Deploy:

1. Create a Pull Request from `dev` into `master`
2. Confirm code is up to date and works correctly
3. Post links to your GitHub repo to the Projects Slack channel

---

### Requirements

To complete the assignment, you must complete the following:

1. Generate the following information:

- The restaurant's name (give it a good one!)
- The restaurant's address
- The restaurant's hours of operation

2. Create a dynamic restaurant menu via the [API](https://entree-f18.herokuapp.com/)

- Must include at _least five_ sections for unique meal type (appetizers, breakfast before 10am, lunch menu, main course, sides, dessert, etc)
  - each meal type must include _at least_ 12 (12) entries per type of meal (bagel and lox, plate of pancakes, omelette, etc) (each section does not need strictly 12; dessert can be 5, appetizers can be 8, etc)
  - since the api generates random foods, you do not need to sort the foods, as long as you are display them in their unique sections (imagine this restaurant exists in a parallel universe where people eat whatever, whenever)
- Each Menu Section must be viewable separately in an [organism](https://patternlab.io) (for example, a bootstrap [accordion](https://getbootstrap.com/docs/4.0/components/collapse/#accordion-example) or [nav tabs](https://getbootstrap.com/docs/4.0/components/navs/#javascript-behavior))
- Each menu item must be an [molecule](https://patternlab.io) (for example, using a bootstrap card with a picture of the meal, as well as the name, and the price, etc)

3. You must use at least one [NPM package](#Recommended-NPM-Installs) to assist you with this project
4. Manage state

#### Additional Requirements

- Website must be responsive
- Style your app as you wish
- Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Repo](https://github.com/bootcamp-students/Resources).
- Your repo should be public so that others can see your code and comment on it.
  - _**Remember to push to GitHub!**_
  - Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

- Embed a Google Map showing the location of the restaurant.
- Include a different menu for each day of the week that the restaurant is open.
- Each time you access the API, you get a different menu. Save the results in local storage so that every time your website is accessed, the user gets the same menu. (Different users will see different menus; that's okay)
- Make each menu type (appetizers, main course, etc ) be the correct foods instead of random
- Parse the results of the API call to show a list of sides available for substitution (either in addition to or instead of listing sides with each entree).
- Implement DoorDash style online ordering

#### Recommended NPM Installs

- [Redux](https://www.npmjs.com/package/react-redux)
- [React Virtualized](https://www.npmjs.com/package/react-virtualized)
- [React Router](https://www.npmjs.com/package/react-router)
- [Axios](https://www.npmjs.com/package/axios)
- [Reactstrap](https://www.npmjs.com/package/reactstrap)
- [DayJS](https://www.npmjs.com/package/dayjs)
- [another instructor approved packaged](https://www.npmjs.com/)

#### If you finish early...

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
3. Add links and resources from this week to the [Class Resources Repo](https://github.com/bootcamp-students/Resources) by forking the repo and then initiating a pull request with your additions to the .md file.

### Additional Resources

- Ask questions :-)
- [Class Resources Repo](https://github.com/bootcamp-students/Resources)
- Learn more about [Good GitHub Practices](https://guides.github.com)
- [Learn JS](https://www.w3schools.com/js/)
- []()

For more information about **_doing something_**, see these articles:

- []()
- []()
- []()
- [API call / timeout visualization](http://latentflip.com/loupe/?code=JC5vbignYnV0dG9uJywgJ2NsaWNrJywgZnVuY3Rpb24gb25DbGljaygpIHsKICAgIHNldFRpbWVvdXQoZnVuY3Rpb24gdGltZXIoKSB7CiAgICAgICAgY29uc29sZS5sb2coJ1lvdSBjbGlja2VkIHRoZSBidXR0b24hJyk7ICAgIAogICAgfSwgMjAwMCk7Cn0pOwoKY29uc29sZS5sb2coIkhpISIpOwoKc2V0VGltZW91dChmdW5jdGlvbiB0aW1lb3V0KCkgewogICAgY29uc29sZS5sb2coIkNsaWNrIHRoZSBidXR0b24hIik7Cn0sIDUwMDApOwoKY29uc29sZS5sb2coIldlbGNvbWUgdG8gbG91cGUuIik7!!!PGJ1dHRvbj5DbGljayBtZSE8L2J1dHRvbj4%3D)
