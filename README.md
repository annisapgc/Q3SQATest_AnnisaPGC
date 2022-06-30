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
- login http://www.shino.de/parkcalc/index.php
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
- login http://www.shino.de/parkcalc/index.php
- Choose a parking lot
- Delete leaving/entry time
- click button calculate
- input leaving/entry time
- Select another parking lot
- Click button calculate
 
Expected result : 
- When the selected parking lot , fee can be computed.
- Parking lot selected successfully
- error message missing
 
Severy : Critical

Priority : High

Attachment : 

<img width="424" alt="error4" src="https://user-images.githubusercontent.com/32071195/176479563-c4471754-4a93-42e7-9828-ada01e040818.png">

ID bugs : 004

Title : AM/PM in entry/leave time back to first selected value after deleting and then re-entering time; uncalculated outcome, wording appears "ERROR! ENTER A CORRECTLY FORMATTED DATE".

Step to reproduce : 
- login http://www.shino.de/parkcalc/index.php
- Choose a parking lot
- Delete leaving/entry time
- click button calculate
- update AM-PM/PM-AM
- Click button calculate

Expected result : 
- appropriate choice time type (AM/PM)
- fee can be computed.
- Parking lot selected successfully
- error message missing
 
Severy : Critical

Priority : High

Attachment :

<img width="418" alt="error5" src="https://user-images.githubusercontent.com/32071195/176481771-d465c7f4-3e87-45cc-b2ea-f235a40b03a7.png">

ID bugs : 005

Title : data is not reset when refresh

Step to reproduce :

- login http://www.shino.de/parkcalc/index.php
- Choose a parking lot
- input entry date and time
- input leaving date and time
- click button calculate

Expected result :

data reset

Severy : Medium

Priority : Medium

Attachment :

<img width="417" alt="error6" src="https://user-images.githubusercontent.com/32071195/176730463-75e3b5bc-60eb-43c1-bc2a-e481394a4b88.png">

ID bugs : 006

Title : Invalid time format

Step to reproduce :

- login http://www.shino.de/parkcalc/index.php
- Choose a parking lot
- Input entry date and time 6/30/2022 15:00 AM

Expected result :

AM and PM only until 12

Severy : Critical

Priority : High

Attachment :

<img width="414" alt="error8" src="https://user-images.githubusercontent.com/32071195/176733403-27e73b58-0aba-4b90-8436-1df4b898d3e5.png">

ID bugs : 007

Title : 

calculation result appears when clock in > clock out in the same day and time (AM)

Step to reproduce :

- Login http://www.shino.de/parkcalc/index.php
- Choose a parking lot
- Input entry date and time 7/1/2022 12:00 AM
- Input leaving date and time 7/1/2022 10:00 AM

Expected result :

Estimate parking costs does not appear

Severy : Critical

Priority : High

Attachment :

<img width="415" alt="error11" src="https://user-images.githubusercontent.com/32071195/176737357-b041e9b8-dee5-4afd-a721-ad262a47b2f4.png">


