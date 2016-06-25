- Why Ember - http://ember.vicramon.com/introduction
- Basic Building Blocks of Ember from [Ember.js Guide](http://guides.emberjs.com/) (skip advanced things)
  - Router, Routes, Controller, Views, Components, Templates.
- Handlebars
  - Download the library from http://handlebarsjs.com/ and try the examples while going through website.
  - Alternatively, setup handlebars on [jsbin.com](jsbin.com) and try the examples there.

- Read on Ember Object http://ember.vicramon.com/the-ember-object
- Blog on creating basic application using only Ember http://andycrum.com/2014/05/17/an-introduction-to-ember-js/

###Task: Create Basic Blog app on emberjs.jsbin.com & locally
  - Design UI on Paper
  - Refer https://github.com/balinterdi/rock-and-roll for basic folder structure (only client part, we will use Fixture instead data of API)
  - Data Models to be created
    - post -> id, title, content, comments, rating
    - author -> id, name
    - comment -> id, text
  
  - Routes
    - posts, posts/:id,  posts/edit, authors, authors/:id, authors/edit
  
  - Features
    - Home page with list of blog posts. Each list item has title, link to full post, link to edit post, author name & comments count
    - Post details page contains Title, content, rating and link to author, edit post button
    - Post Edit page contains Title Edit box, content edit box, Rating Change, Author dropdown
    - Authors List with links to author page, post count.
    - Author page cotains author name, list of his blogs, edit button
    - Author Edit page contains edit box for changing author name, this page cotains 
  - Host on Github pages.    
