# Reportng
An HTML/XML reporting custom plugin for TestNG used by Workable QA team

# Release Management - Maven release plugin
- ./gradlew clean build

Issue build to verify that changes made didn't break compilation

- ./gradlew publishToMavenLocal 

In order to properly test changes users are advised to build and then publish to local maven the new artifact. \
Copy the generated artifacts version and update the build.gradle file of the qa-tests project, update dependencies and \
execute at least on test. Ensure HTMLReporter is included in the Listeners lists of testNG configuration.

- ./gradlew publish

Release all publications produced by this project to target repository

# Deploying a Snapshot to JFrog
- ./gradlew publish \
  Release all publications produced by this project to target repository

# Resources
- https://reportng.uncommons.org/
- https://reportng.uncommons.org/sample/index.html
- http://maven.apache.org/maven-release/maven-release-plugin/
