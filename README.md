# hadoop-word-count

mapper, reducer to code to count word, sort, reshuffle, and put it into hdfs /output folder

command:

```
hadoop jar hadoop-streaming-2.4.0.jar -files mapper.py,reducer.py -mapper mapper.py -reducer reducer.py -input /test/demo.txt -output /output
```
