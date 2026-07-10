# MV* Patterns (MVC, MVVM, MVP)

## Lecture Summary
This Week I learned about the MV* architectural patterns, which are widely used in web and mobile app development. Unlike traditional design patterns such as Singleton, Observer, or Adapter, MV* patterns focus on the overall structure and organization of an application rather than solving a specific object-oriented programming problem. These patterns, very much like blueprints, help developers separate responsibilities within an application, making projects easier to maintain, test, and scale as they grow in complexity.

The MV* family consists primarily of three common architectures:
- Model View Controller (MVC)
- Model View ViewModel (MVVM)
- Model View Presenter (MVP)

Now the these three patterns aim to separate date, user interfaces, and application logic into their own separate components. This separation reduces code coupling and improves its maintainability.

## Understanding the Model
The Model is responsible for managing application data and business logic. This allows for the application to see if the source is true. The Model typically interacts with databases, APIs, or local storage. It is also responsible for storing application data, validating data, communicating with databases and external services, performing business calculations.

The Model should remain independent of the user interface. This allows developers to modify UI components without affecting how data is stored or managed.

For example, in a student management application, the Model would contain information such as student names, IDs, grades, and attendance records.

## Model View Controller (MVC)
MVC is one of the oldest and most popularly used software architecture out of the three. It divides an application into three core components:
#### Model
Contains data and business logic
#### View 
Displays the users information
#### Controller
Handles user input and acts as a mediator between the Model and View

### MVC How it Works
- The user interacts with the View.
- The Controller receives the user action.
- The Controller updates the Model.
- The Model changes its state.
- The View refreshes and displays updated data.

### Why Use MVC?
The MVC has a clear separation of concerns and simultaneously being easier on maintainance and debugging. It can also support multiple Views for the same Model and has a well-established architecture with extensive framework support.

## Model View ViewModel (MVVM)
MVVM is evolved from MVC to better support the modern user interface, particularly reactive and declarative UI frameworks. The only difference between this and MVC is that it has a ViewModel rather than a controller. ViewModel in MVVP acts as an abstraction of the View and prepares Model data for presentation.

### MVVM How it Works
- The View binds directly to the ViewModel.
- User interactions update the ViewModel.
- The ViewModel updates the Model.
- Changes in the Model are reflected back through the ViewModel.
- The View automatically updates through data binding.

### Why Use MVVM?
MVVM has a clear separation between UI and business logic with an improved testability. It has a reduced code in the View and works well with reactive programming techniques, these being a technique focused on creating relationships between pieces of data so that when one value changes, all related values update automatically without requiring extra code. MVVM has become the preferred architecture for modern mobile applications. I kinda found it a little interesting that both Apple and Google have shifted toward MVVM because declarative user interfaces work naturally with data-binding concepts.

## Model View Presenter (MVP)
MVP was created to cover some of the shortcomings of MVC by giving the Presenter more responsability. It is comprised of these components:
#### Model 
Handles data and business logic.
#### View
Displays the UI and forwards the events.
#### Presenter 
Processes user interactions and updates both the Model and the View.

## MVP How it Works
- User interacts with the View.
- The View notifies the Presenter.
- The Presenter updates the Model.
- The Presenter receives data from the Model.
- The Presenter updates the View.

Unlike MVVM, the View in MVP does not automatically bind to the data. The Presenter explicitly manages updates.

## Why Use MVP
MVP has a higher testability than the other two, has a clear separation of its responsibilities and it also has a better control over UI interactions. From my perspective, MVP seems like a good balance between MVC and MVVM, although it appears to require more manual work.

## Reflection
Overall, this week's lesson helped me understand why architecture is so important in software development. When projects are small, it can be tempting to put everything in one place, but as applications grow, that approach quickly becomes difficult to maintain. MV* patterns provide a way to organize code logically and make teamwork easier because developers can focus on specific parts of the application without affecting everything else.

My biggest takeaway from this week is that there is no single "best" architecture. Each pattern has strengths and weaknesses, and the choice depends on the project's needs and the framework being used. As I continue learning app development, understanding these patterns will help me build applications that are cleaner, easier to maintain, and more scalable.

# Assess External Community Contribution Guidelines
## Community Information
### Project: CircuitVerse
### Repository: https://github.com/CircuitVerse/CircuitVerse
Last week, I identified CircuitVerse as the open-source project I was most interested in contributing to. Before starting any work, I reviewed the project's README, CONTRIBUTING guide, and Code of Conduct to understand how contributors are expected to participate in the community.
## What I Learned
One thing I noticed right away is that CircuitVerse has fairly detailed documentation for new contributors. The project encourages contributors to review existing issues before starting work and to look for issues labeled "good first issue" if they are new to the project.
The contributing guide also explains that contributors should:

- Follow the project's Code of Conduct.
- Be respectful and professional when interacting with others.
- Avoid creating duplicate issues.
- Comment on an issue before beginning work so other contributors know it is being worked on.
- Follow the setup instructions provided by the project.
- Use GitHub Discussions or the CircuitVerse Slack community if they need help.
  
I also learned that issue labels are important because they help contributors understand the type and difficulty of work involved. Labels such as good first issue, bug, and help wanted make it easier to find tasks that match a contributor's experience level.
## Code of Conduct
CircuitVerse emphasizes creating a welcoming environment for everyone involved in the project. Contributors are expected to be respectful, supportive, and professional regardless of experience level or background. Harassment and discriminatory behavior are not tolerated.
## Contribution Process I Plan to Follow
Before contributing, I plan to:

1. Fork the CircuitVerse repository.
2. Clone my fork to my local machine.
3. Create a separate branch for my work.
4.Review the issue and related code.
5. Make and test any changes.
6. Commit my work regularly with descriptive commit messages.
7. Push changes to my fork on GitHub.
8. Document my progress in my Research & Reflection Journal.

## Issue I Am Interested In
The issue I selected is:
Fix notifications when the projects or users are deleted (#4904)
I chose this issue because it is marked as a good first issue and appears to be a manageable bug fix for someone making a first contribution. It would also give me an opportunity to learn how CircuitVerse handles notifications and user data within the application.

## Reflection
Reading through the contribution guidelines helped me realize that contributing to open-source projects involves much more than simply writing code. There are expectations around communication, documentation, teamwork, and respecting community standards. The documentation provided by CircuitVerse made the process feel much less intimidating and helped me understand the steps I should follow before starting work on an issue.

# Contribute to External Community
## Intended Contribution
### Community
#### CircuitVerse
#### Repository:
https://github.com/CircuitVerse/CircuitVerse
### Issue
Fix notifications when projects or users are deleted
### Issue Link:
https://github.com/CircuitVerse/CircuitVerse/issues/4904
### Why I Selected This Issue
I selected this issue because it is marked as a Good First Issue and focuses on fixing a bug rather than implementing a large new feature. This makes it a suitable first contribution while allowing me to learn how CircuitVerse handles notifications and database relationships.
### Community Documentation
I reviewed:

- README.md
- CONTRIBUTING.md
- Code of Conduct

The project encourages contributors to:

- Work on good-first-issues
- Claim issues before working on them
- Use branches rather than modifying main
- Follow the Code of Conduct
- Submit tested code changes

### Current Progress

- Forked the CircuitVerse repository to my personal GitHub account.
- Cloned my fork to my local development environment.
- Created a new branch to keep my work separate from the main branch.
- Reviewed the issue description and contributor documentation.
- Began investigating the notification system within the codebase.
- Started identifying files that may be related to notification management and database relationships.

### Current Investigation
My initial understanding of the issue is that notifications may continue to exist after a related project or user has been removed from the database. This could potentially lead to invalid references or errors when notifications are displayed.
To investigate this further, I plan to:

- Locate the notification model and related controllers.
- Examine how notifications are associated with users and projects.
- Determine what occurs when a user or project is deleted.
- Identify whether notifications should also be deleted or handled differently.
- Implement and test a potential solution.

# Follow-Up Question and Reflections
The hardest thing for me to do was not really figuring out what was wrong, as there was plenty of hints for the issue, but figuring out how to work with github more indepth. Usually when I used github it was for documentation and file upload, so creating new branches and forks were new to me.
