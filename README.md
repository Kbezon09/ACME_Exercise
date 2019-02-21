# ACME_Exercise
Calculating the payment due to a worker based in the worked hours, the time of the day and the day the person worked.
My code has 2 main functions besides the main. The first one, getName which gets the name of the person and stores it. The second one is the biggest and more important, getPaymentPerDay, which gets the amount to pay the person for each day.
The code starts by opening the .txt file and reading the first line.After reading the firt line and saving it to a buffer, it stats the function getName. After the name is stored it starts a while controled by a flag in which the program calls getPaymentPerDay to obtain the amount to pay for each day and add it to a total. This while hill continue until a period (.) is found at the end of the line.
Finally the program displays the message using the name and the amount due to that person.

To run the program a .txt file named ACME has to be already created in the debug folder. The report lines for each person have to end in a dot (.).You can run the program through the debugger or the powershell being in the debug folder.
