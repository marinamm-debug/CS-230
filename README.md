# CS-230
CS 230 portfolio featuring the software design document for The Gaming Room’s Draw It or Lose It application and a reflection on software design, architecture, and client requirements.

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room was the client for this project. They wanted to expand their Android game, Draw It or Lose It, into a web-based application that could run on multiple operating platforms. The game needed to support multiple teams and players, use unique names for games and teams, and maintain only one instance of the game service.

What did you do particularly well in developing this documentation?

I did well at connecting the client’s requirements to specific design choices. I explained how the application’s structure would support games, teams, and players while keeping the information organized. I also compared operating platforms and considered how memory, storage, and security would affect the application.

What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand the relationships between classes before implementing the code. Having the requirements and UML diagram available made it easier to determine each class’s responsibilities. It also helped me understand how the singleton pattern could maintain one game service and how checking existing names could prevent duplicates.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise the recommendations section to include more specific examples of how the application would handle multiple games running at the same time. I would explain how shared game data would stay consistent and how the system could grow as more players joined. This would make the recommendations more useful to the development team.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I translated the client’s needs into requirements for platform access, game organization, and unique names. I addressed these requirements through a browser-based design, separate classes for games, teams, and players, and checks to prevent duplicate names. Considering users’ needs is important because the software must solve their problems and be practical for them to use. A design can be technically correct but still fail if it does not meet those needs.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I started by reviewing the client’s requirements and identifying the main objects and relationships in the application. I used UML diagrams, object-oriented design principles, and design patterns to organize the solution. For a similar project, I would continue using these strategies while asking more questions early about expected users, security, and performance. I would also review the design against the requirements throughout development to catch problems before they become harder to fix.
