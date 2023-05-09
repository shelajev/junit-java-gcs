# junit-java-gcs

Example project showing how you can use a Parametrized JUnit 5 test with [Testcontainers](testcontainers.com) to check which GC your JVM picks under certain memory constraints: 

To run: 
```
mvn test
``` 


The test is pretty elegant, check the code at [JavaGCsTest](https://github.com/shelajev/junit-java-gcs/blob/main/src/test/java/org/shelajev/JavaGCsTest.java) 

![Screenshot of the test](https://user-images.githubusercontent.com/426039/237157399-222cc2c9-ce14-4a94-bf58-13adbd2ccd7c.png)

