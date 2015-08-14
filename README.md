# elCurator - the beginner guide.

Just like software, this document will rot unless we take care of it. We encourage everyone to help us on that - just mail me at [trupin@octo.com]().

### Why this document ?

ElCurator is a startup project, incubated at and affiliated to OCTO Technology, and regularly raising funds to develop its structure. Some people are staying on board, some other are quitting, leaving a legacy behind them. Nevertheless, new recruits are constantly willing to arrive in a near future. This document is here to provide you the minimal informations and best advices to begin getting into the project. Obviously, a project like elCurator doesn't only need developpers, that's why, even if some parts of this document are a bit technical, we try to make it as understandable as possible for everybody.

## The Product

### The concept

### Who is the target ?
- Our clients B2B, B2C
- The pricing

### The application features
- the web site (service)
- the mobile applications (iOS, Android)
- the public API

## The context - Inner-entrepreneurship
- The story of a startup living inside a bigger company
- Our legacy, OCTO influences
- OCTO users are special

## Methodolgies

### Lean startup
- What is it?
- Why elCurator is a good application of the lean startup?
- MVP; good or bad thing? What did we learn?

### The team 
- Technical
- Communication
- Sales

### The process; from an hypothese to a production ready feature
- The board (Trello)
- The sources repository (Github/Gitlab)
- The continuous integration server (TeamCity)

#### Web/Api
- The staging server
- The Validation (Chrome, Firefox, etc...)
- The production server

#### Mobile applications
- The test release on a private application store (Appaloosa)
- The Validation (iOS, Android)
- The release (Apple store/Play store)

### The automated tests
- TDD, what is it?
- Why do we write some?
- The limitations (interface tests, controller tests on mobile, web client js tests, etc...)

## The technical stack
- Resources:
[http://adrianmejia.com/blog/2011/08/11/ruby-on-rails-architectural-design/](),

### Server 

#### Architecture - Include a schema (layers?!) with the following roles:
- Data source (Postgres) + Data access layer (Rails:Active record)
- Services (Readability, etc...) + Service Gateways (Rails http client)
- Business Components/Entities (Rails:Controllers/Rails:ActiveRecord:Models)
- Service Interface (API:Json, Html, RSS)
- Background tasks (rake tasks)

#### Hosting
- Heroku

#### Problematic
- Request/Second rate
- Security (about the data, etc...)
- ... Find more

### Clients 

### Mobile applications

#### Problematic
- Offline/Online
- Data synchronization
- Non blocking tasks

#### Architecture - Include a schema (layers?! MVC?!) with the following roles:
- Data source (Sqlite) + Data access layer (ActiveAndroid/Coredata)
- Services (Google+, elCurator API) + Service Gateways
- Business Components/Entities (Controllers/Models)
