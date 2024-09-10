MapReduce job to count models of different makes of vehicles. Display the top 5makes.


How to run Program.java:
	javac Program.java
	jar cfe Program.jar Program *.class
	export HADOOP_CLASSPATH=Program.jar
	hadoop Program [input csv file address] [output folder address]
	*you should specify exact output folder address. (the folder should not exist. the hadoop will create the new folder).
	
