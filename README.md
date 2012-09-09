# Sonar Workshop
This is the suite of materials for the Sonar Workshop run by Matthew McCullough of [Ambient Ideas, LLC](http://ambientideas.com).

## Sonar The Project
Sonar is an analysis and metrics tool that falls under the category of "continuous inspection." Its home on the web is http://sonarsource.org.

## License
This workshop's materials are licensed under an Apache 2.0 license (ASL).

## Feedback and Contributions
Feedback is always welcome. Email matthewm@ambientideas.com, but please have patience, as I receive as many as 250 emails per day. However, feedback is more welcome in the form of Pull Request contributions. Just fork this project, change it as you think it should be, and then send me a Pull Request. You'll see from other workshop materials that I host on GitHub that I'm very open to accepting Pull Request contributions. It gives us a place to have a conversation in the open about the integration of your suggestion with the existing code base.

------------------------

## Chat Room
### https://github.campfirenow.com/151d4

## Pre-re Testing

The environment variable `JAVA_HOME` needs to be set to a Java JDK. It is insufficent to have it set to a JRE because that does not include a Java compiler.

### What Java version is on my path?
For Windows, Mac or Linux, at the Command Prompt or Terminal, run:

    java -version

### Where are Java and Javac?
For Linux and Mac, at the Terminal, type:

    which java
    which javac

### What is JAVA_HOME set to?

For Windows, at the Command Prompt, run:

    echo %JAVA_HOME%

For Linux and Mac, at the Terminal, type:

    echo $JAVA_HOME

This environment variable should be set to the 


## Project 1 - clirunner_groovyhello
This is a build-system-less Groovy project that requires the Groovy plugin in Sonar.

### Sonar Technology Used
Documentation for the standalone Java Runner is at:
http://docs.codehaus.org/display/SONAR/Analyse+with+a+simple+Java+Runner

### Instructions
For Windows, at the Command Prompt, run:

    .\sonar-runner-1.2\bin\sonar-runner.bat

For Linux and Mac, at the Terminal, type:

    ./sonar-runner-1.2/bin/sonar-runner


## Project 2 - ant_junit
This is an Ant-based build of JUnit that uses an Ant build or the command line runner to analyze the source.

### Sonar Technology Used
Documentation for the standalone Java Runner is [here](http://docs.codehaus.org/display/SONAR/Analyse+with+a+simple+Java+Runner).

Documentation for the Ant plugin is [here](http://docs.codehaus.org/display/SONAR/Analyse+with+a+simple+Java+Runner).

### Instructions
To use the command line runner:

For Windows, at the Command Prompt, run:

    .\sonar-runner-1.2\bin\sonar-runner.bat

For Linux and Mac, at the Terminal, type:

    ./sonar-runner-1.2/bin/sonar-runner

To use Ant:

For Windows, Mac or Linux, at the Command Prompt or Terminal, from this project directory, run:

    ant sonar


## Project 3 - maven_commons-cli
This is a Maven-based build of Apache Commons CLI that uses the Maven Sonar plugin to analyze the source.

### Sonar Technology Used
Documentation for the Sonar Maven plugin is at:
http://TODO

### Instructions
For Windows, Mac or Linux, at the Command Prompt in this project directory, run:

    mvn jar sonar:sonar


## Project 4 - maven_commons-validator
Procedures and technology are the same as Project 3.


## Project 5 - gradle_javahello
This is a Gradle-based build of a simple HelloWorld application with tests that uses the Gradle Sonar plugin to analyze the source and test output.

### Sonar Technology Used
Documentation for the Sonar Gradle plugin is [here](TODO) and is in the core of the Gradle distribution.

### Instructions
For Windows, Mac or Linux, at the Command Prompt in this project directory, run:

    gradle sonar


## Eclipse Plugin
* TODO: Where to get ti