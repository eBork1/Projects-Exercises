# Blog

### Description

Create a web site that helps you document your journey through the bootcamp by answering questions and creating posts

For this project we will be adding new questions every week to the [blog-questions.md](../blog-questions.md) file.

The purpose of this project is to not only let you have a way to look back on all your progress when the bootcamp finishes, but also see how different everyone decides to create their websites and work together to learn new techniques.

### Table of contents

<!--ts-->

- [Project/Exercise Name](#Blog)
- [Description](#Description)
- [Table of Contents](#table-of-contents)
- [MVP (Minimum Viable Product)](#MVP)
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

By default, your blog should be able to be viewed online by others.

#### Tech Stack

1. HTML
2. CSS

### Process

##### Setup:

1. Create repo, for example: `my-blog`
2. Locally, navigate to your `sites` folder in the terminal
3. `git clone` + `your-repo-name` into your Sites folder
4. Create necessary files for application and view in VS Code
   <!-- - Run shell script to expedite process unless you are using a framework -->
   <!-- - _If you are using a framework, disregard the "Application File Structure" section_ -->
5. Import and route necessary css/js files (E.g. Bootstrap)
6. Save all and create your first commit to `master`

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

##### Deploy:

1. Create a Pull Request from `dev` into `master`
2. Confirm code is up to date and works correctly
3. Post links to your GitHub repo to the Projects Slack channel

---

### Requirements

To complete the assignment, you must complete the following:

1. Continuous updates to your blog throughout the bootcamp
2. Help others out with making their blog look good
3. Integrate with your portfolio
4. Create a PR for the [everyones-blogs.md](../everyones-blogs.md) file, correcting *your* personal information if it is wrong.

#### Additional Requirements

- Website must be responsive
- Style your app as you wish
- Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Repo](https://github.com/bootcamp-students/Resources).
- Your repo should be public so that others can see your code and comment on it.
  - _**Remember to push to GitHub!**_
  - Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

- Use JS to dynamically render the blog
- Refactor your blog into React.JS
- Use MySQL to store your blog posts
- Refactor your blog into Laravel
- Host your blog on Google Cloud
- Maintain your blog after the bootcamp ends

#### If you finish early...

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
3. Add links and resources from this week to the [Class Resources Repo](https://github.com/bootcamp-students/Resources) by forking the repo and then initiating a pull request with your additions to the .md file.

### Additional Resources

- Ask questions :-)
- [Class Resources Repo](https://github.com/bootcamp-students/Resources)
- Learn more about [Good GitHub Practices](https://guides.github.com)

For more information about blogs, see these articles:

- [How To Stick With A Blog](https://www.freecodecamp.org/news/every-developer-should-have-a-blog-heres-why-and-how-to-stick-with-it-5fd55a247fbf/)
- [Best Blogs to Read on Web Development](https://usersnap.com/blog/12-best-web-development-blogs-reading-right-now/)
- [Blog Design Examples](https://bloggingpro.com/archives/2017/07/20/5-best-blog-design-examples-inspiration/)
- [Blog Template Ideas](https://colorlib.com/wp/blog-website-templates/)
