Gradle Copy Failure on Windows
==============================

This build demonstrates what appears to be a Gradle bug. If you create a Copy task that copies into the project directory, running said task on Windows results in an exception.

To run, just execute the following on Windows:

    gradlew fail


