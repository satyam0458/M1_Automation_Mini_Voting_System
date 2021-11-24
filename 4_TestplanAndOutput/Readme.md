# Test Cases

|S no|	Test Case|	Description|	Ex i/p|	Output|	Status|
|-----| -------------|-----------------|----------|----------|------------|
|1	|	    |Login_1|	Enter wrong Username|	Admin|	Wrong username or password|
|2|	Login_2|	Enter Correct Username|	Admin|	Logged in successfully|	Pass|
|3|	Option:1|	New election initiation|	2019|     |    |	
| |   |   |   branch code-btecs|    |      |		
| |   |   | roll no-100|	Saving files|   |	
| |   |   | no of candidates-2|	Created files successfully|	Pass|
| |   |   | name of candidate 1-ketan|   |		
| |   |   | name of candidate 2- Rithik|   |		
|4|	Login_3|	Enter wrong UserId|	2019btecs00064|	Invalid userID|	Fail|
|5|	Login_4|	Enter correct UserID|	2019btecs00042|	Candidates for election|	Pass|
| |   |   |   |1.ketan|	  |
| |   |   |   |2.Rithik	|   |
| |   |   |    |Your note(enter no.)|   |

StepIN_VaccineRegist
High Level Test Plan
Test ID	Description	Input	Expected output	Actual Output
01	Check patient registration status	123 (aadhar no)	{-1}	(not found)
02	Check patient registration status	123 (aadhar no)	{0,1}	(found)
03	Check patient vaccination status	3 (patient id)	{>0}	(vaccinated)
Low Level Test Plan
Test ID	Description	Input	Expected output	Actual Output
01	Check patient registration status	125 (aadhar no)	0	0 (registered, not vaccinated)
02	Check patient registration status	130 (aadhar no)	1	1 (registered, vaccinated)
03	Check patient vaccination status	3 (patient id)	1	1 (first dose)
04	Check patient vaccination status	3 (patient id)	2	2 (second dose)
05	Check patient vaccination status	3 (patient id)	3	3 (already vaccinated)
