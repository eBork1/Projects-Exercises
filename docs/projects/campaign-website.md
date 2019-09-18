# Campaign Website

### Description

Create a website promoting your favorite _FICTIONAL_ character from a book, TV show, movie, or graphic novel, who is running for the elected position of Constable in your magistrate district of Fayette County. (There are 3 such districts.)

Briefly research the role of Constable, then design a political website for your chosen character. [Here's a link to get you started](https://en.wikipedia.org/wiki/Constables_in_the_United_States#Kentucky)

Your job is to make it easy for voters to see whether your candidate's beliefs align with their own.
To keep things light and fun, pick issues that pertain to the character in their fictional setting, not the real world. :-)

### Table of contents

<!--ts-->

- [Project/Exercise Name](#Campaign-Website)
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

By default, the app should show potential voters who the candidate is and have lots of different content; view the [Requirements](#Requirements) for more

Try your hardest to use bootstrap for any and all css changes - This project is to get familiar with using bootstrap, we already know how to use CSS on its own

#### Wireframe

![wireframe](../wireframes/campaign-website.jpg)

#### Tech Stack

1. HTML
2. CSS (via Bootstrap)
3. JS (via Bootstrap)

### Process

##### Setup:

1. [Create GitHub repo (either online or locally)](../git-instructions.md), for example: `my-app`
2. Create necessary files for application and view in VS Code
3. Import and route necessary css/js files (E.g. Bootstrap)
4. Save all and create your first commit to `master`, **then** switch to a dev branch

###### Application File Structure

Minimally:

```
web/
    index.html - main page
    css/ - folder to contain CSS files
        style.css - stylesheet
    img/ - folder to contain any images
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

1. Your website should introduce the public to your candidate, explain why they are running, and list three issues that are important to them.
2. Website must contain at least [3 distinct organisms](https://patternlab.io/) that you create using the following:
   1. Choose at least Four [Bootstrap Components](https://getbootstrap.com/docs/4.3/components/) to include from this list:
      - Badge
      - Button
      - Caption
      - Card
      - Collapse
      - Icon
      - List Group
      - Media Object
      - Popovers
      - Tooltip
   2. Use Five [Bootstrap Utilities](https://getbootstrap.com/docs/4.3/utilities) to suit the needs of your website
3. A few (more than 3) prominent pictures of your candidate
4. A table displaying important information for voters
5. A call to action - election day is November 5!
6. Scroll to an anchor tag
7. Punch out to a website
8. Use as much bootstrap and as little extend/augmented css as possible

#### Additional Requirements

- Website must be responsive and utilize as much Bootstrap and as little user generated css as possible - this project is to get familiar with the framework
- Style your app as you wish - [bootstrap generators are helpful if you dont like the standard colors](https://themestr.app/theme)
- Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Repo](https://github.com/bootcamp-students/Resources).
- Your repo should be public so that others can see your code and comment on it.
  - _**Remember to push to GitHub!**_
  - Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

- Create a MoSCoW list that could be used in an MVP
- Implement bootstrap components from this list that will enhance your site
  - Carousel
  - Jumbotron
  - Nav/Navbar
  - Progress
  - Spinner
  - Jumbotron
- Extend Bootstrap Core to enhance your website
- Augment Bootstrap classes to override the core
- Try using the built in Bootstrap JavaScript classes to manipulate transitions and moviement
- Download Bootstrap and compile via Sass instead of using CDN

#### If you finish early...

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
3. Add links and resources from this week to the [Class Resources Repo](https://github.com/bootcamp-students/Resources) by forking the repo and then initiating a pull request with your additions to the .md file.

### Additional Resources

- Ask questions :-)
- [Class Resources Repo](https://github.com/bootcamp-students/Resources)
- Learn more about [Good GitHub Practices](https://guides.github.com)
- [Learn JS](https://www.w3schools.com/js/)
- [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
- [Pull Requests](https://stackoverflow.com/questions/21657430/why-is-a-git-pull-request-not-called-a-push-request)

For more information about content creation, see these articles:

- [Content Creation Tips](https://blog.hubspot.com/marketing/content-creation)
- [Content Creation Process](https://www.postmm.com/web-design/content-marketing/content-creation-process/)

Bootstrap Theme Builders

- [themestr.app](https://themestr.app/theme)
- [bootstrap.build](https://bootstrap.build/)
