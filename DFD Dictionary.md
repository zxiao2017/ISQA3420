##Entities<br>
Developer - Internal developer to the organization<br>
Manager - Internal manager to the organization and has the authority to control the project<br>

##Processes<br>
OSS Check - The process organize the package that being sent to NIST Vulnerability Database and Scan for package license<br><br>
Scanner - The process is to scan all the package that has been sent for check license valiability<br>
Retrieve License & Vulnerability - This process is to retrieve package license and vulnerability information from license and vulnerability database<br>
Retrieve Policy - retrieve all the policy information from policy database<br>
Set Policy - Manager can modify, edit or create policy to policy database through this process<br>

##Data Stores<br>
NIST Vulnerability DB - The data store contains software vulnerability information that allows people send package to check vulnerability information<br>
License & Vulnerability DB - All of the packages checked results needs to be stored in this database and use for internally in this organization<br>
Policy DB - The database which contains the policies for project vulnerabilities<br>

## Data Flows<br>
Software Package - Software package information that being sent from developer<br>
Software Package Name - The name of the package that being sent to NIST Vulnerability Database<br>
Vulnerability Result - The checked result of the package from NIST Vulnerability Database<br>
Scan Result - License information result from Scanner<br>
Vulnerability & License Request - A package vulnerability & License Request from Developer or Manager<br>
Vulnerability & License Result - The package vulnerability & License information result from License & Vulnerability Database<br>
Policy Request - Policy information request that being sent from manager<br>
Policy Information - Package policy information from Policy Database<br>
Policy Edit/Create - Policy changes that are made by manager<br>
