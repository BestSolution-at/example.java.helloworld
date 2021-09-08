example.java.helloworld
=======================

This is "Hello World" Example for Java.

The structure ``helloworld`` package is like this: ::

  example.java.helloworld/
  |-- helloworld
  |   `-- Main.java
  |-- LICENSE
  |-- Manifest.txt
  `-- README.md

Compile class
-------------

For compile the main class for package, execute the follow command: ::

  javac helloworld/Main.java

This generate the ``Main.class`` file into ``helloworld`` directory.

Run class
---------

For run the main class for package, execute the follow command: ::

  java -cp . helloworld.Main

This show the ``Hello world`` message.

Create a JAR file
-----------------

For pack the main class for package as a JAR file, execute the follow command: ::

  jar cfme Main.jar Manifest.txt helloworld.Main helloworld/Main.class


Run a JAR file
--------------

For run the JAR file packed, execute the follow command: ::

  java -jar Main.jar

This show the ``Hello world`` message.

Reference
=========

- `java - How to run a JAR file - Stack Overflow <http://stackoverflow.com/questions/1238145/how-to-run-a-jar-file>`_.

- `Setting an Application's Entry Point (The Java™ Tutorials > Deployment > Packaging Programs in JAR Files) <http://docs.oracle.com/javase/tutorial/deployment/jar/appman.html>`_.
