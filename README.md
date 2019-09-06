# Back-end developer exercise

&copy; 2019 Renderbit Technologies LLP.

## Prerequisites

You should be familiar with Node.js (8+), Express 4, Git and GitHub.

## Getting Started

This tutorial assumes you have a local Node.js development environment set up on your machine, with the following components at minimum:

1. Node.js 8 or better
2. Express 4
3. Choice of Database (MySQL/MongoDB/PostgreSQL/SQLite)
4. Choice of IDE/Editor

Fork this repository, and clone your fork locally. Your submission should include the URL of your Git repository. It should have public read permissions or be otherwise shared with us directly.

## Requirements

You have to design a blogging application.

Any user can sign up and create a blog of their own. When signing up, you have to record the user's full name, unique email address, password (8 characters minimum with 1 special character required) and choice of unique username.

The homepage of the blog can be viewed by anyone without login. The homepage shall show a list of all blog posts by all users, with most recent posts on top. The list of blog posts shall be paginated, with 8 posts per page. On clicking a post, a user can view the entire post content.

Every user shall have his/her blog home page at `<sitename>/<username>`. This page shall show a list of all posts by the particular user, with most recent posts on top. This list of blog posts shall also be paginated, with 8 posts per page. On clicking a post, a user can view the entire post content.

A blog post has the URL `<sitename>/<username>/<post_unique_slug_from_title>`. A blog post has a post title and post content. Anyone can view a blog post without login. However, you need to login to comment on a blog post. Any user can comment on any blog post. However, a user can only delete comments that he has made on other users' blog posts. The author of the blog post can delete any comment on the blog post made by any user. The comments are shown below the blog post content, with most recent comments on top. A form to add a new comment is shown above the comments thread.

Every user can access the admin  panel at `<sitename>/admin`. A user has to login to access the admin panel. The admin panel should show a list of all posts, with an option to edit and delete each post. The admin panel should also have an option to create a new post.

### UI

You are free to use any UI framework or library of your choice. We recommend [Bootstrap](https://getbootstrap.com) as a good place to get started.

Note that you are not required to build a mobile responsive website, although if you build one, we will be assigning extra credits for that.

You can use any front-end templating framework (Pug/Jade/Handlebars/Hogan/EJS) or plain vanilla HTML in your code. The default express configuration is set to use EJS. Similarly, you can use plain CSS or any preprocessor (SCSS/Less/Stylus) of your choice.

### Libraries & Frameworks

You are free to use any libraries, frameworks & tools which you think will be useful to build this application. We recommend going with [Angular](https://angular.io/) or [React](https://reactjs.org/). No credits are deducted for use of libraries. You can use either server-side or client-side routing for the application.

### Extra Credits

- Implement a social login feature which allows users to login and sign up via their Google+/Facebook/Twitter/Github accounts.
- Allow photos to be inserted into blog posts.
- Allow WYSIWYG editing of blog posts with rich formatting support.
- Implement a CAPTCHA for adding comments.
- Implement two-factor authentication for login using SMS for one-time passwords.
- Surprise us. :smiley:
