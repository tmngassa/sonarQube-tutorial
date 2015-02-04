This example demonstrates how to analyze a project with Maven reusing JUnit and JaCoCo reports.

Prerequisites
=============
* [SonarQube](http://www.sonarsource.org/downloads/) 3.6 or higher
* [SonarQube Java Plugin](http://docs.codehaus.org/x/KwChCw) 1.4 or higher
* Maven 2.2.1 or higher

Usage
=====
* Build the project:

        mvn clean install

* Analyze the project with SonarQube using Maven:

        mvn sonar:sonar


