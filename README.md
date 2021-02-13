# README

![Ruby](https://img.shields.io/badge/Ruby-v2.7-red)
![RubyOnRails](https://img.shields.io/badge/RoR-6.0.3-red)
![GitHub repo size](https://img.shields.io/github/repo-size/AgnesePortera/alpha-blog)
![GitHub](https://img.shields.io/github/license/AgnesePortera/alpha-blog?style=plastic)
![GitHub](https://img.shields.io/github/last-commit/AgnesePortera/alpha-blog)


Educational Blog deployed with Ruby on Rails framework.

* Ruby version 2.7
* Ruby on Rails 6.0.3
* Database Sqlite3 (one-to-many and many-to-many associations)
* REpresentational State Transfer (REST)
* Front-end styling with Bootstrap 4.4.1
* Deployment suggested with *Heroku* platform

## Preview
The blog includes the following features:
* Signup as a new user
* Log in/Log out with session activities
* Create, edit or destroy articles related to the user (only admin has complete rights)
* Associate an article to a category
* View all articles, categories and users with all related elements

![preview gif](https://github.com/AgnesePortera/alpha-blog/tree/master/app/assets/images/preview-blog.gif)


### How to run the test suite
For executing all the tests included in the project, run the following from the command window:

`rails test` 

Instead if you want to execute a single test:

`rails test test\integration\signup_test.rb` 

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/AgnesePortera/alpha-blog/.
This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the
[code of conduct](https://github.com/AgnesePortera/alpha-blog/blob/master/CODE_OF_CONDUCT.md).

## Code of Conduct

Everyone interacting in the Notification Bot project's codebases, issue trackers, chat rooms and mailing lists is
expected to follow
the [code of conduct](https://github.com/AgnesePortera/alpha-blog/blob/master/CODE_OF_CONDUCT.md).

## License

This project is distributed under _MIT_ license.
