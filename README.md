# Groovy lab

## How to run and test your code

In this repo there's a docker-compose file with gradle image. To run container,
run in your terminal:
```bash
docker-compose run gradle
```
In this container you can run and test your code. The recommended flow it to
edit `app/src/main/groovy/groovylab/App.groovy` file and then run
```bash
gradle run
```
in the container.

Example of `app/src/main/groovy/groovylab/App.groovy`:
```groovy
package groovylab

class App {
    static void main(String[] args) {
        println "hello world"
    }
}
```
