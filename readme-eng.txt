Making projects by different builders:

(Builder must be previously installed)

Features of assembly

Ant

Run in the project directory

0. manage dependencies using ivy, ivy if not installed - Library pumped, Teasing restart job
1. Purpose resolve downloads required libraries
2. Collects war or jar file (build-jar and the build-war objectives are in line);
3. Artifacts lie in a folder build \ libs
4. Is the purpose of the run, runs the jar to perform (before start performing assembly, displays in the "WebApp !!!!" console)
5. clean-all additional net cash ivy

ant clean - clean assembly
ant install-ivy - ivy set
ant resolve - resolve dependencies
ant resources - to copy the files to the classpath
ant compile - compile
ant compile-tests - tests to compile
ant test - perform tests
ant build-jar - create a jar file
ant build-war - to create a war file
ant clean - clean the collected files
ant clean-all - in addition to clear the cache ivy

Maven

Run in the project directory

1. Standard Targets
2. Artifacts created in the target folder

mvn test - Tests
mvn install - collect files
mvn clean - clean assembly files

Gradle

Run in the project directory

1. Artifacts created in the folder build \ libs
2. Determine the 2 additional jobs myTask1, myTask1
3. Targets embedded in the build process
3.1. myTask1 performed before test
3.2. myTask2 performed before the clean
4. logging test tasks redefined

gradle test - test run
gradle build - collect files
gradle clean - clean
gradle myTask1 - my first task for Gradle
gradle myTask2 - my second task for Gradle