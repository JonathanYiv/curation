# Roadmap

This is a general outline of my plan for curation.

## Version 0.1.0: Login and Heroku

* Switch to PostgreSQL
* Use [Yarn](https://yarnpkg.com/en/) to install [Bootstrap](http://getbootstrap.com)
* Create Static Pages
* Integrate [Devise](https://github.com/plataformatec/devise) for Authentication
* Setup an Email System
* Integrate [OmniAuth](https://github.com/omniauth/omniauth/) Login for [Github](https://github.com/intridea/omniauth-github)
* Add [Webpacker](https://github.com/rails/webpacker) as a Parallel Pipeline
* Deploy to [Heroku](https://www.heroku.com)
* Add Authentication Integration Tests

## Version 0.1.1: Gem Power

* Add the [Better Errors](https://github.com/charliesome/better_errors) gem for improved Rails error page
* Add [Rubocop](https://github.com/bbatsov/rubocop) for Clean Code
* Add [Brakeman](https://github.com/presidentbeef/brakeman) to check for Security Vulnerabilities
* Add [Letter Opener](https://github.com/ryanb/letter_opener) for Email Delivery in the Development Environment
* Add [Simple Form](https://github.com/plataformatec/simple_form) for Form Creation
* Add [FactoryBot](https://github.com/thoughtbot/factory_bot_rails) for Factories in Testing

## Version 0.2.0: Functionality

* Users can create many new 'Curriculum'
* Curriculums can have many 'Courses'
* 'Courses' have many 'Lessons'
* 'Lessons' have many 'Concepts'
* 'Concepts' can be dependent on many other 'Concepts'
* Any of the above can have many 'Tags'
* 'Concepts' can have 'Complexity Ratings'
* Multiple Users can contribute to a Curriculum
* Different Users can be assigned different permission levels
* Curriculums can be private or public
* Users can search for existing curriculums

## Version 0.3.0: Interface Polish

* Create a Responsive Design
* Curriculum pages allow Courses/Lessons/Concepts to be expandable
* Curriculum pages allow management of Courses/Lessons/Concepts/Tags
* Course pages allow Lessons/Concepts to be expandable
* Course pages allow management of Lessons/Concepts/Tags
* Lesson pages allow Concepts/Tags to be expandable
* Lesson pages allow management of Concepts/Tags
* Tag pages allow you to see all items tagged
* Concept pages allow you to show all associated lessons/courses
* Courses/Lessons/Concepts all have a Concept Dependency page
* All pages have a breadcrumb trail
* Use AJAX to render modifications to a curriculum
* Create a click and drag interface

## Version 0.4.0: History

* Use [Paper Trail](https://github.com/airblade/paper_trail) to allow version history for Curriculums, Courses, Lessons, and Concepts (including their associated tags)

## Version 0.5.0: Regression

* 100% Test Coverage
* Integration with Travis CI

## Version 0.6.0: Back-Up

* Use [backup](https://github.com/backup/backup) to backup user data

## Version 0.7.0: API

* Design an API for Curation
* Document the API at api.curation.com
* Allows users to get formatted data regarding their curriculum

## Version 0.8.0: Omniauth Expansion

* Add Omniauth Login with [Google](https://github.com/zquestz/omniauth-google-oauth2), [Facebook](https://github.com/mkdynamic/omniauth-facebook), [LinkedIn](https://github.com/decioferreira/omniauth-linkedin-oauth2) and [Twitter](https://github.com/arunagw/omniauth-twitter)
* Allow Single-Sign On

## Version 0.9.0: Discourse

* Integrate a Discourse Forum for discussion of Curation

## Version 1.0.0: Production-Ready

* Pending...

## To Do

* Look into [Kaminari](https://github.com/kaminari/kaminari) for Pagination
* Look into [CanCanCan](https://github.com/CanCanCommunity/cancancan/) for Authorization
* Look into [Ransack](https://github.com/activerecord-hackery/ransack) for Search Forms
* Look into [Searchkick](https://github.com/ankane/searchkick) for Search
* Look into [Chartkick](https://github.com/ankane/chartkick) for Charts
* Look into [Jbuilder](https://github.com/rails/jbuilder) for API JSon formatting
* Look into [Rails Best Practices](https://github.com/flyerhzm/rails_best_practices) and [RubyCritic](https://github.com/whitesmith/rubycritic) for Code Quality Metrics
