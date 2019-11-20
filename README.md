
# Python Robot Ninja Challenge - Hong Kong

This document provides an overview of the methodology used in developing the Robot Ninja and the corresponding outcome.

## Methodology - Scrum

As the rules for the challenge were unclear in the beginning, we had identified Agile as a better way for managing. Objectives were broken down into tasks that fit into the sprints and outcome was secured through the MVP (minimum viable product) after each sprint. Scrum was chosen as the framework for Agile project management.  

### JIRA

A JIRA site was built to manage the backlog items and sprints.

**Sample screenshots:**
* ..\sampleScreenshot\JIRA_1.png
* ..\sampleScreenshot\JIRA_2.png
* ..\sampleScreenshot\JIRA_3.png

### Daily Stand-up Meeting

Daily standup meetings were held to keep track of the progress.

**Sample screenshots:**
* ..\sampleScreenshot\dailyStandup_1.png
* ..\sampleScreenshot\dailyStandup_2.jpg

## Outcome

We had selected two of the programs we developed to be presented.

### Obstacle Avoidance mode

The program enabled the robot to dodge any obstacle that’s on its way, including those that suddenly showed up. This was achieved by constantly sweeping the servo and retrieving distance data while the robot was moving.

**Code:**
* ..\code\obstacle.ipynb

**Sample screenshots:**
* ..\sampleScreenshot\log_obstacle.png

### Maze mode

The program enabled the robot to traverse any maze. The algorithm behind was the wall-follower algorithm. By always following the left / right wall, it led the robot our of the maze.

**Code:**
* ..\code\maze.ipynb

**Sample screenshots:**
* ..\sampleScreenshot\log_maze.png