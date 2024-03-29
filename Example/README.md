# Example and Implemented Requirements

## Example

In the same folder, you will find an excel file called Example showing you how to emplemnt the Preject Management template. A lot of time and date in the Example is not consistent because I have created it for mock test.

## Requirement of this project

Since there is no requirement tool for tracking the requirements of this project, I am using simply the the README file to store the requirements.

### Requirement List

Strike through Item means that is is already implemeted

1. ~~The Project Management Workbook shall include Five Excel Sheets: Project Journal, Cost Tracking, Bill of Material, Requirements, Project Time Management.~~

2. ~~The Project Journal Sheet shall containt the following field: ID, Date, Time, Author and Content.~~

3. ~~The Project Journal Sheet shall contain a button Add Entry.~~
    * ~~When the user clicks the Izem Entry button, a form is appear on the screen.~~

    * ~~The form allow the user enter the following information:~~
        * ~~Date, Time on which the current entry is created. The Date and Time will be automatically generated by the VBA script~~
        * ~~Author of the current entry~~
        * ~~Content of the entry~~
        * ~~A button to save the current entry to the Project Journal Sheet~~
        * ~~A button to delete the current entry~~
        * ~~The ID is generated automatically by the VBA script~~
        * ~~The ID will start with the value PJ0000~~

4. ~~The Project Journal shall contain a button to delete a seleted entry.~~

5. ~~The selected entry from requirement number 4 shall be defined when the user clicks~~ on the ID field of an entry.

6. ~~The Cost Tracking Sheet shall include six fields : Date, Time, ID, Item, Price, Link.~~

7. ~~The Cost Tracking Sheet shall contain a button Add Cost.~~
    * ~~When the user clicks the Add Cost button, a form is appear on the screen.~~

    * ~~The form allow the user enter the following information:~~
        * ~~Date, Time on which the current item is created. The Date and Time will be automatically generated by the VBA script~~
        * ~~Author of the current item~~
        * ~~Price of the item~~
        * ~~Link where the item is purchased~~
        * ~~A button to save the current item to the Cost Tracking Sheet~~
        * ~~A button to delete the current item~~
        * ~~The ID is generated automatically by the VBA script~~
        * ~~The ID will start with the value CT0000~~

8. ~~The Cost Tracking Sheet shall contain a button to delete a seleted item.~~

9. ~~The selected item from requirement number 8 shall be defined when the user clicks on the ID field of an entry.~~

10. ~~The Bill of Material (BOM) Sheet shall include five fields : ID, Item, Partnumber, Price, Link.~~

11. ~~The BOM Sheet shall contain a button Add Cost.~~
    * ~~When the user clicks the Add Item button, a form is appear on the screen.~~

    * ~~The form allow the user enter the following information~~
        * ~~Item field describes the name of the Item on the PCB. This name is given by Author~~
        * ~~Author of the current Item~~
        * ~~Price of the item~~
        * ~~Link where the item is purchased~~
        * ~~A button to save the current item to the BOM Sheet~~
        * ~~A button to delete the current item~~
        * ~~The ID is generated automatically by the VBA script~~
        * ~~The ID will start with the value BOM0000~~

12. ~~The BOM Sheet shall contain a button to delete a seleted item.~~

13. ~~The selected item from requirement number 12 shall be defined when the user clicks on the ID field of an entry.~~

14. ~~The Requirement Sheet shall include five fields~~
    * ID
    * Date
    * Time
    * Author
    * Requirement
    * Type
    * Priority
    * Status
15. ~~The VBA script shall automatically update the ID field.~~

16. ~~The ID field shall start with the prefix R and count from 0000. For example R0000.~~

17. ~~The VBA script shall generate Date and time field automatically.~~

18. ~~When the user modifies Requirement, Author, Priority or Status field, the VBA script shall automatically update the Date and time field.~~

19. ~~Requirement field shall contain the text describing the requirement.~~

20. ~~Priority field shall describe the priority of the requirement:~~
    * Low
    * Normal
    * High
    * Critical

21. ~~Status field shall describe the status of the requirement:~~
    * Not-implemented: this requirement won't be implemented
    * Pending: this requirement will be implemented but it must wait for other higher priority requirement to be finished
    * Implementing: the requirement is being implemented
    * Finished: this requirment is implemented

22. ~~In the same sheet, there shall be a section describing how the requirement should be formulated in natural languague.~~

23. ~~The Type field shall describe the type of the requirement:~~
    * Functional
    * Non-Functional
    * Constraint

24. ~~There shall be one button to let the user add new requirement.~~

25. ~~There shall be one button to let the user delete a selected requirement.~~

26. ~~The selected requirement in 25 shall be define as, when the user click on the ID field.~~

27. ~~When the user clicks on the add button, a form shall appear to let the user enter the information described in 14.~~

28. ~~The form shall have a save button and cancel button.~~

29. ~~Whenever the status of the project changed into implementing, the requirement ID and date will be added into the table in the Project timeline sheet.~~

30. ~~The project timeline sheet shall include the following field:~~
    * ID
    * Start date
    * End date
    * Duration
    * Actual end date
    * Actual duration
    * Progress
    * Status

31. ~~ID and Start date shall be automatically filled by the VBA script describe in 29.~~

32. ~~End date shall be the focasting end date which is set by user. In other words, it is the theoretical end date.~~

33. ~~Duration shall be number of date, in which a requirement is being implemented. It is calculated based on Start date and End date. Therefore it is the theoretical duration.~~

34. ~~Actual end date shall be the date, in which the requirement is atucally implmemented. It shall be the same date that the status of the requirement in the Requirement sheet change from implementing to implemented.~~

35. ~~The Progress field shall be the percentage of the project which is already implemented. It shall be expressed in:~~
    * 0%
    * 25%
    * 50%
    * 75%
    * 100%

36. ~~Status of the project shall describe the actual state of the requirement implementation.~~

37. ~~It shall be described with the following parameter:~~
    * On going: the requirement is being implemented and it is on time.
    * Late: the requirement is being implemented and it passed the end date (aka deadline).
    * Finished on time: the requirement is finished implemented and it is on time.
    * Finish late: the requirement is finished implemented and it is late.

38. ~~On going shall be determenined by the progress is not 100% and current day less than End date.~~

39. ~~Late shall be determenined by the progress is not 100% and the current day is greater than end date.~~

40. ~~Finished on time shall be determenined by the progress is 100% actual end date is smaller or equal end date.~~

41. ~~Finished late shall be determenined by the progress is 100% actual end date is greater than the end date.~~
