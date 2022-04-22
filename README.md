**IMPORTANT!** Please note that **every single** function has to return result
of the calculations, this is crucial for automated testing of your tasks

#### Task 7
`app/src/main/groovy/groovylab/Task07.groovy` - you need to encrypt input string. Conditions:
- string is a space separated words
- you need to encrypt each word using following rules:
  * The first letter needs to be converted to its ASCII code
  * The second letter needs to be switched with the last letter
Example:
```groovy
Task07.encryptThis("Hello") == "72olle"
Task07.encryptThis("hello world") == "104olle 119drlo"
```