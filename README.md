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
![image](https://github.com/user-attachments/assets/7482dac5-96a9-4b87-93a7-6973fb46d1c4)


Remove the directory "my-folder"

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/7288b7fb-749d-474a-901c-08f850adb7da)


Create the file Rose.txt

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/633a8f68-45eb-4e11-9c91-5691a804dfac)


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/33a6e4db-016e-463f-b8aa-45414d9252e5)


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/f5f37dee-dca7-4825-b47d-3a6eceb94611)


Remove the file hello1.txt

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/1bb47819-1624-4ad4-9067-0639c831999f)


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/9d39a4b6-840f-46df-968d-6b1dc08d673e)


List out all the associated file extensions 

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/dff45c20-f9fa-4c50-9535-583ff13ce9e2)

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/f8902125-4c44-4f1c-a632-8ced30814beb)


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

![image](https://github.com/user-attachments/assets/6b8c0bce-7aba-4582-b5d2-29936ed04e8d)


## OUTPUT
![image](https://github.com/user-attachments/assets/449fc921-cd73-4da7-9fce-80e503572341)



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
![image](https://github.com/user-attachments/assets/17827ce0-7f35-4026-a84d-4e54583ad177)



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
![image](https://github.com/user-attachments/assets/58949545-ba32-4c14-a41d-df341fb28bcf)



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
![image](https://github.com/user-attachments/assets/5c828a9e-0648-4ec8-8618-5a90ba055318)


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
![image](https://github.com/user-attachments/assets/0b82a783-485c-4f72-8cbc-6300519098c5)



# RESULT:
The commands/batch files are executed successfully.
