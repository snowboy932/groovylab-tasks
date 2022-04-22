**IMPORTANT!** Please note that **every single** function has to return result
of the calculations, this is crucial for automated testing of your tasks

#### Task 8
`app/src/main/groovy/groovylab/Task08.groovy` - parse input json, find all entries, and return another json
with values where sum of digits in value field equal to 9. Example:
```groovy
Task08.parseAndFilterJson("{\"Kate\":18,\"Alan\":16,\"Osvald\":27}") == "{\"Kate\":18,\"Osvald\":27}"
```