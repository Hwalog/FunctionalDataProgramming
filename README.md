# FunctionalDataProgramming

Two topics need to be created: "iot" (where the data is stored), and "alert" (where alerts are stored).

Folders:
 - "consumer" output the alert
 - "producer" produces the data which is read from the file
 - "spark-scala-streaming" is consuming the data from the "iot" topic to the "alert" topic
 - "storage" is the folder where the data is stored. It uses Hadoop, in a HDFS manner
 - "analytics" is where we analyse the data
 
Additionnaly, you need to change the path in 2 files:
 - in "Main.scala" of "spark-stream-scala", ~ line 52
 - in "Main.scala" of "producer", ~ line 23
 
Hash of the last commit:
commit 7e808d5f963e6c30f42a07bcc92e3509751aba0d (HEAD -> master, origin/master)
