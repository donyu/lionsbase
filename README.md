Lionsbase
=========

A website that helps student entrepreneurs get their startup ideas known by VCs and potential investors, as well as enable outside organizations and interested parties to learn more about the rising startup community at Columbia University. Think Crunchbase for college startups.

## Functional Spec

### User Roles

Lionsbase will support three types of users - student contributors, outside users, reward supporters

* student contributors - can sign up and list their startup for VCs, investors, and other students to see. Students will receive perks based on their startup statistics (user traction, # of likes/followers, etc.)
* outside users - anyone can go on the site and search through all participating startups posted by columbia students and alumni
* reward supporters - will reach out to local VCs, investors, startups, professors in the NYC tech community to sponsor perks (kind of like klout)

### Features

* A simple UI to search and learn about Columbia founded startups
* A headliners page about columbia entreprenuerial events and Columbia startup news
* Students have access to perks for putting their website on (should help them get their startup to the next level)

## Technology Stack

### Frontend

* Bootstrap - for its features, grid system, and responsive design elements
* SASS - so I can make the website pretty w/ less work than CSS
* HAML - because it's just less text I need to write for rails templating
* Coffeescript - because it beats straight javascript
* Formtastic - since I predict there will be a lot of forms in this app
* CarrierWave - so entrepreneurs can upload any relevant startup files
* Backbone.js - MV everywhere, but actually will help w/ front-end
* Mustache - for those templates that backbone views will use

### Backend

* Ruby on Rails - because it's easiest for me
* RSpec - for testing rails
* Postgres - well it's better than MySQL
* Heroku - is there even a better way to deploy rails apps?

### APIs

* Mandrill - offers highest # of free email sends
* Twitter/Facebook - kind of have to nowadays
* Google Analytics - data driven development is a popular buzz word these days
