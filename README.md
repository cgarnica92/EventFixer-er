# EventFixer-er

This is a basic app developed using JQuery to help a user keep track of their workday tasks. 

The web page displays a collapse menu that reveals time slots labeled from 9AM-5PM (the average workday). Users can enter in a description of the desired task into the appropriate block, and then save the task to local storage by clicking the save button; so that the task can be viewed later, even if the page is re-loaded.

The API Moment.js is used so that the actual time of day can be tracked, and so the current date can be displayed on the page. By tracking the time, the application is able to help the user track the day. Time-blocks are color-coordinated to represent different parts of the day, (Grey for blocks of time that have passed, green for future events, and red for the current block).