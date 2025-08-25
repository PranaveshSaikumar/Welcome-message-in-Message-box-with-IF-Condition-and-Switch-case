# Exercise 1 - Welcome message in Message box with IF Condition and Switch case

### Date: 24-08-25

### Name: Pranavesh Saikumar
### Regno: 212223040149

## Aim:
To create a workflow that takes user input (Name, Age, Gender) and checks the legal marital age in India using Switch and If activities, then displays the result in a Message Box.

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

<img width="637" height="820" alt="image" src="https://github.com/user-attachments/assets/f65bbd7e-be5d-4590-b8f9-ac9121736ae7" />

<img width="351" height="777" alt="image" src="https://github.com/user-attachments/assets/885742f6-4bb5-48a1-b297-2042ab078674" />

<img width="487" height="555" alt="image" src="https://github.com/user-attachments/assets/3f6fd628-55d4-4b7a-9339-5343a8e4f560" />

## Output:

<img width="500" height="815" alt="image" src="https://github.com/user-attachments/assets/e071659c-0884-47e5-947e-3d961421e503" />

<img width="472" height="832" alt="image" src="https://github.com/user-attachments/assets/75d4cbb8-d3d8-431c-b54b-a79d82b5df92" />


## Result:
Thus, a workflow that displays a "Hello World" message box using UiPath studio has been created and executed successfully.
