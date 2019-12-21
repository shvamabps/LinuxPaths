# Spark Path

```
sudo vi ~/.bashrc
```

- this file is in `/home/{{ $user }}`
- this will show the basic contents of the file

  - now what needs to be added for setting path for spark:

    - As spark requires both hadoop and jdk
      so we need to set environment for both jdk and hadoop first and then **Spark** path

    ```
       export JAVA_HOME=/opt/jdk
       export HADOOP_HOME=/opt/hadoop
       export SPARK_HOME=/opt/spark24
       PATH=$JAVA_HOME/bin:$HADOOP_HOME/bin:$HADOOP_HOME/sbin:$SPARK_HOME/bin:$PATH
       export PATH
    ```
