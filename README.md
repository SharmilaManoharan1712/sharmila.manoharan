# sharmila.manoharan

You are given a requirement which states
The system should scale to 2000 users
What other questions would you need to ask in order to get enough information to create a
workload model.

get the nonfunctional requirements from the team and get the below details

Number of users
Iteration per hour 
End to End Response Time /SLA
Number of Transactions
Hits (Requests) per second
Throughput
Individual page response time
user distribution for each scenario
Minimum users at which the application to be tested initially and the number of users to be incremented at specific intervals


2. Please rewrite the requirement above so that it testable and more descriptive.

Test the application by incrementing the users until it reaches a maximum of 2000 users and validate the system performance for scaled up volumes. 

3. As well as creating a script in a tool to do the performance testing, what other factors would
need to be considered for a performance testing engagement?

Below are the major factors to be considered for a performance testing engagement


Identify the impacted components.Risk assess and find the impact of the changes and assess if it warrants a performance test
Gather the non functional requirements and finalise the scope of NFT by conducting NFR workshops with relevant teams
Performance test planning:Identify the performance acceptance criteria: It contains constraints and goals for throughput, response times and resource allocation
Figure out the physical test environment before running the performance testing, like hardware, software and network configuration and compare it with production environment and identify the scalability factor for volumetric purpose
Plan and design Performance tests: Define how usage is likely to vary among end users and find key scenarios to test for all possible use cases, workload mix
Test environment configuration: Before the execution, prepare the testing environment and arranges tools for testing, monitoring, other resources, etc.
Test design implementation: According to your test design, create a performance test script, customize the script and make it reusable and runnable for multiple users
Performance Test Data: Arrange or prepare the sufficient amount of test data considering the data limitations as per the application
Support team engagement for assistance with application issues, DB , test data, environment and all other issues.
