# IB Computer Science IA: Tech Manager

## Criterion A - Planning
### Problem Definition

My client is the head of the Tech Crew club at my school.

Tech Crew is a student-led organization responsible for all technical production services across campus events—from lighting and sound at prom to full-scale theatre performances. Recently, the club has had challenges managing multiple events simultaneously, each with its own unique requirements in terms of gear, scheduling, and space usage. 

The current system in place is entirely manual: Google Calendar & Forms for scheduling, and a group chat for coordination. As expected, this setup hasn’t scaled well. Students have been double-booked for different shows, ended up at the wrong locations due to miscommunication, and equipment like cables or lights have gone missing or unreported when damaged. 

To make matters more complicated, the team is composed of rotating volunteers with shifting availability and responsibilities. There’s no clean way to assign tasks, monitor participation, or record equipment usage history.
### Proposed Solution

Tech Crew needs a unified platform to manage task assignments, resource tracking, and scheduling—all in one place. To address this, I propose to develop an integrated application using Python, KivyMD, and SQLite. This application will centralize scheduling, inventory management, and team communication within a single user-friendly interface.

Python is a high-level, interpreted programming language known for its simplicity and readability, making it ideal for rapid development. Its extensive ecosystem of third-party libraries and frameworks adds to its versatility. I’ve chosen KivyMD for the front end because it offers a wide range of pre-built widgets and UI components that make it easy to build visually appealing and functional interfaces. KivyMD applications can also be deployed on Android and iOS, providing flexibility for future mobile versions of the app.

For data management, I’m using SQLite, a lightweight and self-contained database engine. It integrates seamlessly with Python and is well-suited for local storage. Using a database like SQLite allows for efficient data querying, better organization, and the potential to export data to other applications when needed.

Altogether, this tech stack provides a solid foundation for creating a streamlined solution that meets Tech Crew’s organizational needs—now and as the club grows.

### Success Criteria 

#### General Interface Features
1. The application has a dedicated login and registration system
2. Joining the application is closed. The app allows the admin to create new accounts with one-time only passwords, which will be changed by the user upon first login.
3. Upon login, users are redirected to a homepage, where tehy can view 
#### Task Management
4. The admin can create events and upcoming tasks, which will be sent to users and have 
5. Users can receive event and task requests sent out by the administrator, and have the options to participate or opt out of the event.
6. During events, all participants can mark themselves as present.


### References for Criterion A

References:
Python Software Foundation. (n.d.). About Python. https://www.python.org/about/


Stack Overflow. (2023). Developer Survey 2023. https://survey.stackoverflow.co/2023/#technology-most-popular-technologies


Kivy Team. (n.d.). Kivy Documentation. https://kivy.org/doc/stable/


KivyMD Developers. (n.d.). KivyMD GitHub Repository. https://github.com/kivymd/KivyMD


SQLite. (n.d.). About SQLite. https://www.sqlite.org/about.html


SQLite. (n.d.). Appropriate Uses for SQLite. https://www.sqlite.org/whentouse.html


GeeksforGeeks. (n.d.). Python SQLite. https://www.geeksforgeeks.org/python-sqlite/

## Criterion B - Design

### Diagrams

#### System Diagram
#### ER (Database) Diagrams
#### UML (OOP) Diagrams
#### Flowhcharts

### Record of Tasks

| Task No. | Planned Action                                     | Planned Outcome                                                                                                                                                                                                                        | Time Estimate | Date of Completion | Criterion |
|----------|----------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|--------------------|-----------|
| 1        | Client-developer meeting                           | Brief meeting with the head of Tech Crew; A discussion of the difficulties currently being faced was had.                                                                                                                              | 40 minutes    |                    | A         |
| 2        | Solution Brainstorming                             | With the list of issues obtained from the the discussion, research is done to search for potential solutions, as well as the feasibility                                                                                               | 35 minutes    |                    | A         |
| 3        | Solution Brainstorming Part 2 - Framework Drafting | Light drafting is done in to decide what would be required for the solution to work, i.e creating flowcharts of essential functions and deciding the structure of the required database and subsequent tables                          | 1 hour        |                    | A/B       |
| 4        | Success Criteria Creation                          | A list of criteria used to determine the success of the app is formed based on the needs of Tech Crew and what could be realistically achieved                                                                                         | 30 minutes    |                    | A         |
| 5        | Success Criteria & Solution Approval               | Success criteria is shown to both the client and my computer science teacher, with approval received from both.                                                                                                                        | 15 minutes    |                    | A         |
| 6        | Criterion A Documentation                          | Completion of the planning documentation, including evidence of client-developer interaction, the problem definition, a proposed solution and the subsequent success criteria, as well as the reasoning behind my development choices. | 1 hour        |                    | A         |
| 7        | Application Design - Structure                     | Initial design is fleshed out; elements such as the number of screens required for the app, as well as the functions needed for each screen are mapped out and broken down.                                                            | 2 hours       |                    | B         |
| 8        |                                                    |                                                                                                                                                                                                                                        |               |                    |           |
| 9        |                                                    |                                                                                                                                                                                                                                        |               |                    |           |
| 10       |                                                    |                                                                                                                                                                                                                                        |               |                    |           |
| 11       |                                                    |                                                                                                                                                                                                                                        |               |                    |           |
| 12       |                                                    |                                                                                                                                                                                                                                        |               |                    |           |
| 13       |                                                    |                                                                                                                                                                                                                                        |               |                    |           |
| 14       |                                                    |                                                                                                                                                                                                                                        |               |                    |           |
## Criterion C - Development
