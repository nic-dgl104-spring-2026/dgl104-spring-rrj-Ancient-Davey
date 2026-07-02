# Week 8 (June 23 - 29)

## Topics I Have Covered

This week marked the transition into the second half of this course. Up to this point, the course had focused on building software correctly through concepts such as documentation, debugging, testing, code reviews, and refactoring. The focus now being shifted over to understanding how to determine what software should be built and how to define software requirement from a user's perspective.

The topic this week was Functional User Requirements and designing to revolve around the user.

### User Stories
A user story is a short description of a feature that a user would want.
Example:
As a <type of user>,
I want <some capability>,
so that I have <some benefit>.

User stories focus on the user's wants and needs rather than technical implementation details. This would help the dev team focus on solving the user problems instead of thinking about the programming solutions.

### INVEST Framework
I learned that effective user stories should be:
- Independent
- Negotiable
- Valuable
- Estimable
- Small
- Testable

The INVEST framework provide a useful checklist for determining whether a user story is practical and reasonable.

### Acceptance Criteria
Acceptance criteria is defined when a user story can be considered complete. They create a bridge between a user need and a testable feature.
Take for an example the Given-When-Then format:

- Given a starting condition
- When an action occurs
- Then a specific outcome should happen

See how this structure helps to create requirements that can be directly translated into test cases.


### Functional Requirements

Functional requirements describe what a system must do.

Example:

- FR-01: The system shall allow users to create an account.
- FR-02: The system shall allow users to log in.

Functional requirements are more precise than user stories and are written in a way that can be tested and verified. If you want it put simply it is very similar to a checklist but in this case it would be a checklist for the code to follow.


## Reflection

This week helped me see software development from a different perspective. Up until now, a lot of what we've learned has focused on writing cleaner code, debugging problems, testing, and keeping projects organized. Those skills are important, but this week's lesson made me realize that even well-written code isn't very useful if it doesn't actually solve a problem for the people using it.

Learning about user stories showed me how important it is to think like a user instead of immediately thinking like a developer. Before building a feature, it's important to understand who needs it, what they're trying to accomplish, and why it matters to them. That way, development is focused on solving real problems rather than just adding features.

I also found the INVEST framework helpful because it gives a simple way to check whether a user story is actually useful and realistic to implement. The section on acceptance criteria stood out to me as well because it clearly defines what "finished" looks like. Having specific criteria makes it easier to test features and confirm that they work as intended.

Overall, this week's material made me realize that software development isn't just about writing code—it's also about understanding users and planning features carefully before development begins. Going forward, I want to spend more time thinking about user needs and creating user stories before I start building features for my coding project. I think this will help me stay focused and make better design decisions throughout development.

## Activities
### Research a New Language
     So, for this quick research assignment I decided to go with Lua as it was generally considered simple and is used for making games which interested me. Lua is a lightweight scripting language mainly used for game development, embedded systems, and adding scripting features to some applications. For an example, apparently games like Roblox and World of Warcraft use Lua for their in-game scripting. For reference you can head to the official Lua website, which provides documentation straight from the creators, along with the free book “Programming in Lua” first edition, which delves into the language more in depth and clearly for the beginners interested in the particular language.

### Write a User Story
 App: Discord
Feature: Sending the messages to my friends in a channel
User Persona:
Name: John Doe
User Story: I can communicate with my friends in fun ways like with gifs, messages, video call, and even play games with them while on the call.
More Specific User Stories: 
-	I can send messages to my friends privately and effectively
-	I can have a video call with all my friends
-	I can play games while on the call
-	I can send messages mid conversation
-	I can chat with my friends while on the go
-	I have the ability to edit and delete my messages in case I misspell
-	I can have multiple chat groups for different topics
Acceptance Criteria:
-	Users can send private messages to individual friends.
-	Messages are delivered instantly and appear in the chat.
-	Users can start and join video calls with multiple friends.
-	Video calls include audio and video controls (mute, camera on/off).
-	Users can play games while on a call without leaving the app.
-	Users can send text messages during calls or conversations.
-	Messages can be sent and received on mobile devices.
-	Users can edit their own messages after sending them.
-	Users can delete their own messages from the chat.
-	Users can create and manage multiple chat groups.
-	Chat groups clearly display their members and purpose/topic.


