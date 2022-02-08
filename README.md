# jenkins_Capstone
Questions &amp; Answers of jenkins evalution

1.what is Multibranch Pipeline?
- Creates a set of pipeline projects according to detected branches in one SCM repository.
- A multibranch job is simply a folder of pipeline jobs. For every branch you have, Jenkins will create a folder. So instead of creating a pipeline job for each of the branches you have in a git repository, you could use a multibranch job. This means that you'll have to create only one job.

2. what is poll SCM ?
- Poll SCM polls the SCM periodically for checking if any changes/ new commits were made and shall build the project if any new commits were pushed since the last build.
3. what is build periodically ?
- the "build"  shall build the project periodically irrespective to whether or not any changes were made.

4. what is backup plugin in jenkins ?
- Backup plugin allows archiving and restoring your Jenkins (and Hudson) home directory.

5. what is thinbackup ?
- This plugin simply backsup the global and job specific configurations (not the archive or the workspace). This plugin is up for adoption.
- 
6. what is webhook in jenkins ?
-A webhook is a mechanism to automatically trigger the build of a Jenkins project upon a commit pushed in a Git repository.
