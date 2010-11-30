# android sbt project

[g8](http://github.com/n8han/giter8) template to get an android sbt project up and running in a matter of seconds

## how to use

to use this template, g8 needs to be installed first.
read g8's [readme](http://github.com/n8han/giter8#readme) for more information

all done? now fire up your favorite shell and enter

	mkdir bestappever && cd bestappever
    g8 gseitz/android-sbt-project
    sbt update
	sbt compile

## what you get

your android sbt project contains 2 subprojects:

	* MainProject
		* generated AndroidManifest.xml
		* MainActivity.scala (aka "hello world" activity)
	* TestProject

## credit
this g8 template is based on the default [g8 template](http://github.com/n8han/giter8.g8) and the project generated by [jberkel](http://github/jberkel)'s [android-plugin](http://github.com/jberkel/android-plugin)
