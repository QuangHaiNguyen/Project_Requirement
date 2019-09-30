# Project Management Sheet

## Motivation

when I am working on a private project, there are many problems I have to face. First of all, if the project is interupted
for a while, when I restart it again, I dont know where to pick it up.  

I also have the problem with hardware and cost management. I dont know which hardware I am using and how much money I have spent on the project.

The next obvious thing is, there is no tool to manage requirements, architecture and any other documentation or resources.

One last thing I want to add is I have never track how much time I spend on a project.

## Solution

to cope with the mentioned proplems, I want to create an excel sheet with macros function. The excel sheet must address those problems with the following solution

* Project journal where I can shortly describe what I have done and when I have done that thing

* List for tracking which hardware is used for the project, how much money have spent on the project regarding the development, prototype phase and the Bill of Material if the project is realized into a complete product.

* An interface to add, delete, modify requirements. It also allows user to trace the requirements to the supported requirements and other design artifacts (UML diagram, resources)

## Requirement of this project

Since there is no requirement tool for tracking the requirements of this project, I am using simply the the README file to store the requiremet.

### Requirement List

1. The Project Management Workbook shall include Five Excel Sheets: Project Journal, Cost Tracking, Bill of Material, Requirements, Project Time Management.

2. The Project Journal shall containt the following field: ID, Date, Time, Author and Content.

3. The Project Journal shall contain a button Add Entry.
    * When the user clicks the Add Entry button, a form is appear on the screen.

    * The form allow the user enter the following information:
        * Date, Time on which the current entry is created
        * Author of the current entry
        * Content of the entry
        * A button to save the current entry to the Project Journal Sheet
        * A button to delete the current entry
        * The ID is generated automatically by the VBA script
        * The ID will start with the value PJ00000

4. The Project Journal shall contain a button to delete a seleted entry.

5. The selected entry from requirement number 4 shall be defined when the user clicks on the ID field of an entry.
