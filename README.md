# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT

Remove the directory "my-folder"<img width="606" height="223" alt="1 mkdir" src="https://github.com/user-attachments/assets/35be786f-8d32-42ea-a402-b818c4af9dcf" />


## COMMAND AND OUTPUT


Create the file Rose.txt
<img width="842" height="371" alt="2 rmdir" src="https://github.com/user-attachments/assets/953ce6f7-a3d7-42e4-b1d1-77599fa4165e" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
<img width="828" height="352" alt="3 rose" src="https://github.com/user-attachments/assets/4ce73809-ef45-4082-96f9-51d1d90661fa" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="960" height="121" alt="4 hello" src="https://github.com/user-attachments/assets/162f385c-3c12-4dd9-994b-386510bd9dc3" />

## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="782" height="221" alt="6 remove" src="https://github.com/user-attachments/assets/2fb7412c-fc76-4bc5-bf9d-19d22b5c8f37" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="757" height="1059" alt="7 list" src="https://github.com/user-attachments/assets/988e43a9-2065-4b47-869a-da9406636bcd" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="863" height="1106" alt="8 list" src="https://github.com/user-attachments/assets/b25a6684-9ac5-46a9-a469-41ca383012ec" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
<img width="826" height="188" alt="9 rose" src="https://github.com/user-attachments/assets/12386a9b-d26f-4b72-816c-bba3e3d88a99" />





## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.
<img width="697" height="89" alt="10 bat" src="https://github.com/user-attachments/assets/6aa7c74a-62a9-4617-994a-5fd29cc8f758" />



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

<img width="693" height="260" alt="11 bat" src="https://github.com/user-attachments/assets/54cefe61-2a27-468e-8189-18fb9301d2c1" />



## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):<img width="715" height="209" alt="12 bat" src="https://github.com/user-attachments/assets/c914ba4e-7782-4a99-9d16-25811cafecee" />


## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.<img width="753" height="442" alt="14 bat" src="https://github.com/user-attachments/assets/141ed52b-4f91-4c4e-8362-052913a8cf93" />







# RESULT:
The commands/batch files are executed successfully.

