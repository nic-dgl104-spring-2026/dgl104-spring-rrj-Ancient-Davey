# Design Patterns
This week introduced me to design patterns; these are not to be confused with just copy and paste type of material. A design pattern is a common, reusable solution to a commonly occurring problem in software design, it works more like a reusable blueprint. After learning about design patterns, I now understand how much an experienced developer must spend just as much time thinking about how his code will be structured, how different parts of a system communicate, and how it will be maintained.
I found it interesting that design patterns became widely recognized through the work of the “Gang of Four” authors, who documented 23 common patterns in their book Design Patterns: Elements of Reusable Object-Oriented Software. These patterns  being grouped into three different categories: Creational, Structural, and Behavioral patterns. Having a clear understanding of these categories helped me see that design problems often fall into predictable areas, such as how objects are created, how they connect, or how they interact with each other.
## Observer Pattern
The observer pattern, which belongs to the Behavioral category, solves the problem of keeping multiple objects informed when changes occur in another object. Multiple observers can listen to a single subject due to the pattern creating a one-to-many dependency. The stock ticker example simulates this quite well on how a single subject can notify multiple observers, such as chart display, alert system, and history logs. The main advantage of the observer pattern is that its components are loosely coupled meaning that the system will be much easier to extend and to maintain.
## Singleton pattern
The singleton pattern ensures that only one instance exists in the instantiation of the class. By providing a single access point, the pattern promotes consistency and prevents unnecessary duplication of resources. However, I also learned that overusing Singletons could create hidden dependencies and make applications harder to test. It also allows classes to control their instantiation and provide easier access to that instance. From what I learned use a Singleton only when a resource genuinely needs to exist with exactly once.
## Additional patterns
I looked briefly into several other design patterns. The Factory Method pattern for one separates object creation from object usage, making applications more flexible when different implementations may be needed. The Decorator pattern was easy to relate to because it works similarly to adding toppings to a coffee order, allowing functionality to be added without modifying the original object. The Strategy pattern stood out because it supports interchangeable algorithms, which would be useful in systems that need multiple approaches to solving the same problem. Finally, the Module pattern highlighted JavaScript's emphasis on encapsulation and organizing code into reusable, maintainable units.
## Personal Reflection
Overall, this lesson gave me a more insight into software development. Design patterns are not really shortcuts, but rather accumulated knowledge from previous developers who experienced the same challenges before hand. Learning these patterns helps me recognize common structures in the frameworks and libraries I already use.  
## Bibliography
> Refactoring Guru. (n.d.). Design Patterns. Retrieved July 5, 2026, from https://refactoring.guru/design-patterns

> Wikipedia contributors. (2026). Observer pattern. Wikipedia. https://en.wikipedia.org/wiki/Observer_pattern

> NIC DGL-104 App Development Foundations. (2026). Week 9 – Design Patterns course notes. North Island College.
# Activies
## Find Potential Projects To Contribute To
### Project 1: Next.js
URL: https://github.com/vercel/next.js
Project Summary
Next.js is a popular React framework used for building web applications. It is one of the most widely used JavaScript frameworks and is, from what I see, actively maintained by Vercel. The repository seems to regularly provide issues for "goodfirstissue" for new contributors.

#### Checklist Analysis

<img width="646" height="893" alt="Screenshot 2026-07-03 092109" src="https://github.com/user-attachments/assets/6ce613a2-681c-4986-9451-8fcb766eebac" />

#### Interesting Discoveries

- Over 140,000 GitHub stars, showing a very large community.
- Many beginner-friendly issues focus on documentation, testing, and small bug fixes rather than advanced programming.
- Contributing documentation is very detailed and helpful for first-time contributors.

#### Why I Would Consider Contributing
As a web development student, contributing to a React-based framework would provide me experience with modern industry tools and development workflows.

### Project 2: Shields.io
URL: https://github.com/badges/shields

#### Project Summary
Shields.io produces the status badges mostly seen in GitHub repositories. It is written primarily in JavaScript, from what I researched, and is widely used throughout the open-source community. The project currently has some beginner-friendly contribution opportunities available.

#### Checklist Analysis

<img width="636" height="896" alt="Screenshot 2026-07-03 095303" src="https://github.com/user-attachments/assets/b0a40afe-2193-445a-952b-7c67b9ddf84a" />

#### Interesting Discoveries

- Open Source: Shields.io has been licensed under the CC0 public domain license and has adopted a dual-license model, re-licensing under both the MIT and Apache 2.0 licenses, which enhances its copyright status. 
- Badge Creation: It allows users to create customizable badges for their projects, displaying information like build status, code coverage, or version numbers, streamlining developer tool workflows. 
- Community Engagement: The Shields community actively works on improving the platform, with ongoing efforts to support various package managers and enhance badge visibility. 
- Security and Compliance: Shields.io provides advanced security and compliance features, making it suitable for both small teams and large organizations. 
- User-Friendly Interface: The platform is designed to be user-friendly, with a responsive interface that simplifies the process of adding badges to project documentation. 

#### Why I Would Consider Contributing
The project is smaller and easier to understand than large frameworks, making it a good first open-source contribution experience.
 
### Project 3: CircuitVerse
URL: https://github.com/CircuitVerse/CircuitVerse

#### Project Summary
CircuitVerse allows users to create and simulate digital circuits directly in a web browser without needing specialized software or hardware, making it accessible for students, educators, engineers, and hobbyists. It also includes open issues specifically labeled for first-time contributors.

#### Checklist Analysis

<img width="667" height="902" alt="Screenshot 2026-07-03 101013" src="https://github.com/user-attachments/assets/066f961e-d801-4db4-a6ab-fcf3c4d29108" />

#### Interesting Discoveries
- Educational Platform: CircuitVerse is an educational platform designed to help students and educators construct, simulate, and share digital logic circuits online. 
- Open-Source Project: It is an open-source project with an active community, allowing contributions from anyone interested in improving or expanding the platform. 
- Interactive Learning: The platform offers interactive digital textbooks and tutorials designed to teach digital logic from the basics to more advanced concepts. 
- Collaboration: CircuitVerse allows for easy sharing of circuits, which is especially useful for educational settings where teachers can assign projects or share resources with students.
- Mobile Access: In addition to the web interface, CircuitVerse also offers a mobile app for Android, allowing users to work on circuits on the go.

#### Why I Would Consider Contributing
The issues seem to appear manageable while still being useful for learning purposes.

### Reflection
After reviewing these projects, I found that open-source contribution involves much more than writing code. Documentation improvements, user-interface enhancements, testing, translations, and bug reports are all valuable contributions. Among the three projects, CircuitVerse seems the most approachable for a first contribution, while Next.js would provide the most exposure to professional web-development practices.
