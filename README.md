# Hadoop-Hive
## hadoop
Java home is important to run the hadoop please download java [Click Here](https://www.oracle.com/in/java/technologies/javase/javase-jdk8-downloads.html) .  
While installing allow add path option to add path of java in environmental Variables.  
Then download hadoop from the hadoop [download](https://hadoop.apache.org/releases.html) click the binary file to download.  
After Downloading from the internet extract hadoop-2.7.3.tar.gz use 7-zip to extract.  
#### We have to configure the Core-site.xml,hdfs-site.xml,mapred-site.xml and yarn-site.xml where they located at hadoop/etc/hadoop.
#### Then add file path in environmental variables.
Next, we have to add the Winutils libarary in hadoop/bin so [download kontext-tech winutils from github](https://github.com/kontext-tech/winutils).  
Then run commands 
hadoop -version it shows the java version  
hadoop version it shows the version of the hadoop  
start-all which starts the start-dfs and start-yarn  
if namenode is shutdowns then give
##### hdfs namenode -format
then give start-all in cmd as Adminstrator.  

## Hive
To work with the hive we need hadoop,derby
For this you have to [download](https://db.apache.org/derby/derby_downloads.html) according to java version.  




