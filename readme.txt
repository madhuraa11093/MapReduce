1.	Instructions to run the app in non-Hadoop environment:
•	Include the command below command in the source code as shown in the picture.
File file = new File(“path of folder in your system”) 
 
•	We need to have a “retailsales” with a .java extension.
•	Convert into .class file by compiling it using “javac retailsales.java” command.
•	Use “java retailsales” to execute the code on single system environment.
•	Output is shown in the console.

2.	Instructions to run the app in Hadoop environment:
•	Upload the data set and the .jar file of “retailsales” in S3 bucket of AWS.
•	Create the instances of EC2 in amazon.
“hadoop jar retailsales.jar RetailSales /InputFilepath/input /OutputFilePath/output
•	” on EMR console to execute the .jar file in Hadoop environment.
