# flink-scala-experiments


- docker pull flink

## Packaging
In IntelliJ, go to Maven tab, and click on 'package'

Once you have the artifact ("_flink-scala-wc-1.0-SNAPSHOT.jar_"), you can submit it in Flink:

Example:
```./bin/flink run flink-scala-wc-1.0-SNAPSHOT.jar --input data.txt```


### References
https://naiveskill.com/flink-wordcount-scala/