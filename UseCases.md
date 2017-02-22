##Use Case 1<br>
Title: Developer Determine License and Vulnerability<br>
Primary Actor: Developer<br>
Goal in Context: Scan all external software package. Check package license information and gather vulnerability information from NIST vulnerability database<br>
Stakeholders: Developer / Manager<br>
Preconditions: Developer is able to evaluate the software package's license information from FOSSOLOGY scanner and vulnerability information by using NIST vulnerability database before implementing the package in the project<br>
Main Success Scenario: Developer check the software package license and vulnerability information validity<br>
Failed End Conditions: Developer receives invalid license and vulnerability information<br>
Trigger: Developer check the package<br>

##Use Case 2<br>
Title: Manager Check Package Policy<br>
Primary Actor: Manager<br>
Goal in Context: The manager is able to check the package policy information and be able to edit/create policy in policy database<br>
Stakeholders: Manager<br>
Preconditions: Relevant policy information is in the policy database<br>
Main Success Scenario: Manager is able to retrieve correct policy from the policy database<br>
Failed End Conditions: Manager cannot retrieve package policy information from policy database<br>
Trigger: Manager retrieve software package policy information from policy database<br>

##Use Case 3<br>
Title: Developer Retrieve License and Vulnerability<br>
Primary Actor: Developer<br>
Goal in Context: Developer is able to retrieve all of the software package license and vulnerability result from license and vulnerability database<br>
Stakeholders: Developer<br>
Preconditions: Developer has the authority to access license and vulnerability database / Developer wants to check package license and vulnerability information<br>
Main Success: The software package license and vulnerability information is stored in the license and vulnerability database<br>
Failed End Condition: Developer does not have the access permission to the license and vulnerability database<br>
Trigger: Developer upload the name of the package to which license and vulnerability is request<br>
