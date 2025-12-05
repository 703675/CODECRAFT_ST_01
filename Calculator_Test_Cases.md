TEST CASE 1
Test Case ID:TC_CAL_001
Test Description:Verify addition of two positive integers
preconditions:Calculator app should be open
Test Steps:
1.Enter 10 in the first input field
2.Enter 20 in the second input field
3.Select the addition (+)operator
4.click on the Calculate/Equal(=)button
Expected Result:
The calculator should dispaly the result as 30

TEST CASE 2
Test Case ID:TC_CAL_002
Test Description:Verify subtraction of two positive integers
preconditions:Calculator app should be open
Test Steps:
1.Enter -5 in the first input field
2.Enter -10 in the second input field
3.Select the -(subtraction)operator
4.click on the equal button
Expected Result:
The result should be 5 (because -5-(-10)=5)

TEST CASE 3
Test Case ID:TC_CAL_003
Test Description:Verify multiplication using decimal values
preconditions:Calculator app should be open
Test Steps:
1.Enter 2.5
2.Enter 4
3.Select the *(multiplication)operator
4.Tap the equals button
Expected Result:output should be 10  as 2.5*4 is 10

TEST CASE 4
Test Case ID:TC_CAL_004
Test Description:Verify division operator with valid numbers
Preconditions:Calculator should be functional
Test Steps:
1.Enter 20
2.Enter 5
3.select/(division)
4.Tap the equals button
Expected Result:
output should be 4 as 5*4 20 and 20 divided by 5 is 4

TEST CASE 5
Test Case ID:TC_CAL_005
Test Description:Verify division by zero
Preconditions:None
Test Steps:
1.Enter 10
2.Enter 0
3.Select /
4.Click the equals button
Expectedd Result:
App should show an error message such as "Cannot divide by Zero"

TEST CASE 6
Test Case ID:TC_CAL_006
Test Description:Verify input of non-numeric characters
Preconditions:None
Test Steps:
1.Enter abc in any input field
2.Select any operator
3.Tap the equals button
Expected Result:
Calculator must show validation message:"Invalid input"
Should NOT crash 

TEST CASE 7
Test Case ID:TC_CAL_007
Test Description:Verify BODMAS operation if multi-input expression is allowed
Preconditions:Calculator supports expressions
Test Steps:
1.Enter 2+3*4
2.press equal
Expected Result:
Result should follow BODMAS =14

TEST CASE 8
Test Case ID:TC_CAL_008
Test Description:Verify UI behaviour when one field is empty
Preconditions:None
Test Steps:
1.Leave first number blank
2.Enter 10 in second field
3.Select +
4.Click equals
Expected Result:
Show warning:"Enter both values"
No calculation performed

TEST CASE 9
Test Case ID:TC_CAL_009
Test Description:Verify calculator clears dats using "clear"button
Preconditions:Calculator is open with some values entered
Test Steps:
1.Enter 10
2.Enter 5
3.Select +
4.Click clear
Expected Result:
All input fields and result field should be cleared

TEST CASE 10
Test Case ID:TC_CAL_010
Test Description:Verify multiplication with large numbers
Preconditions:Calculator supports large numerical input
Test Steps:
1.Enter 999999
2.Enter 999999
3.Select *
4.Press equals
Expected Result:
Calculator should display correct result:999998000001
Should not freeze or crash















