# jqwik-starter-gradle-kotlin

Simple examples of how to use [jqwik](https://jqwik.net) with Gradle and Kotlin.

It also uses [AssertJ](https://joel-costigliola.github.io/assertj/) but any
Assertion library (including JUnit Jupiter) will do.

## Running tests

- In IDE of your choice that has JUnit5 platform support, e.g. IntelliJ IDEA.
- Using gradle: `./gradlew test`

## Configuration

Jqwik's
[configuration file](https://jqwik.net/docs/current/user-guide.html#jqwik-configuration)
is located in `/src/test/resources/junit-platform.properties`

You probably want to add the database name (default is `jqwik-database`)
to your `.gitignore` file.
