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
