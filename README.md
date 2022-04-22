**IMPORTANT!** Please note that **every single** function has to return result
of the calculations, this is crucial for automated testing of your tasks

#### Task 11
`app/src/main/groovy/groovylab/Task11.groovy` - you need to insert first input string inside the brackets,
near the number, which equals to the second input parameter (string to be used
as default - `"1() 2() 3()"`). Example:
```groovy
Task11.gstring("test", 2) == "1() 2(test) 3()"
```