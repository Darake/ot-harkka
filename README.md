# Deadlines Begone    

This application helps with keeping track of ongoing courses and their deadlines. With this application it's possible to quickly see all the undone assignments and to keep track of assignments done for a course. All assignments are ordered by their deadlines.  

## Documentation  
[Instructions](https://github.com/Darake/deadlines-begone/blob/master/documentation/instructions.md)  

[Software requirements specification](https://github.com/Darake/deadlines-begone/blob/master/documentation/Software%20requirements%20specification.md) 

[Architecture](https://github.com/Darake/deadlines-begone/blob/master/documentation/architecture.md)  

[Testing](https://github.com/Darake/deadlines-begone/blob/master/documentation/testing.md)  

[Timesheet](https://github.com/Darake/deadlines-begone/blob/master/documentation/timesheet.md)  

## Releases  
[Week 5](https://github.com/Darake/deadlines-begone/releases/tag/week5)  
[Week 6](https://github.com/Darake/deadlines-begone/releases/tag/week6)  
[Final release](https://github.com/Darake/deadlines-begone/releases/tag/1.0)  

## Terminal commands  

### Testing  
Run tests with the following command  

```mvn test```  

Code coverage report for tests can be created with  

```mvn jacoco:report```  

Code coverage can be viewed by opening target/site/jacoco/index.html with a browser  

### Generating an executable jar  

```mvn package```  

Jar can be found in the target directory  

### Checkstyle  

Checkstyle report can be generated with  

```mvn jxr:jxr checkstyle:checkstyle```  

Report can be found in target/site/checkstyle.html  

### JavaDoc  

JavaDox can be generated with the following command  

``` mvn javadoc:javadox ```  

The generated file can be found in target/site/apidocs/index.html
