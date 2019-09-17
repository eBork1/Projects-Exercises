# Attack of the Clones

### Description

Create a webpage that clones an already existing app

For this project we will be using React.js to create components, and Laravel to create templates and pages. We will also be following the [Atomic Design Principles](https://patternlab.io)

### Table of contents

<!--ts-->

- [Project/Exercise Name](#Attack-of-the-Clones)
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

By default, the clone app should replicate the design and functionality of the real app front end as closely as possible. The back end is not required to complete the project besides basic CRUD in one area of the app

#### Wireframe

- [Gmail wireframe](https://mail.google.com/mail/u/0/)
- [Twitter wireframe](https://twitter.com/awesome_inc)
- [Slack wireframe](https://app.slack.com/client/TKV4DCHDH/CL8LDQGTY)
- [Trello wireframe](https://trello.com/b/0Bn39pyt/bootcamp-f19)
- Or choose your own! (tell us first so we can approve it)

#### Tech Stack

1. HTML
2. CSS
3. JS
4. React.JS
5. MySQL
6. PHP
7. Laravel

### Process

##### Setup:

1. Create repo **locally**, for example: `my-app`
2. Locally, navigate to your `sites` folder in the terminal
3. Create necessary files for application and view in VS Code via CLI
4. Initialize directory as repo and [link to existing repo you created on GitHub](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line)
5. Import and route necessary css/js files (E.g. Bootstrap)
6. Save all and create your first commit to `master`

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

1. Deconstruct the webapp you plan to clone (do not worry about matching fonts or images/colors, we are only concered with design layout and components/functional features)
2. Follow atomic design principles for deconstructing the original web app look

   - Atoms -> Molecules -> Organism (component)

3. Use React.js for creating components
4. Use Laravel to create Templates (blades) to put the reusable components on for multiple pages (different type of blade, with imports for template blades)
5. Have full CRUD functionality for at least one aspect of the site (does not need to be complicated)

- For example, in gmail:
- Create a new email in drafts (CREATE)
- Read an email by clicking on it (READ)
- Change the state from unread to read (UPDATE)
- Delete an email (DELETE)

6. Use a random text generator [API](http://www.randomtext.me/) _or_ [NPM package](https://www.npmjs.com/package/casual) to create random tweets/emails/usernames/trello cards etc...
7. Be able to port this app onto your portfolio website either by adding a link or putting the files into your Laravel portfolio project

#### Additional Requirements

- Website must be responsive
- Style your app as you wish
- Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Repo](https://github.com/bootcamp-students/Resources).
- Your repo should be public so that others can see your code and comment on it.
  - _**Remember to push to GitHub!**_
  - Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

- Connect your app to a server to have multiple people be able to log in and use it at the same time (gmail clone users can email each other, twitter clone users can @ and follow each other, etc)

#### If you finish early...

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
3. Add links and resources from this week to the [Class Resources Repo](https://github.com/bootcamp-students/Resources) by forking the repo and then initiating a pull request with your additions to the .md file.

### Additional Resources

- Ask questions :-)
- [Class Resources Repo](https://github.com/bootcamp-students/Resources)
- Learn more about [Good GitHub Practices](https://guides.github.com)
- [Atomic Design Principles - book](http://atomicdesign.bradfrost.com/)
- [How to Deconstruct a Website (2010)](https://www.smashingmagazine.com/2010/05/case-study-deconstructing-popular-websites-opinion-column/)
- [How to Deconstruct a Website (2017)](https://github.com/dsinecos/notes/wiki/How-to-deconstruct-a-website's-front-end-for-learning%3F)

For more information about clone apps, see these articles:

- [What is an app clone?](https://www.quora.com/What-is-an-app-Clone)
- [How much does Uber cost?](https://thinkmobiles.com/blog/how-much-cost-make-app-like-uber/)
- [When You Can’t Innovate, Copy](https://hbr.org/2012/05/when-you-cant-innovate-copy)
- [The Copycats Of Silicon Valley](https://www.inc.com/yazin-akkawi/why-are-silicon-valley-companies-copying-each-other.html)
- [Self Retweeting Tweet](https://www.youtube.com/watch?v=zv0kZKC6GAM)
