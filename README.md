# 100 Module Gradle Sample

This project has a task called `createModules` that generates 100 modules with a single test inside each project.

This is used for benchmarking test JVM startup times.

Run as follows:

    $ gradle createModules
    $ gradle clean test
