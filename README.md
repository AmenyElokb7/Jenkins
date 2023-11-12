# My Jenkins Project

## Overview
This repository showcases my work in setting up a continuous integration and continuous delivery pipeline using Jenkins. The project is divided into two main parts: a FreeStyle project and a Pipeline project.

## Part 1: FreeStyle Project

### Initial Setup
1. Ensure Jenkins is installed and running on your server.
2. Access Jenkins at http://localhost:8080.

### Creating and Configuring a FreeStyle Project
1. Create a FreeStyle project named "MyFreeStyleProject" on the Jenkins dashboard.
2. Configure SCM (Git) under "Source Code Management."
3. Enable "Poll SCM" for regular code checks.
4. Schedule SCM checks every 5 minutes using the cron expression `*/5 * * * *`.
5. Add build steps with shell commands and echo messages under the "Build" section.

### Running the FreeStyle Project
1. Save the project configuration.
2. Click "Build Now" to execute the project.
3. Monitor the build progress through the project dashboard and logs.

## Part 2: Pipeline Project

### Creating and Configuring a Pipeline Project
1. Create a Pipeline project named "MyPipeline" on the Jenkins dashboard.
2. Integrate SCM checks in the Jenkinsfile.
3. Use the Jenkinsfile to define stages and echo messages for each step.

### Running the Pipeline Project
1. Save the project configuration.
2. Click "Build Now" to execute the pipeline.
3. Monitor the pipeline progress through the project dashboard and logs.

4. Test the pipeline by making a code change in your repository.

