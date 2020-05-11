# Christian-Blog
## Author

[EssyMwangi](https://github.com/EssyMwangi)

# Description
This  is a flask application that allows writers to post blogs, edit and delite blogs. It also allows users who have signed up to comment on the blogs that has been posted by a writer. It also allows a person to subscribed to recieve email everytime a new blog is posted by a writer.

## Live Link
[View Site](https://christianblogbyess.herokuapp.com/)

## Screenshots

<img src="https://user-images.githubusercontent.com/44394821/81558240-0666cf80-9396-11ea-907b-86cafbe94cf4.png" width="900px" height="440px">
<img src="https://user-images.githubusercontent.com/44394821/81558255-09fa5680-9396-11ea-9355-24dd7f17d15b.png" width="900px" height="440px">
<img src="https://user-images.githubusercontent.com/44394821/81558235-036bdf00-9396-11ea-9483-f78b25985cc7.png" width="900px" height="440px">
<img src="https://user-images.githubusercontent.com/44394821/81558245-08309300-9396-11ea-9524-63d11270c161.png" height="440px">

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

## Development Installation
To get the code..

1. Cloning the repository:
  ```bash
  https://github.com/EssyMwangi/christian-blog
  ```
2. Move to the folder and install requirements
  ```bash
  cd blog
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python manage.py server
  ```
5. Testing the application
  ```bash
  python manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.


## Technology used

* [Python3.7](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

If you have any question or contributions, please email me at [sonnieessy@gmail.com]

## License
* _MIT License:_[LICENSE MIT](./LICENSE)
* Copyright (c) 2019 **Essy Mwangi**
