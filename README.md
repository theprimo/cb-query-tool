# cb-query-tool

Tool which connects to couchbase database, executes the given n1ql query and writes the query output to a csv file

Required files:
1.CBQueryTool.jar - executable jar file which contains the code to perform the task 
2.config.properties - input configuration properties
3.InputQuery.sql - input n1ql query file

Output file:
1. On successful execution of the query, we'll see the result csv ResultCsv.csv in the same location

How to run:
Keep the required 3 files in a single directory and open the cmd from here and execute below commnad
java -jar CBQueryTool.jar

Future updates:
Code currently uses ConnectReadFromCBv2.java file
Please upgrade the version in case of future updates

Please note:
1.Provide the input n1ql query in a single line, also use single quotes instead of double quotes
2.Take case of input configuration properties, provide proper values

