# Exercise 1 - Welcome message in Message box with IF Condition and Switch case

### Date: 24-08-25

### Name: Pranavesh Saikumar
### Regno: 212223040149

## Aim:
To create a workflow that displays a welcome message in Message box with IF Condition and Switch case.

## Procedure:
Step 1: Open UiPath Studio on your system.

Step 2: Create a new Process project and give it a name (e.g., MaritalAgeCheck).

Step 3: In Main.xaml, create a Sequence workflow.

Step 4: Add an Input Dialog activity to ask for Name. Store it in a variable personName.

Step 5: Add another Input Dialog activity to ask for Age. Store it in a variable age (as Integer).

Step 6: Add another Input Dialog activity to ask for Gender. Options:

"M"

"F"

Store it in a variable gender.

Step 7: Drag a Switch activity into the Sequence.

Set Expression to gender.

Set TypeArgument to String.

Step 8: Add Case "M"  Use If activity inside:

Condition: age >= 21

Then: Message Box = "Legal marital age reached!"

Else: Message Box = "Marry after "+(21-age).ToString+" Years"

Step 9: Add Case "F" = Use If activity inside:

Condition: age >= 18

Then: Message Box = "Legal marital age reached!"
Else: Message Box = "Marry after "+(21-age).ToString+" Years"

## WorkFlow:
<img width="1919" height="1079" alt="Screenshot 2025-08-22 092926" src="https://github.com/user-attachments/assets/aa7ff543-5996-45b0-90bd-df74313a7d2c" />

## Output:
<img width="1919" height="1079" alt="Screenshot 2025-08-22 092940" src="https://github.com/user-attachments/assets/fcf7f858-d40e-4f51-a87b-3589636719c0" />

## Result:
Thus, a workflow that displays a "Hello World" message box using UiPath studio has been created and executed successfully.
