Use Case 1<br>
Title: Developer Determine License and Vulnerability<br>
Primary Actor: Developer<br>
Goal in Context: Scan all external software package. Check package license information and gather vulnerability information from NIST vulnerability database<br>
Stakeholders: Developer / Manager<br>
Preconditions: Developer is able to evaluate the software package's license information from FOSSOLOGY scanner and vulnerability information by using NIST vulnerability database before implementing the package in the project<br>
Main Sucess Scenario: Developer check the software package license and vulnerability information and make sure that is valid before implementation<br>
Failed End Conditions: Developer receives invalid license and vulnerability information<br>
Trigger: Developer receives external software package<br>

Use Case 2<br>
Title: Manager Check package Policy<br>
Primary Actor: Manager<br>
Goal in Context: The manager is able to check all the license and vulnerability policy information and be able to edit/create policy in policy database<br>
Stakeholders: Manager / Developer<br>
Preconditions: Relevant file/package information is in the License and Vulnerability database / All the policy information is in the Policy database<br>
Main Sucess Scenario: manager receives correct license and vulnerability information, and manager is able to retrieve policy from the policy database<br>
Failed End Conditions: Manager cannot retrieve package policy information from policy database<br>
Trigger: manager retrieve software package policy information from policy database<br>

Use Case 3<br>
