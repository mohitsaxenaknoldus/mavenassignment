Maven Assignment Group 1

Modules:

-assign
  -cal-api
  -cal-impl
  
Plugins:

-checkstyle
-spotbugs
-maven assembly
-maven compiler
-maven dependency

How to run:

1) Clone the repo.
2) Inside group1 folder, run this: mvn clean compile assembly:single
3) Inside cal-impl folder, run this to execute the jar: java -cp target/<jar_file_name> Application
