TEST CASE 1
Test Case ID:TC_CAL_001
Test Description:Verify addition of two positive integers
preconditions:Calculator app should be open
Test Steps:
1.press 10 in the  input field
2.press the addition (+)operator
3.press 20 in the  input field
3.press on the Equal(=)button
Expected Result:
The calculator should dispaly the result as 30

TEST CASE 2
Test Case ID:TC_CAL_002
Test Description:Verify subtraction of two positive integers
preconditions:Calculator app should be open
Test Steps:
1.Enter 10 in the  input field
2.Select the -(subtraction)operator
3.Enter 5 in the  input field
4.click on the equal button
Expected Result:
The result should be 5 (because 10 - 5 =5)

TEST CASE 3
Test Case ID:TC_CAL_003
Test Description:Verify multiplication using positive values
preconditions:Calculator app should be open
Test Steps:
1.Enter 9
2.Select the *(multiplication)operator
3.Enter 4
4.Tap the equals button
Expected Result:output should be 36  as 9*4 is 36

TEST CASE 4
Test Case ID:TC_CAL_004
Test Description:Verify division operator with positive numbers
Preconditions:Calculator should be open
Test Steps:
1.Enter 20
2.select/(division)
3.Enter 5
4.Tap the equals button
Expected Result:
output should be 4 as 5*4 20 and 20 divided by 5 is 4

TEST CASE 5
Test Case ID:TC_CAL_005
Test Description:Verify addition of negative integers
preconditions:Calculator app should be open
Test Steps:
1.Enter -10 in the  input field
2.Select the addition (+)operator
3.Enter 20 in the second input field
3.click on the Calculate/Equal(=)button
Expected Result:
The calculator should dispaly the result as 10

TEST CASE 6
Test Case ID:TC_CAL_006
Test Description:Verify subtraction of negative integers
preconditions:Calculator app should be open
Test Steps:
1.Enter -10 in the  input field
2.Select the -(subtraction)operator
3.Enter 5 in the  input field
4.click on the equal button
Expected Result:
The result should be -15 (because -10 - 5 =-15)

TEST CASE 7
Test Case ID:TC_CAL_007
Test Description:Verify multiplication using negative values
preconditions:Calculator app should be open
Test Steps:
1.Enter -9
2.Select the *(multiplication)operator
3.Enter 4
4.Tap the equals button
Expected Result:output should be -36  as -9*4 is -36

TEST CASE 8
Test Case ID:TC_CAL_008
Test Description:Verify division operator with negative numbers
Preconditions:Calculator should be open
Test Steps:
1.Enter -20
2.select/(division)
3.Enter 5
4.Tap the equals button
Expected Result:
output should be -4 as 5*4=20 and -20 divided by 5 is -4

TEST CASE 9
Test Case ID:TC_CAL_009
Test Description:Verify BODMAS operation without brackets if multi-input expression is allowed
Preconditions:Calculator supports expressions
Test Steps:
1.Enter 2+3*4
2.press equal
Expected Result:
Result should should be 20 as 2+3=5 and 5*4 is 20
NOTE:The given calculator does not support Bodmas rule.

TEST CASE 10
Test Case ID:TC_CAL_010
Test Description:Verify division by zero
Preconditions:None
Test Steps:
1.press 5
2.press division button
3.press 0
4.Click the equals button
Expected Result:
App should show an error message such as "Cannot divide by Zero"or "Infinity"

TEST CASE 11
Test Case ID:TC_CAL_011
Test Description:Verify percentage(%)function
Preconditions:None
Test Steps:
1.press 200
2.press %
Expected Result:
Display should  show (1%of 200)OR follow calculator logic

TEST CASE 12
Test Case ID:TC_CAL_012
Test Description:Verify decimal number input
Preconditions:None
Test Steps:
1.press7
2.press .
3.press 5
4.press +
5.press 2
6.press =
Expected Result:
Display should show 9.5

TEST CASE 13
Test Case ID:TC_CAL_013
Test Description:Verify calculator clears data using "CE"button i.e clear button
Preconditions:Calculator is open with some values entered
Test Steps:
1.Enter 10
2.Select +
3.Enter 5
4.Click clear
Expected Result:
All input fields and result field should be cleared

TEST CASE 14
Test Case ID:TC_CAL_014
Test Description:Verify Backspace removes one digit 
Preconditions:None
Test Steps:
1.press 8
2.press 5 
3.press backspace button
Expected Result:
Last digit removed dispaly shows 8

TEST CASE 15
Test Case ID:TC_CAL_011
Test Description:Verify multiple sequential operations
Preconditions:None
Test Steps:
1.press 5
2.press +
3.press 5
4.press = here result should be 10
5.press *
6.press 2
7.press =
Expected Result:
Final display should be 20

TEST CASE 16
Test Case ID:TC_CAL_016
Test Description:Verify input of multiple zeroes
preconditions:None
Test Steps:
1.press 0
2.press 0
3.press 0
Expected Result:
Display remains 0(should not show 000)

TEST CASE 17
Test Case ID:TC_CAL_017
Test Description:Verify UI button click responsiveness
preconditions:None
Test Steps:
1.click each number button(0 to 9)
2.click each operator
3.observe button highlight/feedback
Expected result:
Button respond instantly

TEST CASE 17
Test Case ID:TC_CAL_017
Test Description:Verify pressing = without entering input
preconditions:None
Test Steps:
1.press =
Expected Result:
Display remains 0

TEST CASE 18
Test Case ID:TC_CAL_018
Test Description:Verify decimal cannot be entered twice
preconditions:None
Test Steps:
1.press 7
2.press .
3.press . again
Expected Result:
only one decimal should appear thats is 7.

TEST CASE 19
Test Case ID:TC_CAL_019
Test Description:Verify big number display
preconditions:None
Test Steps:
1.Enter long number:123456789
Expected Result:
Display should not break UI or overflow


























