# simple-java-maven-app

This repository is for the [Using Jenkins to build a Java/Maven project]( https://jenkins.io/doc/tutorials/using-jenkins-to-build-a-java-maven-project/)
tutorial in the [Jenkins User Documentation](https://jenkins.io/doc/).

The repository contains a simple Java application which outputs the string
"Hello world!" and is accompanied by a unit test to check that the main
application works as expected.

The `jenkins` directory contains an example of the `Jenkinsfile` (i.e. Pipeline)
you'll be creating yourself during the tutorial and the `scripts` directory
contains a shell script with commands that are executed when Jenkins processes
the "Deliver" stage of your Pipeline.
