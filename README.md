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
<img width="861" height="101" alt="image" src="https://github.com/user-attachments/assets/0a424d32-ed14-477e-a265-ba78e9e070dc" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="939" height="105" alt="image" src="https://github.com/user-attachments/assets/0bcbdb5e-d94b-4120-8e85-57572fb951cc" />

## COMMAND AND OUTPUT
<img width="976" height="65" alt="image" src="https://github.com/user-attachments/assets/7a92ccb1-ae49-4ecf-9a8f-a043595d9d91" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="1063" height="36" alt="image" src="https://github.com/user-attachments/assets/4c118bfd-e94b-4576-ad0f-12707e6521ab" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1063" height="36" alt="image" src="https://github.com/user-attachments/assets/2606f027-6b2f-404d-93b9-34f275dc4f2d" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="848" height="85" alt="image" src="https://github.com/user-attachments/assets/ca8483d2-1857-4623-a992-e43eea94e966" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="944" height="184" alt="image" src="https://github.com/user-attachments/assets/0250a499-cdc8-4807-bdd1-329fb1ab42f1" />

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="788" height="1064" alt="image" src="https://github.com/user-attachments/assets/ef69e9f3-8b07-446e-9b2e-8c3a74e6b7e7" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="948" height="161" alt="image" src="https://github.com/user-attachments/assets/1969c279-18f4-4ddd-b568-554a4ff02953" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


<img width="466" height="83" alt="image" src="https://github.com/user-attachments/assets/34a330e8-d792-41d7-beab-0688acbfdd65" />



## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.


<img width="543" height="214" alt="image" src="https://github.com/user-attachments/assets/6a90589a-82e4-4b89-a037-7236d22c7659" />


## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):
<img width="387" height="180" alt="image" src="https://github.com/user-attachments/assets/ccda51da-973f-4a36-a513-62bb24e10a14" />

## OUTPUT

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.
<img width="380" height="55" alt="image" src="https://github.com/user-attachments/assets/128863e3-db0d-4893-8679-b02c70bd2012" />


## OUTPUT

<img width="362" height="149" alt="image" src="https://github.com/user-attachments/assets/4bf30500-a0e7-4223-a5b5-f3b6401eb2e1" />


# RESULT:
The commands/batch files are executed successfully.

