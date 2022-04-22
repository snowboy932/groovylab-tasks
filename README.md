**IMPORTANT!** Please note that **every single** function has to return result
of the calculations, this is crucial for automated testing of your tasks

#### Calculator
`app/src/main/groovy/groovylab/TaskCalculator.groovy` - function `int exec(string)`, calculate input
expression. Example:
```groovy
TaskCalculator.exec("6(3+1)") == 24
TaskCalculator.exec("1+9/3") == 4
```