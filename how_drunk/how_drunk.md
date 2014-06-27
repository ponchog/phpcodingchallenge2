How Drunk are You? (5 Point)
=

The Challenge
-
Due to the high number of Spurs and FIFA World Cup fans being caught lately by the police while drunk driving, you have been assigned the task to develop a little program that can tell people how drunk they really are before driving
Specifications
-
The program will take in multiple inputs then output the Users BAC (blood alcohol concentration percentage) and a Message related to their BAC: 


You will need this
-

Liquid Ounces of Alcohol per beer bottle = 0.60

Liquid Ounces of Alcohol per glass of wine = 0.65

Liquid Ounces of Alcohol per tequila shot = 0.70

This is how you calculate your %BAC

%BAC = (A x 5.14/W x r) – .015 x H

A = Total liquid ounces

W = Weight

r = is the alcohol distribution ratio which for men is 0.73 and for women is 0.66

H = Hours

Input
-
Inputs: User Weight, User Sex, Hours Spent Drinking, # of Beers, # of Wine Glasses, # of Tequila Shots
We Will provide the formula needed to calculate BAC (See section above)


Output
-
You have to output the Users BAC (blood alcohol concentration percentage) and a Message related to their BAC: 

If your %BAC is below 0.05 you have to print "C'mon! Are you serious? Get back to the bar!"

If your %BAC is between 0.05 and 0.08 you have to print "Getting there dude..."

If your %BAC is greater than 0.08 and less than 0.20 you have to print "Better call Uber!"

If your %BAC is equal or greater than  0.20 you have to print "It doesn't matter anymore, you probably won't be able to read this..."


Example
-
-
**Example 1**

**Input:**
Enter Your Weight: 190

Enter your Sex: M

Hours spent drinking: 4

Bottles of Beers: 6

Glasses of Wine: 0

Shots of Tequila: 1


**Output:**
-
Your BAC % is 0.1994

Better call Uber!

-
**Example 2**

**Input:**
Enter Your Weight: 160

Enter your Sex: F

Hours spent drinking: 5

Bottles of Beers: 1

Glasses of Wine: 0

Shots of Tequila: 1


**Output:**
-
Your BAC % is 0.0223

C'mon! Are you serious? Get back to the bar!

-
**Example 3**

**Input:**
Enter Your Weight: 120

Enter your Sex: F

Hours spent drinking: 3

Bottles of Beers: 2

Glasses of Wine: 6

Shots of Tequila: 9


**Output:**
-
Your BAC % is 1.0583

It doesn't matter anymore, you probably won't be able to read this...

-
**Example 4**

**Input:**
Enter Your Weight: 220

Enter your Sex: M

Hours spent drinking: 4

Bottles of Beers: 4

Glasses of Wine: 0

Shots of Tequila: 0


**Output:**
-
Your BAC % is 0.0680

Getting there dude...
