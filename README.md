## ISO8583 Library

It is based on JPOS. 


### Build an eclipse project
````
gradle eclipse
````

### Build an IDEA project
````
gradle idea
````

### Build your own jar
````
gradle jar
````

### Check the jPOS version
````
gradle version
````

### Create a distribution of your application
````
gradle dist
````
This creates a tar gzipped file in the `build/distributions` directory.

### Install application in 'build/install' directory
````
gradle installApp
````
Installs application in `build/install` with everything you need to run jPOS. Once the directory is created, you can `cd build/install` and call `java -jar your-project-version.jar` or the `bin/q2` (or `q2.bat`) script available in the `bin` directory.

### Generate an install a Maven artifact
````
gradle install
````

### List available Gradle tasks
````
gradle tasks
````

