# Jira-jira_cloud_center-

brfore creating scripted field first we need to created a customfield with readonly configuration
the scripted file needs to place in scriptrunner add new scripted file with newly created customfield number and update

after successfully update of customfield_scrip in adaptivistscriptrunner
place the job file in job section of adaptive scriptrunner and give cron expression as (0 0 * * * ?) as it represent for 1hour

after all this setup now the real time of an issue from opened to closed will be saved in database except on-hold time of an issue.
