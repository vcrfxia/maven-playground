# Scratch space for testing Maven behaviors

Barebones setup of a parent with three child modules: A, B, and C. Module C depends on A and B.

Build with `mvn install` and run with `mvn exec:java -pl mp-c -Dexec.mainClass="space.scratch.maven.C"`
to see the message `Code is: A B` logged to the console.
