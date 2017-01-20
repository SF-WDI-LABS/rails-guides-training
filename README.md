<!--
Creator: Team editing by Cory
Market: SF
-->

![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

# Training -  Getting Started with Rails Guides


### Setting up an app

Read and follow along with chapters 1-4 of the [Rails getting started guide](http://guides.rubyonrails.org/getting_started.html). This will probably take about **an hour**.


1. Create a GitHub repo for your getting started project so it's easy to reference later. Make commits for each step of the tutorial.  

1. As you go through the tutorial, note what each file and command is for. Try answering the following questions:
  * What are some things the terminal command `rails new blog` does?
  * What does the command `bundle` do?
  * What is `config/routes.rb` for?
  * What is `app/views/layouts/application.html.erb` doing for the project? 
  * What is the `Gemfile` for?


### Dealing with Data

In the  [Rails getting started guide](http://guides.rubyonrails.org/getting_started.html), work through chapter 5 up to and including section 5.9. You will have an app that lets you create and read articles -- you can continue if you'd like to and enable update and delete. You should end up with app that lets you create and read articles.  **This is a *long* chapter - set aside about 2 hours**. As you're working through chapter 5:

1. In your own words, answer the following questions about the **Model** part of Rails MVC. Reference the [ActiveRecord Rails Guide](http://guides.rubyonrails.org/active_record_basics.html) if you're not sure.
    * What is a "resource"?
    * What does it mean that ActiveRecord is an ORM framework?
    * What is a migration? How is it related to the app's database schema (`db/schema.rb`)?
    * What are some methods we can use to CRUD resources for a model, from inside a controller file?  It may help to look at controller `app/controllers/articles_controller.rb`, and section 5 of the [ActiveRecord Rails Guide](http://guides.rubyonrails.org/active_record_basics.html).

1. In your own words, answer the following questions about the **View** part of Rails MVC. Reference the [ActionView Overview Rails Guide](http://guides.rubyonrails.org/action_view_overview.html) if you're not sure.
    * In Rails RESTFUL routes, the `index`, `show`, `new`, and `edit` routes render HTML files. What should a user see on each of these pages?
    * What is the difference between a "layout" template and a "partial" template? Give an example of when you've used each.
    * Examine the HTML created by a `form_for` helper in your code. Why should we use `form_for` and helpers like `f.text_area` or `f.email_field` instead of writing Rails forms by hand?
    * How do we make data from the controller available in the view?
