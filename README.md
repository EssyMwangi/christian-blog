# Christian-Blog
## Author

[EssyMwangi](https://github.com/EssyMwangi)

# Description
This  is a flask application that allows writers to post blogs, edit and delite blogs. It also allows users who have signed up to comment on the blogs that has been posted by a writer. It also allows a person to subscribed to recieve email everytime a new blog is posted by a writer.

## Live Link
[View Site](https://christianblogbyess.herokuapp.com/)

## Screenshots

<img src="" width="900px" height="440px">
<img src="" width="900px" height="440px">
<img src="" width="900px" height="440px">

## User Story

* As a user, I would like to view the blog posts on the site.
* As a user, I would like to comment on blog posts.
* As a user, I would like to view the most recent posts.
* As a user, I would like to an email alert when a new post is made by joining a subscription.
* As a user, I would like to see random quotes on the site.
* As a writer, I would like to sign in to the blog.
* As a writer, I would also like to create a blog from the application.
* As a writer, I would like to delete comments that I find insulting or degrading.
* As a writer, I would like to update or delete blogs I have created.

## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load the page | **On page load** | Get all blogs, Select between signup and login|
| Select SignUp| **Email**,**Username**,**Password** | Redirect to login|
| Select Login | **Username** and **password** | Redirect to page with blogs that have been posted by writes and be able to subscribe to the blog|
| Select comment button | **Comment** | Form that you input your comment|
| Click on submit |  | Redirect to all comments tamplate with your comment and other comments|
|Subscription | **Email Address**| Flash message "Succesfully subsbribed to Christian-Blog"|