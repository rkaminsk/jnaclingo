This is a small prototype to show how to provide the [clingo](https://potassco.org/clingo) API using [JNA](https://github.com/java-native-access/jna).
Check out [jclingo](https://github.com/kherud/jclingo) for a full-featured clingo Java API.

# Small example to use clingo with JNA

```bash
$ mvn package
...
$ java -jar target/example-1.0-SNAPSHOT-jar-with-dependencies.jar
clingo version: 5.5.0
model: 2
ANSWER: a b
```
