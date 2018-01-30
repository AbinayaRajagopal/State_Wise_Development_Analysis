# State_Wise_Development_Analysis

Step 1:
Copy dataset from local file system to HDFS using flume.
Note: use the conf file by downloading from below link.
Click here to download
Command:
flume-agent agent –n agent1 –c conf –f <path to filecopy.conf>

Step 2:
Input file is in the XML format use Map reduce or pig to parse the data and get the results for
the below problem statements.
4. Problem statement
1. Find out the districts who achieved 100 percent objective in BPL cards
Export the results to mysql using sqoop
2. Write a Pig UDF to filter the districts which have reached 80% of objectives of BPL cards.
Export the results to MySQL using Sqoop.
