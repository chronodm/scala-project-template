# scala-project-template

A skeletal Scala/Gradle project. It includes Scala, ScalaTest, JUnit, [Mockito](http://mockito.org/), and the [gradle-scalatest](https://github.com/maiflai/gradle-scalatest) plugin, as well as [Log4J 1.2](http://wiki.apache.org/logging/log4j1) and a console-only [log4j.xml](src/test/resources/log4j.xml) for testing. 

## Installation

1. create the new repository and copy its URL, e.g. `https://github.com/chronodm/new-project.git`

2. create a 'bare clone' of this this project:

    ```
    git clone --bare https://github.com/chronodm/scala-project-template
    ```

3. cd to the bare clone:

    ```
    cd scala-project-template.git
    ```

4. mirror-push to the new repository

    ```
    git push --mirror https://github.com/chronodm/new-project.git
    ```

5. remove the `scala-project-template.git` directory

    ```
    cd ..; rm -rf scala-project-template.git
    ```

6. clone the new repository and CD to the new directory:

    ```
    git clone https://github.com/chronodm/new-project.git

    cd new-project
    ```
7. remove or edit this README file.
8. edit `build.gradle` to update versions, if you feel like it
9. edit `settings.gradle` file to set the root project name
10. check that everything's working:

    ```
    ./gradlew check
    ```

11. start coding!
