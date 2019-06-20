## Data Interview Project

### Overview

As a prospective candidate for a data role at Peerfit we'd like to see how you would go about solving data problems that are similar to the things you would solve day-to-day as a member of the Peerfit development team.
Before developing your solution, please consider the following:
- You should budget between 3-5 hours of time for your solution
- Your solution should include:
  - All python scripts and sql code/artifacts added to the `project/solution` directory
  - Completed questionnaire in the root of the project directory
- Thoughtful, well-documented partial solutions are acceptable - we want to see you go as deep as you can, but want to keep things reaonsably timeboxed.
- We want you to provide the database objects you would build out as part of your solution. These can be provided in a plain-text database schema file or a mysql/postgres database dump
- Your solution should include use of git and exhibit your style and process for version control

### Description
#### ETL Architecture

Given several different datasets for member reservation data, we want to build ETL pipelines that can support the transformation of this data to a normalized form. We want to use this data to report on things like:
- Reservations by studio by month showing:
  - Completed
  - Canceled
  - Abandoned (Did not cancel but did not check-in)
- Monthly unique members completing a reservation for a studio class
- Abandon rate across studio
- Cancel rate across member
- Incomplete/invalid data

The `project/data` directory provides the datasets necessary to complete the example.
