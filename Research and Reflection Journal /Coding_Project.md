# Task Management System - Project Documentation 

## Week 8 – Getting Started

This week was mostly about getting everything set up. I accepted the GitHub Classroom repository, created my Android Studio project, and spent some time reading through the assignment requirements. I also started thinking about what features I would need and how I wanted the app to be organized.

At this point, I knew I wanted to use Kotlin because I had more experience building code with it. I also started looking into design patterns since they were one of the project requirements.

## Week 9 - Did Nothing!

This week I did not do anything for the project as I planned to do it in the following week.

## Week 10 - Starting to build the Task Manager

### Activities
- Created the Android project in Android Studio.
- Designed the basic user interface.
- Implemented Create, Read, Update, and Delete (CRUD) operations for tasks.
- Added due dates, priorities, and task assignment.
- Created login and registration screens.
- Implemented the Singleton, Factory, Observer, and Strategy design patterns.

### Reflection
 I learned how design patterns can make code easier to organize. Using the Singleton for the database and the Factory pattern for creating users made the project much cleaner, but I guess that is a given when you start organizing parts into their separate folders.


## Week 11 - Problems with Firebase

### Activities
- Added logging using Android Logcat.
- Started creating unit tests.
- Fixed CRUD bugs.
- Improved the task editing screen.
- Added task assignment.
- Fixed RecyclerView refresh issues.
- Improved error handling.
- Connected the project to Firebase.
- Added Firebase Authentication.

### Reflection
This week involved a lot of debugging. I found several issues where tasks were not updating or deleting immediately because the RecyclerView was not refreshing correctly. Turns out it was that the problem was that I did not set up my Firebase correctly by not adding the settings after I added my app. Fixing these problems helped me better understand how Firestore updates data.


## Week 12 - Final Documentation and App Testing

### Activities
- Failed to add GitHub Actions for CI/CD.
- Improved the README documentation.
- Created the CONTRIBUTING.md file.
- Tested the application.
- Fixed remaining bugs.

### Reflection
By the end of this week the application included most of the required features. Most of my time was spent testing, improving the user experience, and making sure everything worked together properly. Even though I tried I could not seem to get the GitHub Actions working properly as even though I followed the steps it seems it did not want to link up with my repository and was only trying to send files from ".idea", even though ".github"  was not located in that file. So, please be lenient as I had no idea why it was acting weird.

## Final Reflection

Overall, this project helped me gain experience building a complete Android application using Kotlin and Firebase. I learned how to implement CRUD operations, user authentication, Firestore integration, and several software design patterns and I now have a better understanding on how each part of an app works together. I also became a little better at debugging problems and reading error messages.
