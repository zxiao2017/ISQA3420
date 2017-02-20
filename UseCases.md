##Use Case 1<br>
Title: Developer Determine License and Vulnerability<br>
Primary Actor: Developer<br>
Goal in Context: Scan all external software package. Check package license information and gather vulnerability information from NIST vulnerability database<br>
Stakeholders: Developer / Manager<br>
Preconditions: Developer is able to evaluate the software package's license information from FOSSOLOGY scanner and vulnerability information by using NIST vulnerability database before implementing the package in the project<br>
Main Success Scenario: Developer check the software package license and vulnerability information and make sure that is valid before implementation<br>
Failed End Conditions: Developer receives invalid license and vulnerability information<br>
Trigger: Developer receives external software package<br>

##Use Case 2<br>
Title: Manager Check package Policy<br>
Primary Actor: Manager<br>
Goal in Context: The manager is able to check all the license and vulnerability policy information and be able to edit/create policy in policy database<br>
Stakeholders: Manager / Developer<br>
Preconditions: Relevant file/package information is in the License and Vulnerability database / All the policy information is in the Policy database<br>
Main Success Scenario: Manager receives correct license and vulnerability information, and manager is able to retrieve policy from the policy database<br>
Failed End Conditions: Manager cannot retrieve package policy information from policy database<br>
Trigger: Manager retrieve software package policy information from policy database<br>

##Use Case 3<br>
Title: Developer Retrieve License and Vulnerability<br>
Primary Actor: Developer<br>
Goal in Context: Developer is able to retrieve all of the software package license and vulnerability result from license and vulnerability database<br>
Stakeholders: Developer / Manager<br>
Preconditions: Developer has the authority to access license and vulnerability database<br>
Main Success: The software package license and vulnerability information is stored in the license and vulnerability database<br>
Failed End Condition: The software package that developer retrieved is not excess in license and vulnerability database<br>
Trigger: Developer wants to retrieve software pakcage<br>
