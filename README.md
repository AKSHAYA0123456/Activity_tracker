# Activity Tracker Chrome Extension

## Assignment

### Problem Statement
People tend to browse the web for numerous hours and during these hours sometimes they fail to be productive. In this era of social media where short videos have taken over the world, time seems to flow without much realization. Your task is to make a chrome extension that will track all the time you are spending on each website. And provide analytical information to organize the time you are spending on the internet. The aim of this project will be to make people focus on productivity and reduce the time spent on distractive websites like Instagram, Facebook, Netflix, etc.

### Feature List (Must Have)

1. *Chrome Extension*
    - Anyone with an email address can create an account and login to the extension.
    
2. *Track Activity*
    - Time Spent on each Website (Active Tab)
    - Track activity or time spent on a specific part of the website.
    - For example: a user visits eLitmus.com/jobs, it should be tracked that user visited that page along with the time spent on it.

3. *Productive Browsing*
    - Users should be able to add and delete websites to restricted lists.
    - If they visit restricted sites, they will see the warning and cannot proceed to that website.
    - For example: A user has added netflix.com in the restricted list, they will not be able to open Netflix.
    - Users can set a time limit on websites.
    - If they exceed the time restriction, the tab will be automatically closed.
    - For example: An user has set a time restriction of 30 minutes, so after 30 minutes ends, the user will not be able to access that website.

4. *Personalized Dashboard*
    - Each user can see their website usage.
    - Users can login to the dashboard with the same credentials as for chrome extension.
    - Users should be able to see the time they spent on each website, data should be presented in the form of a graph or other similar metrics.
    - When clicked on a specific website from the list, Users should be able to see detailed analytics for that website, such as time spent on each page, idle time, active time, etc.
    - Users should be able to categorize websites into different groups, such as distracting, productive, entertainment, etc.

### Additional Features

- *Data Filter*
    - Generate Reports daily, weekly, monthly and yearly.

- *Feedback*
    - Provide Tips for managing browsing time.

### Motivation
- The project aims to increase productivity by helping users track and manage their browsing time effectively. By providing insights into their browsing habits and restricting access to distractive websites, users can focus more on productive tasks.

### Tech Requirements

- *Backend:* RubyOnRails
- *Frontend:* Any Javascript Framework
- *Database:* MySQL
- All the code and documentation should be pushed to GitHub
- Deploy the final application to any cloud-hosting website of your choice

## Setup Instructions

1. *Backend Setup:*
    - Clone the repository.
    - Install RubyOnRails and MySQL.
    - Run bundle install to install dependencies.
    - Set up the database using rails db:create and rails db:migrate.
    - Start the Rails server using rails server.

2. *Frontend Setup:*
    - No specific instructions provided. Choose any Javascript framework and set it up according to its documentation.

3. *Chrome Extension Setup:*
    - Load the extension in developer mode in Chrome browser.
    - Configure extension settings as required.

### Implemented Features

-  Chrome Extension functionality.
-  User authentication and login system.
-  Tracking time spent on each website.
-  Restricted website list with time limits.
-  Personalized Dashboard with website usage metrics.
-  Data categorization and filtering.
-  Backend setup with RubyOnRails and MySQL.
-  Frontend setup using Javascript framework.
-  GitHub repository with well-organized and documented codebase.
-  Deployed application to a cloud-hosting website.
-  README file with setup instructions and project details.

### Additional Features

-  Data Filter for generating reports.
-  Feedback system for managing browsing time.

## Project Value to Society

This project aims to promote productivity and mindful browsing habits among users. By tracking and analyzing their online activities, users can make informed decisions about how they spend their time on the internet. The restriction features help users limit their access to distractive websites, fostering a more focused and productive online experience.
