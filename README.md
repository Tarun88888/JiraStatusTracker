# Jira-jira_cloud_center-

Jira customized script for storing real time of an issue except oh hold.
    This project stores and updates the real-time status of Jira issues from when they are opened to when they are closed, excluding the       "On Hold" status. The status changes are saved in a database with a formatted duration.

Prerequisites
  Jira Cloud: Ensure you have access to Jira Cloud.

  ScriptRunner: Install the ScriptRunner plugin for Jira.

Setup Instructions

1. Create a Custom Field
  First, create a custom field in Jira with read-only configuration.
2. Add Scripted Field
  In ScriptRunner, add a new scripted field.
  Use the newly created custom field number in your script.
  Update the script as needed.

3. Update Custom Field Script
   After successfully updating the customfield_script in Adaptivist ScriptRunner, proceed to the next step.

4. Create a Job in ScriptRunner
  Place the job file in the job section of Adaptivist ScriptRunner.
  Set the cron expression to (0 0 * * * ?), which represents a 1-hour interval.

5. Save Real-Time Issue Status
  With all the setup complete, the real-time status of an issue from opened to closed will be saved in the database, excluding the "On      Hold" time of an issue.

License
This project is licensed under the MIT License - see the LICENSE file for details.
