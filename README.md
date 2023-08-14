# Wiegand-Keypad-V4
Wiegand Updated Keypad
User codes have to be 4 digits
Master code has to be 6 digits


Factory master code should be 123456
to change master code, ender the master code twice and then enter a new master code. 
(#) has to be used after the end of every code entered.

example 123456# 123456# 654321# = new code is 654321
admin can add one code and four tags. 
to add admin code:
(master code)# 9000#, then new code 
example 654321#, 9000#, 1234#, new admin code is 1234
tags are the same but change the 9000 out for 9001, 9002, 9003, 9004. 
example 654321#, 9001#, scan new tag, then new tag is saved. 

there are 12 other users. 
user one is (master code)# 1001#, then new code. all the way to 1012# for users 1-12. 
tags are simular exccept 1001-1012 is changes out to 2001-2012. 


There is a lock out for uses 3-12. enter the master code# then 1111#. this will toggle access for users 3-12. 


This can of course all be set in the UI. 

use the select to pick the code you want to enter and enter it. 
