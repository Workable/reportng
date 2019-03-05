# Reportng
An HTML/XML reporting custom plugin for TestNG used by QA team

# Release Management - Maven release plugin
- mvn clean -Darguments=-DskipTests release:prepare
- mvn clean -Darguments=-DskipTests release:perform

If you changed your mind, or something got wrong:
- mvn release:rollback
- mvn release:clean

# Resources
- https://reportng.uncommons.org/
- https://reportng.uncommons.org/sample/index.html
- http://maven.apache.org/maven-release/maven-release-plugin/
