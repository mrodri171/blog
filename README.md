# README

Blog Assignments #1 and #2

This is a Ruby on Rails application with the following two scaffolds:
Post
Comment

The Post scaffold has two attributes:
title - string and 
body - text

The Comment scaffold has two attributes:
post - references and
body - text

Post "has many" Comments

Destroy dependency added to the has many comments relationship in the Post model.

Created a nested resource for comments within posts in the routes.rb file

Validates presence of title and body for Posts and Comments.

Versions:
Ruby 2.3.1
Rails 5.0.0.1
