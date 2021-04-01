# [University of Regina](http://uregina.ca) | [Data Science Laboratory](http://urdatascience.ca)
Directed by [Dr. Alireza Manashty](http://urdatascience.ca/members/alireza)

[![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](http://urdatascience.ca)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](mailto:a.r.manashty@gmail.com)
[![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/ur-datascience/)

Powered by [Jekyll](http://Jekyllrb.com/)

# What are you looking for?

- [How can make a new blog post?](#make-blog-post)
- [How can make a new member page?](#make-member-page)
- [How can setup and run code on my computer?](#setup-and-run-on-your-own-computer)
    - [Docker Compose](#docker-compose)
    - [Locally](#locally)


# Setup and Run on your own computer
There are two method to run and start developing.

## Docker Compose
Make sure you already installed `docker` and `docker-compose` on your computer
and then run the command line below:
```shell script
docker-compose up
```

## Locally

- Firstly, Clone the repo on your computer; if you use CLI, run the command bellow!
```shell script
git clone http://github.com/ur-datascience/ur-datascience.github.io
```

- Enter to the repo's directory!
```shell script
cd ur-datascience.github.io
```

- Now times to install requirements; if you already have any of them ignore that step!
    - Install Ruby
    ```shell script
    brew update
    brew install ruby
    
    # If you use bash
    echo 'export PATH=/usr/local/Cellar/ruby/2.4.1_1/bin:$PATH' >> ~/.bash_profile 
    
    # If you use ZSH:
    echo 'export PATH=/usr/local/Cellar/ruby/2.4.1_1/bin:$PATH' >> ~/.zprofile
    ```
    > This command use HomeBrew for other installation methods check [here](https://www.ruby-lang.org/en/documentation/installation/)                                                                                                                                               
    
    - Install Jekyll:
    ```shell script
    gem install bundler jekyll
    ```
- Install Gems requirements
```shell script
bundle install
```
    
- Run the code by command bellow; your site will run on your ==localhost== port `4000`
```shell script
bundle exec jekyll serve
```
> Open [http://localhost:4000](http://localhost:4000) on your browser

- Done :blush:


# Make blog post
To make a new post, follow the continuous steps.

- Create a new `.markdown` file in `_blog` directory
> Attention: The name of the file will be the URL of the post!
>
> URDataScience.ca/blog/name_of_the_file

- Copy content of the [post_sample.markdown]() and paste it on your file

- Fill the gaps, as the example's structure

- Push(Save) it :octocat:

> Your post will appear on the website as soon as you push it.


# Make member page
To make a new member page, follow the continuous steps.

- Create a new `.markdown` file in `_members` directory
> Attention: The name of the file will be the URL of the page!
>
> URDataScience.ca/members/name_of_the_file

- Copy content of the [member_sample.markdown]() and paste it on your file

- Fill the gaps, as the example's structure
> You can remove any part which is you don't need that

- Push(Save) it :octocat:

> Your page will appear on the website as soon as you push it.


# Contribute
TODO

# LICENSE
GNU GENERAL PUBLIC LICENSE

# Note

- Recommended to use Jetbrains' application to work on project(Feel free it's just a recommendation)