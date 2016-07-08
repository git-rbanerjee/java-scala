# Spark Mixed Scala/Java maven project

This is a sample project with Maven which contains both Scala and Java code for Apache Spark.
It is using the [scala-maven-plugin](https://github.com/davidB/scala-maven-plugin). 
[Here](http://davidb.github.io/scala-maven-plugin/plugin-info.html) is the set of possible goals.


To Run : spark-submit --class WordCount --master yarn-cluster /home/cloudera/sampleMixedScalaJavaMavenProject/target/scala-java-spark-1.0-SNAPSHOT-jar-with-dependencies.jar /test.csv /op
 
 
