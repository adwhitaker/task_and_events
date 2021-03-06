# Kaffee (Task and Event Manager)
Kaffee allows the user to keep their personal tasks and Google Calendar events in one place, allowing them to view what needs to be completed today and in the upcoming week.

Kaffee can be viewed at: http://arcane-anchorage-79235.herokuapp.com/

## Features

### Daily Tasks
- view personal tasks and Google Calendar events for the current day
- add new task
- set tasks start date in the future - tasks will appear in this view on that date
- checkbox to complete task
- view information about personal tasks, as well as update and delete the information
- view information about events for the current day

### Weekly Tasks
- calendar view of the current week events from Google Calendar

### Completed Tasks
- list of completed tasks
- option to uncheck task to add it back to the list of tasks to be completed

### Settings
- add, update and delete personal everyday tasks that are to be completed daily
- everyday tasks are displayed at the top of the page beside the application logo
- everyday tasks can be completed by clicking on the box at the top of the page

## Running the Server
- after cloning the project, run `npm install` in the terminal
- PostgreSQL database setup information can be found in database.sql
- in the Google Developer Console create a new project to use Google OAuth/Google Calendar
- enter the AUTHORIZATION_URL, TOKEN_URL, CLIENT_ID, CLIENT_SECRET, CALLBACK_URL, and SECRET in a new .env file
- in the terminal, run `npm start`
- go to localhost:3000 in a Chrome Browser
- in the terminal, press Control + C to quit the server connection

## Stretch Goals
- post to Google Calendar
- page to view tasks set in the future
- Fitbit OAuth setup/step counter display
- edit events and personal tasks on weekly view
- update bootstrap modals to angular ui-bootstrap

## Authors
- Alexander Whitaker
