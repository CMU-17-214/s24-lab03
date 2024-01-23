# Testing Infrastructure in Java

This repository is set up for testing with _JUnit_ and test coverage with _Jacoco_, both automated through _Maven_.

You will likely want to explore IDE integration for test execution and coverage in your IDE, but also ensure that tests still execute with Maven in a Continuous Integration environment (e.g. github actions).

The following commands might be useful:
* `mvn clean` reset the build
* `mvn test` execute tests and write a test coverage report in `target/site/jacoco/index.html`
* `mvn site` build and test the project and write results in `target/site/index.html` (includes coverage and test results)

See the comments in `pom.xml` for technical details of this setup.
