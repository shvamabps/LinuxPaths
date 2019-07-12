# JAVA path




```
sudo vi ~/.bashrc
```
* this directory is in  ```/home/{{user}}``` 
* this will show the basic contents of the file

    * now what needs to be added for setting path for **JAVA**

     ```
            export JAVA_HOME=/opt/jdk
            PATH=$JAVA_HOME/bin:$PATH
            export PATH
     ```