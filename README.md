# spark-scala-project

## Apache Spark

https://spark.apache.org/

## Build

### Maven
```
$ mvn clean package

```

scalastyle:
```
$ mvn scalastyle:check 

```

### SBT

TBD

## Unit Testing

Refs:
 - https://github.com/bosea/spark-unit-testing
 - https://dzone.com/articles/testing-spark-code
 - https://stackoverflow.com/questions/44536150/how-do-i-use-spark-testing-base-with-maven


## Release a new version

```
mvn versions:set -DnewVersion=X.Y.Z -DgenerateBackupPoms=false
git commit -m "Prepare release X.Y.Z" -a
git tag -a X.Y.Z -a "A useful comment here"
git push
git push --tags
```

