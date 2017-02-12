Use Case 1<br>
Title: Developer Determine License and Vulnerability<br>
Primary Actor: Developer<br>
Goal in Context: Scan all external software package and gather vulnerability information from NIST vulnerability database<br>
Stakeholders: Developer / Manager<br>
Preconditions: Developer is able to evaluate the software package's vulnerability and license information by using NIST vulnerability database before implementing the package in the project<br>
Main Sucess Scenario: Developer checked the software package license and vulnerability and make sure that is valid before implementation<br>
Failed End Conditions: Developer uses invalid license and vulnerability information for the project<br>
Trigger: Developer upload an external software package<br>

Use Case 2<br>
Title: Corporate Manager Determine the Risk of External Source<br>
Primary Actor: Corporate Manager<br>
Goal in Context: The corporate manager is able to check license and vulnerability information that provided from developers<br>
Stakeholders: Corporate Manager / Developer / Project Owner<br>
Preconditions: Relevant file/package information is in the SPDX database / Necessary information has been provided<br>
Main Sucess Scenario: Corporate manager receives correct license and vulnerability information for the project<br>
Failed End Conditions: Corporate manager receives invalid license and vulnerability project package<br>
Trigger: Corporate manager uploads project information with license and vulnerability information<br>
