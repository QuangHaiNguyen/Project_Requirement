# Project Management Template

## Motivation

when I am working on a private project, there are  so many problems I have to face. First of all, if the project is interupted
for a while, when I restart it again, I dont know where to pick it up.  

I also have the problem with hardware and cost management. I dont know which hardware I am using and how much money I have spent on the project.

The next obvious thing is, there is no tool to manage requirements, architecture and any other documentation or resources.

One last thing I want to add is I have never track how much time I spend on a project.

## Solution

To cope with the mentioned proplems, I want to create an excel sheet with macros function. The excel sheet shall address those problems with the following solution.

* Project journal where I can shortly describe what I have done and when I have done those things. Normally, you can use git and commit message to keep track of what you are doing but the commit messages address which changes have been applied to the repo. The Project Journal is more about, what you have done since the last journal entry. It is like a personal diary of the project.

* List for tracking which hardware is used for the project, how much money have spent on the project regarding the development phase, prototype phase and the Bill of Material if the project is realized into a complete product.

* An interface to add, delete, modify requirements. It also allows user to trace the requirements to the supported requirements and other design artifacts (UML diagram, resources).

* A Gantt Diagram for time management.

## Usage

Please relate the Introduction and Userguide sheet in the template for "How to use the template"

## Room for improvement

The template is naturally not bullet proof so I am always open for any suggestions, recommendations and contributions. Here are some points that I think important for the next release:

* The template shall be tested more. I have done the testing, for sure, but it is not enough to call it a stress test.

* I am not an VBA guy, so the script may look "funny" and not so efficient. Therefore, Optimizing the script is also an topic.

* The Gantt diagram a very basic. Therefore, graphical enhance is neccessary.

* On the functional point of view, there is no linking between the requirements, between the requirements and journals entry. For example, The Entry - "Today I developed item number 1, 2 and 3" links to the requirement A, B or C. Therefore, these relationship must be shown and implemented.

## Change log

### 1.0.0

Initial Release

## Contact

For any information, feedback, recommendation, please use the Issues or send me an email.

Quang Hai Nguyen

hainguyen.eeit@gmail.com
