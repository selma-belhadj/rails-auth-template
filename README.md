# Basic Rails App Template
> This template is a basic Rails application that includes some popular gems and a basic layout. It is intended to be used as a starting point for new Rails projects.

## [Live Demo](https://template.onrender.com/)

## Built With

- Ruby (version 3.1.2)
- Ruby on Rails (version 7.0.4.2)
- PostgreSQL (version 14.4)

## Usage

To use this template, you can either create a new Rails application using the template or use the template to create a new branch in an existing Rails application.

### Using the template to create a new Rails application

To create a new Rails application using this template, run the following command:
`rails new myapp -m https://github.com/selma-belhadj/rails-template-app.git`
Replace `myapp` with the name of your new application.

### Using the template to create a new branch in an existing Rails application

To use this template to create a new branch in an existing Rails application, you can use the `git` command line tool.
- `git remote add template https://github.com/selma-belhadj/rails-template-app.git`
- `git fetch template`
- `git checkout -b mybranch template/template`
Replace `mybranch` with the name of the new branch you want to create.

## Getting Started
- Install packages
  `bundle install`
- Setup database
  `rails db:setup`
- Run tests
  `rspec`
- Tun the server
  `rails s`
<!-- - Create database
  `rails db:create`
- Run migration
  `rails db:migrate` -->

## Features
- RSpec for testing
- Bootstrap for layout and styling
<!-- - Authentication using Devise
- Authorization using Pundit
- Forms using Simple Form -->
## Authors

👤 **Selma Belhadj**

- GitHub: [@selma-belhadj](https://github.com/selma-belhadj)
- Twitter: [@selma_bel_hadj](https://twitter.com/selma_bel_hadj)
- LinkedIn: [@selma-belhadj](https://www.linkedin.com/in/selma-belhadj/)

## Customization

You can customize the template to suit your needs by modifying the `config/application.rb`, `config/environments`, `config/routes.rb`, and `app/views` files. 

You can also add or remove gems as needed. Be sure to run `bundle install` after making changes to the Gemfile.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/selma-belhadj/rails-template-app/issues).

If you would like to contribute to this template, please fork the repository and submit a pull request.


## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](./MIT.md) licensed.
