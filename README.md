# Project Title: The Sound Editor

### Statement
We are going to create our own language/syntax similar to HTML where we will create a text editor for this new language and the user will be able to generate sounds. It will be a GUI application.

### Analysis
We will likely use recursion in our processing of the user input text. Map/filter will like be used when we execute the sounds we will program into our language.

Data abstraction will certainly be used in our parser, as we will have to take the user input, parse the syntax, and store what the user inputs. Not 100% sure yet on object orientation, though it would intuitively make sense to have a generic data object and specialize it for each type of sound we will support.

State modification will likely be a part of this program, though this isn't necessarily the best use of a functional language.

### Data set or other source materials
Data will be provided by the user

How will you convert that data into a form usable for your project? 
We will parse the user input (a syntax/markdown similar to html).

### Deliverable and Demonstration
At the end we wish to have a GUI application that will take some user input and produce a sound. We would like to save the user input to disc.

### Evaluation of Results
How will you know if you are successful? 
We will be able to type some text into a GUI program, press a button and sound will be produced by the computer.

## Architecture Diagram
Upload the architecture diagram you made for your slide presentation to your repository, and include it in-line here.

Create several paragraphs of narrative to explain the pieces and how they interoperate.

## Schedule

### First Milestone (Fri Apr 15)
A working GUI program and some sort of syntax for our language. The sound may or may not be produced by the program.

### Second Milestone (Fri Apr 22)
Work out the kinks in the parser and GUI program, sound will be produced by this date.

### Final Presentation (last week of semester)
Polish off the language, polish off the application and further extend if time allows (such as a visualization of the sound, like a graph or graphic). Be able to save user input to disc.

## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.

### John Kilgo @john-kilgo *Team lead
will write the....

### Tony @put your username here
will work on...

### Tyler @tylerbezuka
I will work on the sound portion of the project using the rsound library.
