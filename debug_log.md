
# debug_log.md
# Author: Luke Mikhail

## Bug 1
Error type: KeyError
File + line: week8_buggy.py, line 12
What the error means: The first record used amout instead of amount
What I told the duck: I explained how the code adds up the amounts and 
noticed the first record has a typo in the key name.
What I tried: I ran the program, read the traceback, and added a print statement to inspect the record.
How I fixed it: I changed amout to amount and removed the temporary debug print.

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 18
What the error means: The code is comparing a number to '1000', which is written as text.
How I fixed it: removed the quotation marks around 1000 so Python compares two numbers.

## After Fixing Both Bugs
Final output: $5150.00 across 3 records and True
Did pytest pass? Yes / No

## AI Literacy Reflection
Did I use AI? Yes
If yes -- exact prompt I used: I’m having trouble with the errors in my Python debugging assignment. Can you explain what the errors mean in simple terms and help me understand how to fix them?
What AI explained: AI helped me understand the errors and how to fix them.
What I changed myself: I ran the commands, inspected the errors, and applied the fixes.
Can I explain every fixed line? Yes

## What I learned
I learned how to read error messages in Python and use them to find and fix mistakes in my code. I also learned that small mistakes, like spelling a variable wrong or using quotation marks incorrectly, can cause errors.

