# Q3SQATest_AnnisaPGC
Report Bugs

ID bugs : 001

Title : error while deleting and then re-entering data; uncalculated outcome, wording appears "ERROR! ENTER A CORRECTLY FORMATTED DATE"

Step to reproduce : 
- login http://www.shino.de/parkcalc/index.php
- Choose a parking lot
- Delete leaving/entry time
- click button calculate
- input leaving/entry time
- Click button calculate

Expected result : 
- When the entry/exit hours are properly input, the fee can be computed.
- Error message missing

Severity : Critical

Priority : High

Attachment : 

<img width="421" alt="error1" src="https://user-images.githubusercontent.com/32071195/176472689-3fe14b9b-4730-4edb-9ff4-0e4d2f427b5d.png">

ID bugs : 002

Title : error while selected parking lot after deleting and then re-entering data; uncalculated outcome, wording appears "ERROR! ENTER A CORRECTLY FORMATTED DATE".

Step to reproduce : 
- login http://www.shino.de/parkcalc/index.php?
- Choose a parking lot
- Delete leaving/entry time
- click button calculate
- input leaving/entry time
- Select another parking lot
- Click button calculate
 
Expected result : 
- When the selected parking lot the fee can be computed.
- error message missing

Severity : Critical
Priority : High

Attachment : 

<img width="426" alt="error2" src="https://user-images.githubusercontent.com/32071195/176476582-68ce34c9-f6f7-4f13-9307-5a4f4a02d080.png">

ID bugs : 003

Title : parking lot back to first selected value after deleting and then re-entering data; uncalculated outcome, wording appears "ERROR! ENTER A CORRECTLY FORMATTED DATE".

Step to reproduce : 
- login http://www.shino.de/parkcalc/index.php?
- Choose a parking lot
- Delete leaving/entry time
- click button calculate
- input leaving/entry time
- Select another parking lot
- Click button calculate
 
Expected result : 
- When the selected parking lot , fee can be computed.
- Parking lot selected successfully
 
Severy : Critical

Priority : High

Attachment : 

<img width="424" alt="error4" src="https://user-images.githubusercontent.com/32071195/176479563-c4471754-4a93-42e7-9828-ada01e040818.png">
