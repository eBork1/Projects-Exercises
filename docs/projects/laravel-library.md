# Laravel Library

### Description

Create a webpage that acts as a hub for librarians to know the status of books in their library, and update books and their information

For this project we will be using Composer to generate a Laravel project

Learn about how to properly [link a repo created on the command line with an existing repo you created on the GitHub website](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line)

### Table of contents

<!--ts-->

- [Project/Exercise Name](#Laravel-Library)
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

By default, the app should let a Librarian maintain a simulated library via a web interface that is connected to the Google Books API

#### Wireframe

[Library Wireframes](../wireframes/library) - you do not need to copy these exactly, its just an idea

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

1. Create repo on GitHub, for example: `my-app`
2. Locally, navigate to your `sites` folder in the terminal
3. Create necessary files for application and view in VS Code via Composer CLI
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

1. Use the [Google Books API](https://developers.google.com/books/docs/v1/getting_started) to generate book content for users to check in and out from the library
2. Store library card holders in your local MySQL database with the following database schema:

Users

- user id (string) - this will be the "library card"
- user name (string)
- any other info you would like to store that is NOT redundant

| user_id (string) | user_name (string) |
| ---------------- | ------------------ |
| 217bhjds8        | ianrios            |
| 3fioy7823        | justinhall         |
| 62hd7gd11        | nicksuch           |

Books

- book id (string) - linked to Google Book API Book ID so we do not actually store the book pdf in our repo
- user id of user that currently has this book checked out (foreign key)
- times the book has been checked out (integer)
- any other info you would like to store that is NOT redundant

| book_id (string) | user_id (foreign key) | number_of_times_checked_out (int) |
| ---------------- | --------------------- | --------------------------------- |
| iui4vdsua        | 217bhjds8             | 1                                 |
| 876b3ksyn        | 217bhjds8             | 10                                |
| 16fkc44c4        | 62hd7gd11             | 7                                 |
| qyjdi7sje        | 217bhjds8             | 4                                 |
| tzbckg83n        | 62hd7gd11             | 1                                 |
| 08hkudtbj        | 62hd7gd11             | 2                                 |
| 235jc7782        | 62hd7gd11             | 3                                 |
| 1uuid78h3        | null                  | 4                                 |

3. Full CRUD operations should be available for `Users`
4. Read access should be available for `Books` (it is not possible to perform Create, Update, or Delete functions on the Google Books API) via GET requests
5. Only save the books in the book table AFTER a user decides to check the book out. (no need to save all the books locally, that's what the API is for)
6. Use React.js for creating components to put on Laravel Blades.
7. Users do not need to be real people, this can be simulated by you by clicking a "new user" button in the admin interface as a Librarian. (think 'library simulator')
8. Show all user and book statistics that are saved in database (for example: There are 3 users registered with the library, user "bob" has 2 books checked out: "Algorithms", and "Design Patterns", user "phil" has 0 books checked out, and user "sally" has 1 book checked out: "The Pragmatic Programmer") you can format this data however you'd like, we suggest a table with multiple tabs
9. Be able to click any user or book and view the info as well as perform full CRUD where applicable.

#### Additional Requirements

- Website must be responsive
- Style your app as you wish
- Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Repo](https://github.com/bootcamp-students/Resources).
- Your repo should be public so that others can see your code and comment on it.
  - _**Remember to push to GitHub!**_
  - Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

- Create a search bar for querying books from the Google Books API
- Implement Laravel Auth using composer to create many "Librarians"
- Add a 'due by date' that keeps track of how long a book has been checked out
- Add a 'late fee' for books that have been checked out too long that can be modified by the librarian
- Add a way for a user to 'renew' their checked out book
- Add a way for users to put a book on hold if someone else has it currently checked out
- Add a history for the librarians to see a list of all people who checked out a particular book
- Add any other data to the scheme as long as it is NOT redundant

#### If you finish early...

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
3. Add links and resources from this week to the [Class Resources Repo](https://github.com/bootcamp-students/Resources) by forking the repo and then initiating a pull request with your additions to the .md file.

### Additional Resources

- Ask questions :-)
- [Class Resources Repo](https://github.com/bootcamp-students/Resources)
- Learn more about [Good GitHub Practices](https://guides.github.com)

For more information about CRUD, see these articles:

- [What is CRUD?](https://www.codecademy.com/articles/what-is-crud)
- [Why is CRUD so Important?](http://trendintech.com/2018/01/19/why-is-crud-so-important-in-computer-programming/)
