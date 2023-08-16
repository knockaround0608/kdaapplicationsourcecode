# kdaapplicationsourcecode
kinesis data analytics application source code
This application is from https://aws.amazon.com/blogs/devops/setting-up-a-ci-cd-pipeline-by-integrating-jenkins-with-aws-codebuild-and-aws-codedeploy/ You can download the sample from here.
 
In this example, the application files are in the templates directory, test_app.py file, and web.py file.

The appspec.yml file is the main application specification file telling CodePlay how to deploy the application. Jenkins uses the AppSpec file to manage each deployment as a series of lifecycle event "hooks", as defined in the file.

The buildspec.yml file is a collection of build commands and related settings in YAML format, that CodeBuild uses to run a build. You can include a build spec as part of the source code, or you can define a build spec when you create a build project.

The script folder contains the scripts that you would like to run during the CodeDeploy LifecycleHooks execution with respect to your application requirements
