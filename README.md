## e_nstruments Music Shop Web App - Ruby on Rails & React

<a name="readme-top"></a>
<div align="center">
    <img src="/logo_jcm_md.png" alt="main-logo" width="500"  height="auto" />
  <br/>
  <h3><b>e_nstruments Music Shop Web App - Ruby on Rails & React</b></h3>
</div>
📗 Table of Contents <a name="table_of-contents"></a>

- [📗 Table of Contents](#table-of-contents)
- [📖 About project ](#about-project)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
    - [Run tests](#run-tests)
    - [Deployment](#deployment)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [❓ FAQ ](#-faq-)
  - [📝 License ](#-license-)


## 📖 About the project - e_nstruments Music Shop Web App <a name="about-project"></a>

This is a Music Shop Web App called e_nstruments, developed using Ruby on Rails (RoR) as the backend and React as the frontend. The web app includes a home page to display all the products for sale, a details page with all the instrument's information, a form to sell a new instrument, a page for displaying the cart contents, and it also allows the user to delete from the cart some or all the products he wants. It uses a PostgreSQL database to perform all database operations and includes some Rails gems, like Devise for user authentication, and CanCanCan for authorizations. Finally, the project includes the RSpec gem for unit testing.


## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

  <ul>
    <li><a href="https://ruby-doc.org/">Ruby v 3.2.2</a></li>
    <li><a href="https://rubyonrails.org/">Rails v 7.1.3.2</a></li>
    <li><a href="https://www.postgresql.org/">PostgreSQL v 16.1.1</a></li>
  </ul>

### Key Features <a name="key-features"></a>
- **A backend repo set up with Ruby on Rails, linters, and some gems like Devise (user authentication), CanCanCan (authorizations), and pg for connecting with a PostgreSQL database.**
- **A frontend repo set up with Vite and React. It includes the Tailwind CSS framework.**

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.


### Prerequisites

In order to run this project you need:

[Install Ruby](https://www.ruby-lang.org/en/documentation/installation/)

[Set Up Rails](https://www.ruby-lang.org/en/documentation/installation/)

Prerequisites: Ruby, Ruby Development Kit (for Windows), Ruby Gems packaging system, and PostgreSQL database server. Run the following commands...
```sh
$ gem install rails
```


### Setup

```sh
  cd my-folder
  git clone https://github.com/jcmunav63/e_nstruments_rails_react.git
```
- Remember that you will need to set up the connection to the PostgreSQL database first (username and password), and then you will have to create the databases (using rails db:create), before starting the development server.


### Install

This project requires the following dependencies: the Ruby interpreter, the Gem package manager, the Ruby on Rails web framework, a PostgreSQL database server, thr RSpec gem for unit testing, and the Devise gem for user authentication. Additionally, the project uses two linters checkers: RuboCop (Ruby) and Stylelint (CSS styles).

```sh
bundle install
```
- Note: The Devise gem needs to be installed, according to your needs (one option is to install the Views templates from the Devise gem and adapt their styles, and the other option is to create the Views from scratch and use them instead of the installed templates).

### Usage

To run the project, navigate to the project directory and execute the following command:

Start the Ruby on Rails web server (Puma server) typing the following command...
```sh
  rails s , or the complete command,
  rails server
```

### Run tests

* Install the Rubocop and Stylelint linters.

Install the Rubocop linters checker using the following steps...
- First add the following code to the Gem file:
```sh
gem 'rubocop', '>= 1.0', '< 2.0'
```
- Second run the command to install dependicies in your project:
```sh
bundle install
```
- Remember to copy the .rubocop.yml file to your root directory.

gem 'rubocop', '>= 1.0', '< 2.0'

Install Stylelint linters checker using the following command...
```sh
npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
```
- Remember to copy the .stylelintrc.json file to the root directory.

- Copy the linters.yml file inside of path .github/workflows


To run LINTERS, run the following command:

Run the following command for Ruby code...
```sh
rubocop
```

Run the following command for CSS code...
```sh
npx stylelint "**/*.{css,scss}"
```

* Implement unit tests using RSpec.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Deployment

This application is deployed on Render. Visit the following link...
pending

You can visit my presentation video at,,,
[Demo video...](https://youtu.be/pending)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Authors <a name="authors"></a>

👤 **Developer's name here**

- GitHub: [@jcmunav63](https://github.com/jcmunav63)
- Twitter: [@jcmunav63](https://twitter.com/jcmunav63)
- LinkedIn: [@juan-carlos-muñoz](https://www.linkedin.com/in/juan-carlos-mu%C3%B1oz-fullstackdev/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 🔭 Future Features <a name="future-features"></a>

- **Credit card or PayPal Payment feature.**
- **Social media options (share, like, follow).**

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## ⭐️ Show your support <a name="support"></a>

If you like this project please give me a star on Github. Thanks in advance.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to acknowledge Andy Leverenz for the original idea of this project. You can review his blog at: [Let's build an eCommerce Music Shop](https://webcrunch.com/posts/ruby-on-rails-ecommerce-music-shop)

I would also like to thank all my colleagues, who inspire me to do my best everyday.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ❓ FAQ <a name="faq"></a>


**Did you create this project from scratch?**

  - Yes, it is an eCommerce e_nstruments Music Shop web app built with Ruby on Rails project, a PostgreSQL database connection, and React components to create the frontend.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
