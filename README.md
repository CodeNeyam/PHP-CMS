# PHP-CMS

CMS is a web application that allows website owners to manage the content on their website, including blog posts, pages, and media files.

## Features

- Create and edit blog posts and pages
- Manage media files, including images
- Customize website design and layout
- Schedule posts for future publication
- Manage user roles and permissions

## Technologies Used

- PHP
- MySQL
- HTML
- CSS
- JavaScript

## Installation

1. Clone this repository.
2. Navigate to the repository directory in the terminal.
3. Run `composer install` to install dependencies.
4. Create a new MySQL database and import the `database.sql` file to create the necessary tables.
5. Rename the `config.example.php` file to `config.php` and update the database connection details.

## Usage

1. Start the local server using `php -S localhost:8000 -t public`.
2. Navigate to `http://localhost:8000` in a web browser to view the application.
3. Login using the default admin user credentials: `admin` for the username and `password` for the password.
4. Create a new blog post or page by clicking the `New Post` or `New Page` button in the dashboard.

## Contributing

Contributions to CMS are welcome! Please follow these steps to contribute:

1. Fork this repository.
2. Create a branch: `git checkout -b my-new-feature`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request.
