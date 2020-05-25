--5/23 5:19 Problems: The operate function is not being called properly. The operatorValue isn't clearing, and the runningAnswer is not being affected. Isolating one operation doesn't help

--5/23 8:07 Problems: Trying to add a third operand won't allow multiple digits. 
If I fix that by adding && postOperator===false to the second option in digitAction(), 
I get the problem that after that the EQUALS button gets pressed, the display won't reset 
for an additional operation.

--5/25 9:24 Problem: If Ido an operation, and then try to enter a new number, it doesn't clear. Add something to digitAction() function. Then, deal with decimals 'n' such


--End Tasks: Make it so that the chain of numbers appears on the screen
Use Order of operations
