# elCurator - the beginner guide.

Just like software, this document will rot unless we take care of it. We encourage everyone to help us on that - just mail me at [trupin@octo.com]().

### Why this document ?

ElCurator is a startup project, incubated at and affiliated to OCTO Technology, and regularly raising funds to develop its structure. Some people are staying on board, some others are quitting, leaving a legacy behind them. Nevertheless, new recruits are constantly willing to arrive in a near future. This document is here to provide you the informations and best advices to begin getting into the project. Obviously, a project like elCurator doesn't only need developpers, that's why, even if some parts of this document are a bit technical, we try to make it as understandable as possible for everybody.

## The context - Inner-entrepreneurship
- The story of a startup living inside a bigger company
- Our legacy, OCTO influences
- OCTO users are special

## The Product

### The concept

### Who is the target ?
- Our clients B2B, B2C
- The pricing

### The application features (screenshots if possible!?)
- the web site (service)
- the mobile applications (iOS, Android)
- the public API

### The fund raisings
- investors, ...
- OCTO Technology

## Methodolgies

### Lean startup
- What is it? Canvas
- Why elCurator is a good application of the lean startup?
- Continuous deployment
- Be careful with lean startup!? This is a methodology for product development, not for enterprise development! The startup still need a vision for success that lean won't give you!

### The team 
- Technical
- Communication
- Sales

#### Internal communication
- Meetings -> Retrospectives, Stand-up, Team building...
- Documents direct feedback -> slides, blog posts, contracts...
- BBL -> feedback rate at the end
- Mailing lists, collective curation tools (elCurator), chat (Slack)
--> Internal communication is transversal so everybody feel involved and usefull to the project.

### The automated tests
- TDD, what is it?
- Why do we write some?
- The limitations (interface tests, controller tests on mobile, web client js tests, etc...)

### The continuous integration
- Explain the principle
- Why is it particularly adapted to lean startup methodology?

### The process; from an hypothese to a production ready feature (diagram!?)
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

- Then write about hosting strategy (Heroku)

#### Problematics
- Performance -> product related
- Uptime -> product related
- Security (data storing, confidentiality - CNIL, etc...) -> client/marketing related
- Continuous deployment -> lean startup related
- Metrics -> lean startup related

### Mobile applications

#### Architecture - Include a schema (layers?! MVC?!) with the following roles:
- Data source (Sqlite) + Data access layer (ActiveAndroid/Coredata)
- Services (Google+, elCurator API) + Service Gateways
- Business Components/Entities (Controllers/Models)

#### Problematics
- Offline/Online modes -> product related
- Data synchronization -> product related
- Non UI blocking processings -> mobile plateform related

## The developer role

### A good front-end developer take care of details
- Design matters (careful, mobile is not web!)
- Interactivity matters (especially on mobile): UI feedback, never lock the screen, animations... 
- The finality is the feature, not the technical aspect of it.
Your role is to make sure all these points are technically well implemented so the final user isn't desappointed when using your application.

### A good back-end developer should make the front-end developer life easier
- Well designed API (RESTful)

### Software craftmanship
- The beauty of code matters (if no one can read your code, consider it as dead)
- Write a best practices guide, or find an existent one, and apply it with no exception

### A good developer should share his opinion
- Blog posts
- Meetups
- Forums (StackOverflow)
- Github (open sourcing)
--> Being involved in a net community is very important to keep your technical skills up to date

## Conclusion
