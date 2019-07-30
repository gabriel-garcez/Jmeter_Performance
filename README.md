# Jmeter_Performance
Framework for load tests in Jmeter

The framework contains:

1. Defined Variables to use it in different environments
2. Token Generator
3. CSV Data Config
4. If controlers to get different payloads
5. Response Assertions

Most details in the CSV File

To Run the framework by command line:

jmeter -t Test_Plan.jmx Jthread=30 Jcount=30 Jrumpup=30 -l report.xml

SET
Thread: Number of users connects to the target website
Count: Number of time to execute testing
RumUp: Nunber of executions by each user


Obs: Set Jmeter in the environment variables, configure the jmx with the proper credentials and populate CSV with the data test

