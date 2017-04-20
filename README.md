# HadoopMapReduce Vehicle Accidants Analysis

## Steps followed to create the project:

1. Program written in Java Map Reduce.
2. Mapper reads the data and splits based on ','.
3. Output of mapper is given to combiner, which does the shuffle and sort.
4. Reducer returns the final count.

## How to execute the project:

1. Using "maven package" we can generate the jar file.
2. Run the program using jar file on given dataset
3. Command Used "hadoop jar HadoopTut-0.0.1-SNAPSHOT.jar org.test.WordCount /data/nyc/nyc-traffic.csv wordOutput/output"
