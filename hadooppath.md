# Hadoop Path

```
sudo vi ~/.bashrc
```

- this file is in `/home/{{ $user }}`
- this will show the basic contents of the file

  - now what needs to be added for setting path for hadoop :

    - As hadoop requires java als, so the path for jdk will also be used for setting environment for **Hadoop**
      ```
      export JAVA_HOME=/opt/jdk
      export HADOOP_HOME=/opt/hadoop
      PATH=$JAVA_HOME/bin:$HADOOP_HOME/bin:$HADOOP_HOME/sbin:$PATH
      export PATH
      ```
