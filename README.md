# Remove stop words in Java

This is a simple Spring Boot project which removes stop words from a text file.

# The resource files

There are two resource files:
1. A file with a collection of stop words, with each line having one stop word.
2. A file with a sample essay, taken from this [source](https://www.apstudynotes.org/english/sample-essays/definition-success/).

# Building the project

Once you clone this repo, ```cd``` into the project root directory and run the following command to compile and 
build this maven project:

```shell script
mvn clean install
````

Once you run this command, Maven will build the project and keep it in the ```/target``` directory in the project 
root directory. You can run the program using the command below:

```shell script
java -jar target/RemoveStopWordsInJavaPOC-1.0-SNAPSHOT.jar
```