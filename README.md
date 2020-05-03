# Integrate Toogl Entries with OpenProject
PHP Script to insert Toggl entries inside OpenProject Modules

Description:
This script allows the insertion of Toggl entries into OpenProject

INSTRUCTIONS

- You must get the ID of each user inside OpenProject
- You need the Toggl API KEY of each user (inside profile settings on Toggl website)
- The project name inside Toggl and OpenProject must to be the same.
- The descripcion of the Toggl entry must match the Module name inside OpenProject
- If the module to insert the time does not exist, the script inserts the time inside a module called "Others". *This module must be manually created in every projects*


RECOMMENDED

Create a cronjob to execute the script. For example every night.
