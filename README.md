osxappbundle-maven-plugin
=========================

Forked [osxappbundle-maven-plugin](http://mojo.codehaus.org/osxappbundle-maven-plugin/) v. 1.0-alpha-2

In this fork the following issues have been fixed:

* [MOJO-1688](http://jira.codehaus.org/browse/MOJO-1688) On Mac OS X whith SetFile utility, the generated .app has an alias attribute and do not execute
* [MOJO-1888](http://jira.codehaus.org/browse/MOJO-1888) Allow to skip packaging the app bundle as a Zip archive
* [MOJO-1889](http://jira.codehaus.org/browse/MOJO-1889) Allow packaging pom
* [MOJO-1892](http://jira.codehaus.org/browse/MOJO-1892) Do not create a $JAVAROOT/repo folder if there are no project dependencies to copy there