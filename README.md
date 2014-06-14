POSA-14
=======

This repository contains assignments and examples for the 2014 offering of the POSA MOOC (see www.coursera.org/course/posa for more information) stripped from Eclipse dependencies and converted into something more IDE neutral like Maven.

## Build instructions

Whenever project uses Maven (pom.xml file exists in project directory) simply invoke:

	$ mvn -q package

from directory containing pom.xml file (provided that you have Maven installed).

## Specific assignment instructions

### Assignment from week 2, running BuggyLongTest

After building (JUnit test failure is not issue here) invoke:

	$ cd target/classes && java edu.vuum.mocca.BuggyLongTest -classpath . && cd ../..

from assignment root directory.

### Assignment from week 4, running PingPongRight

After filling all the TODOs and building invoke:

	$ cd target/classes && java edu/vuum/mocca/PingPongRight -classpath . && cd ../..

from assignment root directory.
