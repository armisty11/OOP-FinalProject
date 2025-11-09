## Overview

For our first week, our main focus was on brainstorming and planning the foundation of our project. I initially asked each member to propose libraries and features that could be integrated into our system. Everyone actively participated and presented different, creative, and well-thought-out ideas; each one unique and useful in its own way. Because of this, we actually struggled a bit to decide which ideas to include, since all of them were worth considering.

Despite that, the process turned out really well. We collaborated smoothly, exchanged opinions respectfully, and made sure everyone’s voice was heard. I’m genuinely proud to say that I chose the best people to work with, because so far, there have been no issues when it comes to communication and teamwork. Our team’s creativity and cooperation truly made the planning phase both productive and enjoyable.

## Task Distribution and Planning

After finalizing the project concept, datahabit, our group focused on assigning specific roles and responsibilities to ensure a clear direction and accountability from the very beginning. This allowed us to organize our workflow effectively and prepare for the development phase in the upcoming weeks.

The use of GitHub for project collaboration and version control was required by the instructor, allowing transparent tracking of each member’s commits and contributions. In addition, our group utilized a Messenger group chat for coordination, progress updates, and quick communication during the planning stage.

Our project lead, **Dahe, Aira Grettel C.**, managed the GitHub repository setup, established the initial project folder structure, and oversaw documentation and testing plans. 
**Dellosa, Karylle L.** served as the concept proposer and main coder, responsible for designing the core analysis logic of the library, including how the system detects and labels behavioral patterns.
**Hayag, Carmel Mariane T.** handled documentation, particularly drafting the README file and assisting in writing the narrative reports to document the group’s progress and decisions.
**Java, Armisty Genia L.** worked on visualization planning, preparing how the habit data would be presented through graphs and charts for clearer interpretation.
**Trillo, Rodney G.** focused on data handling, particularly the timestamp and data cleaning module, to ensure datasets are properly processed before analysis.

All in all, Week 1 was centered on establishing our foundation — finalizing the concept, clarifying everyone’s responsibilities, and ensuring all members were aligned with our project goals. This clear division of work allowed us to prepare to start Week 2 with direction, focus, and enthusiasm for bringing *datahabit* to life.

## System Design/UML Part

For our system design phase, we focused on building a clear and organized structure for DataHabit using OOP principles. This stage involved designing how the different parts of the system would interact with one another, ensuring that our program could efficiently handle, analyze, and visualize student task data. To achieve this, we created a UML class diagram that visually represents the relationships between the main components of our project.

Our design consists of three main classes: TaskData, BehaviorAnalyzer, and Visualizer. Each class was carefully planned to perform a specific role while maintaining modularity and simplicity.

The TaskData class serves as the foundation of the system. It handles the basic data structure, including student IDs, task names, and submission timestamps. This class also contains essential methods for parsing timestamps and calculating submission delays, which are crucial for later analysis. Since this class manages the raw data, it was designed to be reusable and extendable for future updates or additional features.

The BehaviorAnalyzer class inherits from TaskData, meaning it extends the base class to include behavior classification features. It is responsible for interpreting submission trends and identifying student behavior types such as “Procrastinator” or “Consistent Worker.” By using inheritance, we avoided code repetition and allowed the analyzer to directly use the data and methods from TaskData, making the design cleaner and more efficient.

The Visualizer class, on the other hand, was implemented through composition. It works by taking the analyzed data from the BehaviorAnalyzer class and transforming it into visual outputs like graphs and summaries. This helps present the patterns more clearly and allows users to easily understand the results of the analysis. The decision to use composition instead of inheritance was intentional, as it keeps visualization functions separate from data analysis, following the OOP principle of single responsibility.

Overall, our UML diagram shows how these classes connect and work together — inheritance between TaskData and BehaviorAnalyzer, and composition between BehaviorAnalyzer and Visualizer. We designed it this way to ensure flexibility, scalability, and clarity in our system’s flow. Each class handles a specific part of the process: data collection, behavior analysis, and visualization. This structured design not only keeps the system organized but also makes it easier to maintain and expand as we continue developing DataHabit.

## Repository Setup and Documentation

After completing the initial brainstorming and planning phase, our group proceeded to organize the project repository and set up its structure. We wanted to make sure our workspace was organized and easy to navigate before starting the actual development. We arranged the repository in a way that each part of the project would have its proper place and purpose. 

We decided to create four main directories: **Proposals**, **Reports**, **Final Project**, and **Docs**. Each served a specific function—Proposals for initial project concepts, Reports for weekly updates, Final Project for the implementation of our Python library, and Docs for documentation and reference materials. We also added important files such as **.gitignore**, **.gitattributes**, and the **MIT License** to ensure proper project setup and adherence to open-source standards.

The **README.md file** was then updated to include the project’s title, objective, and contributor details. We wanted it to clearly explain what the project was about and serve as a quick guide for anyone viewing our repository.

Overall, the setup process went smoothly. By the end of the week, we successfully built a structured and well-documented repository that laid the foundation for the upcoming coding and testing phases.

## Reflection

On our first week, we confidently say that our group made an excellent start in building the foundation for **DataHabit**. This initial phase was not just about outlining ideas, but about learning how to collaborate effectively and align our individual strengths toward a shared goal. The brainstroning sessions reminded us how valuable teamwork can be when everyone contributes thoughtfully. Each member's ideas were diverse yet insightful, which made decision making both exciting and challenging. Still, through open communication and respect for each other's perspectives, we managed to turn our collection input into a clear and unified project plan.

The process of assigning tasks also gave us a sense of direction and accountability. Everyone had a defined role that matched their strength, allowing us to work efficiently without confusion or overlap. We realized that clear task delegation is crucial, especially in a collaboration determines success. The use of **GitHub** and **Messenger** also made our workflow transparent and organized, ensuring that communication and progress tracking remained consistent.

Designing the system architecture and **UML** diagram was another rewarding experience. It gave us a concrete understanding of how our components interact and how **OOP principles** could make our project more maintainable and scalable. Seeing our ideas take shape through structure and logic made the project feel more real and achievable.





