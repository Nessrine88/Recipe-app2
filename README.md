# <div align = "center">  Recipes App </div>

<a name="readme-top"></a>
<div align="center">

</div>

# 📗Table of Contents
- [📖 Recipes App ](#-recipes-app-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Database](#database)
    - [Usage](#usage)
    - [Run tests](#run-tests)
    - [Run linter](#run-linter)
    - [Deployment](#deployment)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

# 📖 Recipes App <a name="about-project"></a>

The Recipe app keeps track of all your recipes, ingredients. It will allow you to save ingredients, keep track of what you have, create recipes, and generate a shopping list based on what you have and what you are missing from a recipe. Also, since sharing recipes is an important part of cooking the app should allow you to make them public so anyone can access them.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

  <ul>
    <li><a href="https://rubyonrails.org/">Ruby on Rails 7.1.2</a></li>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>

### Key Features <a name="key-features"></a>

- Creation: Users can create new recipes, providing details such as name, preparation time, cooking time, and description.
- Ingredient Database: The app maintains a database of ingredients that users can reference when creating recipes..
- Automatic List Generation: The app generates a shopping list based on the ingredients required for selected recipes and what the user doesn't currently have in their inventory.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

[Install Ruby](https://www.ruby-lang.org/en/documentation/installation/)

### Setup

```sh
cd my-folder
git clone https://github.com/Alejandroq12/recipe-app.git
```

### Install

Install all necessary dependencies listed in the `Gemfile`.

```sh
bundle install
```

Install all necessary dependencies listed in the `package.json`.

```sh
npm install
```

### Database

Important: please, rename .env.example to .env and fill out all necessary fields otherwise you will not be able to connect to the database.

Before running the migrations and seeds, ensure that PostgreSQL is installed and running:

```sh
sudo service postgresql start
```

Create database:

```sh
rails db:create
```

Run migrations:

```sh
rails db:migrate
```

Add the seeds:

```sh
rails db:seed
```

### Usage

To run the project, navigate to the project directory and execute the following command:

```sh
rails server
```

### Run tests

To execute all test suites in the application, use the following command in your terminal:

```sh
rspec
```

If you wish to run only the controller request tests, you can specify the path to your request specs directory:

```sh
rspec spec/requests/ 
```

If you wish to run only the integration tests:
```sh
rspec spec/system
```

### Run linter

To run linter, run the following command:

```sh
rubocop

```
```sh
npx stylelint "**/*.{css,scss}"
```

### Deployment

You can deploy this project using:

- Render : [render](https://dashboard.render.com/login)
- Heroku : [heroku](https://www.heroku.com)
- Netlify : [netlify](https://www.netlify.com)
- Fly.io : [fly.io](https://fly.io)
- Amazon web service : [aws](https://aws.amazon.com/fr/)
<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Authors <a name="authors"></a>

👤 **Julio Quezada**

- GitHub: [Alejandroq12](https://github.com/Alejandroq12)
- Twitter: [@JulioAle54](https://twitter.com/JulioAle54)
- LinkedIn: [Julio Quezada](https://www.linkedin.com/in/quezadajulio/)

👤 **Nessrine Macherki**

- GitHub: [Nessrine Macherki](https://github.com/Nessrine88)
- LinkedIn: [Nessrine Macherki](https://www.linkedin.com/in/nessrine-macherki-86959196/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

- User Feedback: Users might have the option to leave reviews or comments on recipes.
- A rating system could be in place for recipes, helping users discover popular or highly-rated dishes.
- Web and Mobile: The app might be accessible through both web and mobile platforms for a seamless user experience.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project please give a star.
Thanks in advance.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank all of my colleagues who inspire to do my best everyday.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FAQ (optional) -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
