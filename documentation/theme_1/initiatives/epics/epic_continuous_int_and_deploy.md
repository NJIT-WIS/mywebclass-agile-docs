# Epic: Continuous Integration and Deployment
## Description: Allow easy integration into the central repo and quick reviewing and testing of code
## Stories
* [Automatically build and test code every time changes are made](stories/story_autotesting.md)
* [Easily deploy new features and bug fixes to production](stories/story_quickfix.md)
## Test Plan
* Make a small code change in the application codebase. 
* Push the code changes to the source code repository (e.g. GitHub)
* Observe if the CI tool reports the status of the build and test process (e.g. success, failure) and provides details about any errors or issues. 
* Verify that the build and test results are automatically reported to the team (e.g. via Slack, email, or a dedicated dashboard).
* Check if the DevOps setup includes a Continuous Integration/Continuous Deployment (CI/CD) pipeline that automatically builds, tests, and deploys changes to production. 
* Check if the DevOps team has a process for verifying changes before they are deployed to production. This may involve manual or automated testing, code reviews, or other quality assurance processes.