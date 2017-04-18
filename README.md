# RPS CRUD

## Standard Workflow

 1. Fork to your own account.
 1. Clone to your computer.
 1. In the GitHub Desktop app, [create a branch for your work](https://help.github.com/desktop/guides/contributing/creating-a-branch-for-your-work/#creating-a-branch).
 1. Open the entire folder you downloaded in Atom.
 1. Make your first change to the code. (You could modify this `README.md` file by adding your username next to the project in the heading, for example.)
 1. In the GitHub Desktop app, create a commit. You *must* type a "summary"; "description" is optional.
 1. Click Publish. Verify that your branch is now visible on your fork at GitHub.com in the "Branch" dropdown.
 1. **Commit and Sync often as you work.**
 1. Make new branches freely to experiment. You can always switch back to an older branch and start over. **When in doubt, create a branch**, _especially_ before starting on a new task.
 1. This project does **NOT** have `rails grade` functionality.
 1. If you have a question about your code, a great way to get feedback is to open a [Pull Request](https://help.github.com/articles/creating-a-pull-request/). After creating it, if you include the URL of your Pull Request when you post your question, reviewers will be able to easily see the changes you've made and leave comments on each line of your code with suggestions.

## Project Specific Setup

1. `cd` into the folder you downloaded.
1. `bundle install` (or `bundle` for short)
<!-- 1. `rails server` (or `rails s` for short) -->


## Project Details
1.  In this project we will extend the rps_rcav project by creating a database table (or what is referred to as a *model* in Rails) to save each round of play.
1.  There is an accompanying **video** for this project.  
1.  First, we create a model with the generate command.  Open up a terminal and cd into your rps_crud folder and issue the following command at your terminal prompt:
````
rails generate model round computer_move:string player_move:string outcome:string
````
1.  Now to create the table issue the following command at your terminal prompt:
````
rails db:migrate
````
1.  You now have a model (a database table) named Round.
1.  Follow the accompanying **video** and our [CRUD With Ruby Guide](https://guides.firstdraft.com/crud-with-ruby.html) to complete the project.
