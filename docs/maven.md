#execute one file
mvn -Dtest=examples.Lambda test
#execute one java file
mvn exec:java -Dexec.mainClass="stack.overflow.Main2"
