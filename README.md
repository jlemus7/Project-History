# Project-History

This GitHub repository serves as a showcase of my past school projects, providing an overview of my programming skills and demonstrating the breadth of my experience. Each project within this repository represents a significant milestone in my educational journey and highlights my growth as a programmer.

Table of Contents

IT-145 Final Project

SC-230 Operating Platforms

CS-210 Programming Languages

============================================================================================

IT-145 Final Project

Description: The final project of IT-145 was intended to demonstrate my understanding of object-oriented programming principles by creating a project that utilized inheritance, polymorphism, encapsulation, and abstraction to implement a modular design. The purpose of this program was to create a system that contains information about rescue animals that are then destined as service animals. The system handles two kinds of animals Dogs and Monkeys. The system's purpose is to maintain a database of the animals in the form of array lists that contain animal objects. The program allows the user to add new monkeys and new dogs into the system, check for all the animals that are reserved, print a list of all the monkeys, and all the dogs, and print a list of the animals that are not reserved. The language used for this project is Java, and it was developed through Eclipse IDE.
The biggest challenge that I encountered in this project was the input validation part. The reason why I found this specific part challenging was that, from our initial given code, almost all, if not all, the variables and objects were of type String, which meant, the user could type anything, and it could have been easily accepted even though it was not the correct input. I consider that one of the things that I do not appreciate about Java is that we have to tell the scanner what is receiving, with scanner types like nextInt(), next().CharAt(), to name a few, even before the input is processed. Receiving the wrong type will immediately return an error which, although can be handled with exceptions, I consider affects the polymorphism of a function. To solve this problem, I created three functions dedicated to validating the user input, one that accepts only string characters from [A-Za-z]*, another one that accepts only numeric type input, and the last one that validates the format of the date, this last one was particularly harder because the input is both integers and non-letter/non-numerical characters within a string. I used if statements to validate the scanner’s content to ensure the desired input was in the scanner before continuing. In the end, I was very proud of my findings as I was able to validate every input the user entered and utilized these three functions in over twenty different processes in the Driver class.

============================================================================================

SC-230 Operating Platforms

Description: The Project of Operating Platforms was an introduction to systems analysis and design. This project was focused on collecting technical requirements for a web-based application “Draw it or Lose it”. The purpose of the application was to recreate the experience of the mobile version of the game, which was only available on Android. The game was loosely based on the 1980s television show "Win, Lose or Draw," where teams compete to guess what is being drawn. The application would render images from a large library of stock drawings as clues.
The main challenges faced during the project included reviewing the suitability of different operating platforms (Linux, Mac, Windows, and mobile) to host the application successfully. Understanding the functionality and limitations of each platform was crucial to making informed decisions.
Lessons learned during the project included the importance of identifying design constraints and creating clear instructions for both clients and developers. The domain model and UML diagrams were valuable tools for guiding the development process and ensuring a comprehensive understanding of the game's functionality before coding.

============================================================================================

CS-210 Programming Languages

The project aimed to develop a program that counts the frequency of grocery items purchased at a store. The purpose was to analyze the purchase data and generate a sorted list of the most frequently bought items. The program was implemented using C++ and involved file reading and writing, as well as the utilization of containers like vectors and maps.
The program read a text file containing the items purchased in order and created a frequency map to track the occurrence of each item. The map was sorted in descending order based on the frequency of items, allowing the most purchased items to be displayed at the top of the list. The user interface provided options to continue displaying items or end the program, ensuring convenience and flexibility.
Identifying and handling repeated words in the input file was a challenge that required efficient checking and avoidance of duplicates. The std::count() function from the C++ standard library was used to address this issue. Designing the sorting mechanism was another challenge. Since maps are designed for fast access rather than sorting, the sorted map was inserted into a vector of pairs to enable convenient access while maintaining the sorted order.
Working with maps and understanding their capabilities for efficient data storage and retrieval was a valuable lesson from this project. File reading and writing techniques were learned and implemented, providing essential skills for handling external data. Exception handling was used to manage runtime errors, improving the overall robustness of the program.


Conclusion

By exploring this Project History repository, you will gain insight into my programming capabilities and witness the evolution of my skills over time. Feel free to explore the projects and their respective source code to get a comprehensive understanding of my expertise in various programming languages, technologies, and problem-solving approaches.
For more information about me or to discuss potential collaborations, please feel free to reach out via the contact details provided in my resume.
