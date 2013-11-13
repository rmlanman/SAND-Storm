SAND-Storm
==========

Topology for SAND on Storm

Notes
==========
Add all python modules to the multilang/resources directory

The main line for the code is located in the default java package, to execute it using maven 

```
mvn -f m2-pom.xml compile exec:java -Dexec.classpathScope=compile -Dexec.mainClass=storm.starter.WordCountTopology
```
