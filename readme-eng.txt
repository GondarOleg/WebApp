Making projects by different builders:
All builders support the standard goals: build (install to maven), clean, test

Features of assembly

Ant

0. manage dependencies using ivy, ivy if not installed - Library pumped, Teasing restart job
1. Purpose resolve downloads required libraries
2. Collects war or jar file (build-jar and the build-war objectives are in line);
3. Artifacts lie in a folder build \ libs
4. Is the purpose of the run, runs the jar to perform (before start performing assembly, displays in the "WebApp !!!!" console)
5. clean-all additional net cash ivy

Maven

1. Standard Targets
2. Artifacts created in the target folder

Gradle

1. Artifacts created in the folder build \ libs
2. Determine the 2 additional jobs myTask1, myTask1
3. Targets embedded in the build process
3.1. myTask1 performed before test
3.2. myTask2 performed before the clean
4. logging test tasks redefined