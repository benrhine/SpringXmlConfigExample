SpringXmlConfigExample
======================

A Simple Spring MVC application with XML configuration and a complete test suite

For me this is more of a memory aide as well as a learning tool.  I wanted to have a fully tested, template web application to jump start any future projects for work as well as being able to easily reference things that I have learned or just want to remember.  This will be the first template program in a series I am working on in my free time, I hope to soon have four of these examples.

Spring MVC with XML Config                                                                                                
Spring MVC with Java Config                                                                                               
Spring MVC with Groovy on Grails                                                                                          
Spring MVC with Scala                                                                                                           
Spring MVC with XML Config  
=======================
For the xml based config I have the servlet configured as 2.4 as servlet 2.4 is the highest version that will still run on a Tomcat 5.5 container as well as JSTL 1.1.2 (I will be updating these in another example). At the time of writing this cobertura shows by test coverage to be around 94% of all lines of code combining my JUnit 4 tests with my integration tests.

Tested Containers:
-----------------
Tomcat 5.5.28                                                                                                       
Tomcat 6.0.36                                                                                                           
Tomcat 7.0.37                                                                                                         
Jetty  8.1.12.v20130726                                                                                               

The later three are all runable from the maven plugin and jave been configured with a JNDI datasource. Use the commands
mvn tomcat6:run, mvn tomcat7:run or mvn jetty:run.

Tested Compilers:
-----------------
Maven 3.0.5                                                                                                             
Maven 3.1.0

Builds and runs tests with either version without issue.
