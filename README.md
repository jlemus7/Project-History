# Project-History

This GitHub repository serves as a showcase of my past school projects, providing an overview of my programming skills and demonstrating the breadth of my experience. Each project within this repository represents a significant milestone in my educational journey and highlights my growth as a programmer.

Table of Contents

IT-145 Foundation of App Development

SC-230 Operating Platforms

CS-210 Programming Languages

CS-300 Data Structures and Algorithms

SC-255 System Analysis and Design

==========================================================================

IT-145 Foundation of App Development

Description: The final project of IT-145 was intended to demonstrate my understanding of object-oriented programming principles by creating a project that utilized inheritance, polymorphism, encapsulation, and abstraction to implement a modular design. The purpose of this program was to create a system that contains information about rescue animals that are then destined as service animals. The system handles two kinds of animals Dogs and Monkeys. The system's purpose is to maintain a database of the animals in the form of array lists that contain animal objects. The program allows the user to add new monkeys and new dogs into the system, check for all the animals that are reserved, print a list of all the monkeys, and all the dogs, and print a list of the animals that are not reserved. The language used for this project is Java, and it was developed through Eclipse IDE.

The biggest challenge that I encountered in this project was the input validation part. The reason why I found this specific part challenging was that, from our initial given code, almost all, if not all, the variables and objects were of type String, which meant, the user could type anything, and it could have been easily accepted even though it was not the correct input. I consider that one of the things that I do not appreciate about Java is that we have to tell the scanner what is receiving, with scanner types like nextInt(), next().CharAt(), to name a few, even before the input is processed. Receiving the wrong type will immediately return an error which, although can be handled with exceptions, I consider affects the polymorphism of a function. To solve this problem, I created three functions dedicated to validating the user input, one that accepts only string characters from [A-Za-z]*, another one that accepts only numeric type input, and the last one that validates the format of the date, this last one was particularly harder because the input is both integers and non-letter/non-numerical characters within a string. I used if statements to validate the scanner’s content to ensure the desired input was in the scanner before continuing. In the end, I was very proud of my findings as I was able to validate every input the user entered and utilized these three functions in over twenty different processes in the Driver class.

==========================================================================

SC-230 Operating Platforms

Description: The Gaming Room wants to develop a web-based application for their game Draw It or Lose It. This game must hold the same characteristics as their current mobile version, which is only available on Android.
Draw It or Lose It is a game that is loosely similar to the 1980s television show “Game Win, Lose or Draw,” where teams compete to guess what is being drawn. In this game, however, the application will render images from a large library of stock drawings as clues. A game consists of four rounds of play lasting one minute each. Drawings are rendered at a steady rate and are fully complete at the 30-second mark. If the team does not guess the puzzle before time expires, the remaining teams have an opportunity to offer one guess each to solve the puzzle with a 15-second time limit.
For this application, I was tasked to review the three traditional operating platforms (Linux, Mac, and Windows), as well as mobile platforms in order to determine which operating platform could host the application successfully.
The application had the following requirements:
  1.	A game can have one or multiple teams involved.
  2.	Each team will have multiple players assigned to it.
  3.	The game and team names must be unique.
  4.	The user should be allowed to check whether a name is in use when choosing a name.
  5.	Only one instance of the game can exist in memory at any given time.
  6.	Each game must contain a unique identifier.


The main challenges faced during the project included reviewing the suitability of different operating platforms (Linux, Mac, Windows, and mobile) to host the application successfully. Understanding the functionality and limitations of each platform was crucial to making informed decisions.

Lessons learned during the project included the importance of identifying design constraints and creating clear instructions for both clients and developers. The domain model and UML diagrams were valuable tools for guiding the development process and ensuring a comprehensive understanding of the game's functionality before coding. The key aspect of a successful software design document is understanding the client’s requirements and the development limitations of both software and hardware. This was my approach to developing this design. First, it is important to understand what the client wants in the application. After the requirements have been labeled, it is important to analyze the software and hardware elements such as memory management, operating systems, databases, security, and storage to identify what requirements can be met and how. It is also important to identify potential roadblocks and constraints as well as provide a solution on how these can be eliminated. Lastly, it is important to provide recommendations for both software and hardware that can be implemented in the development of the application in order to be successful for both the user and the client.

==========================================================================

CS-210 Programming Languages

Description: The project aimed to develop a program that counts the frequency of grocery items purchased at a store. The purpose was to analyze the purchase data and generate a sorted list of the most frequently bought items. The program was implemented using C++ and involved file reading and writing, as well as the utilization of containers like vectors and maps.

The program read a text file containing the items purchased in order and created a frequency map to track the occurrence of each item. The map was sorted in descending order based on the frequency of items, allowing the most purchased items to be displayed at the top of the list. The user interface provided options to continue displaying items or end the program, ensuring convenience and flexibility.

Identifying and handling repeated words in the input file was a challenge that required efficient checking and avoidance of duplicates. The std::count() function from the C++ standard library was used to address this issue. Designing the sorting mechanism was another challenge. Since maps are designed for fast access rather than sorting, the sorted map was inserted into a vector of pairs to enable convenient access while maintaining the sorted order.

Working with maps and understanding their capabilities for efficient data storage and retrieval was a valuable lesson from this project. File reading and writing techniques were learned and implemented, providing essential skills for handling external data. Exception handling was used to manage runtime errors, improving the overall robustness of the program.

==========================================================================

CS-300 Data Structures and Algorithms

Description: This project was intended to expand the knowledge of data structures and algorithms and how these play a role in a program’s runtime and memory management. For this project, we were asked to analyze the runtime complexity of common algorithms from three different data structures, vector, hash table, and binary search tree. The goal was to choose a data structure that proficiently stored and handled a course entity that contained a name, a course ID, and a list of prerequisites to handle requests like inserting, sorting, searching, deleting, and printing.

In order to find the most efficient data structure, I developed pseudocode for every algorithm to be performed in the project, from reading data from an external file to printing the whole data structure to the console. I performed a runtime complexity analysis of each algorithm individually to decide which data structure was the most efficient for the kind of data that I was trying to store. I then selected a data structure and performed an overall runtime complexity analysis to determine the performance and memory management capabilities of the complete program.

The major roadblock of this project was to determine the runtime complexity of independent nested loops (nested for-loops) and iterations that depended on conditions such as if-statements. Although the functionality of these statements is self-explanatory on their own, applying this concept to a big data set proved challenging at first. In order to overcome this obstacle, I deeply analyzed the written pseudocode and did external research on the subject to understand the dependency of each written statement. After understanding this dependency, it became easy to determine the runtime complexity of each statement and the difference between linear and quadratic runtime complexity.

This project has taught me a great deal about the importance of considering the underlying processes that involve running a software application. Initially, I would rely on predetermined data structures such as arrays, vectors, and maps to store data. Before this course, I used to choose a data structure based on my level of comfort without considering the overall performance of the application. Now, I have developed the skills to analyze data, its purpose, and functionality before starting to develop code and choose a data structure, which has enhanced my critical thinking and analytical skills.

This project has reinforced the importance of planning when it comes to software development. Before this course, I used to start with code and use pseudocode as a supporting alternative. This project has taught me the importance of planning and analyzing a process before its implementation starts. Using pseudocode as a planning tool has made my code easier to understand and implement. This method has also reduced the time that I spend coding to less than 50%, which has also reduced the likelihood of frustration in the process. This project has also enhanced my implementation of best practices such as in-line comments and descriptions of processes between functions, which improves the readability and maintainability of my code.


==========================================================================

SC-255 System Analysis and Design

Description: The DriverPass project is an initiative to provide better driver training and education. The client, Liam, is the founder of DriverPass and envisions a company that offers online classes, practice tests, and on-the-road training for customers seeking to improve their driving skills. The desired interface for the system is a web-based solution utilizing cloud technology to handle backup and security. The design must have the ability to generate downloadable reports and provide security measures like access control based on company roles. The system must also provide users with an account where they can manage goods and services such as appointment schedules, course material, and comments on past lessons. The system also must use an activity tracking system to know who makes changes and updates. The client also intends to comply with the state standards and regulations, and for this reason, they also want the system to communicate with the DMV on updates on driving rules and regulations.

The main challenge faced in this project was the recommendation of hardware and software that could handle the system's functional, non-functional, and technical requirements based specifically on the system's needs. I approached this issue by conducting research on the technical requirements such as cloud-based systems, database services, web-based frameworks, server options, and the memory management services each option provides. After this research, I was able to provide an educated suggestion on hardware and software to begin the production and testing of the system.

Some of the most important things that I learned in this course was the attention to detail and understanding of client needs. Some of the strategies that I would use in the future for system design include understanding client requirements and user needs, planning and organizing the order of tasks to be completed, understanding software hardware limitations to provide the best suggestions, and detailed decomposition of functional requirements in order to provide good documentation of the system for both the client and the development team.

==========================================================================

Conclusion

By exploring this Project History repository, you will gain insight into my programming capabilities and witness the evolution of my skills over time. Feel free to explore the projects and their respective source code to get a comprehensive understanding of my expertise in various programming languages, technologies, and problem-solving approaches.
For more information about me or to discuss potential collaborations, please feel free to reach out via the contact details provided in my resume.
