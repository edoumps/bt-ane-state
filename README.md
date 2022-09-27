# README

# Bitam Ane State is a Blog about the city of Bitam in Gabon

The blog focus on given news about the city on differents subjects categories

- Latest News (Headlines)
- Politics
- Social
- Culture
- Sport
- Entertainment
- Services

Features

- Users can comment posts
- Users with account receive the latest news,jobs opportunities, etc..
- Only the admin can post content
- Only the admin can delete and filter bad comments
- User can search for blog post by category, date,

Blog Post Schema

Post (table)

- Title(text)
- comments(text)
- author(text)
- user(string)

A - "HELLO RAILS" (minimum route, controller, action)

1 - Routes setup (test)

      get "/articles", to:
      "articles#index"

2 -  Create ArticlesController
      rails generate controller Articles index --skip-routes
      * 'Articles index' tell Rails to generate a 'index.html.erb' render file at the same time

3 -  Insert content inside the render file 'index.html.erb' to test in the browser
      <h1> This is a ROR test!</h1>
      - start server & visit http://localhost:3000/articles

4 -  Initialize a git repo and commit all files
      $git add . or -A
      $git commit -am "Initial commit"
    
5 -  Create git repo on github & remote 
      $




This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...
