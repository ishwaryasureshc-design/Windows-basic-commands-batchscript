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
<img width="426" height="114" alt="Screenshot 2026-09-19 082421" src="https://github.com/user-attachments/assets/439d5ab2-f936-4549-947e-1757df021408" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="505" height="122" alt="Screenshot 2026-09-19 082425" src="https://github.com/user-attachments/assets/19a733ff-ee2c-430c-9eba-498b4a53bb5f" />



Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="290" height="90" alt="image" src="https://github.com/user-attachments/assets/fe2c7862-5774-4367-a91d-b6b9b9e39e73" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="606" height="94" alt="Screenshot 2026-09-19 082701" src="https://github.com/user-attachments/assets/8422cb4f-27b2-4929-bcad-24f46e172495" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="425" height="130" alt="Screenshot 2026-09-19 082728" src="https://github.com/user-attachments/assets/445893b7-bb75-4bb8-8436-ea84e8a494e0" />



Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="350" height="247" alt="Screenshot 2026-09-19 082754" src="https://github.com/user-attachments/assets/8a377fab-a52f-42e3-af4a-65fb214c5bf4" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="435" height="446" alt="Screenshot 2026-09-19 082818" src="https://github.com/user-attachments/assets/0e00f077-602a-4ffc-92c9-725098f13a90" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="443" height="190" alt="Screenshot 2026-09-19 082844" src="https://github.com/user-attachments/assets/3112aa8c-f382-4a00-9520-680eec4ef636" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="275" height="175" alt="Screenshot 2026-09-19 082935" src="https://github.com/user-attachments/assets/e73ab916-2174-45ba-8635-5091d8205499" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="668" height="312" alt="image" src="https://github.com/user-attachments/assets/94e9b8c9-2f44-4fa8-81c3-ef6290c50256" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="504" height="240" alt="image" src="https://github.com/user-attachments/assets/9cc735e6-8707-4236-98a8-63d713c62239" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="545" height="220" alt="image" src="https://github.com/user-attachments/assets/d33ed680-8d16-4bb1-82b9-274da6b27dec" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="301" height="340" alt="image" src="https://github.com/user-attachments/assets/0102468e-c377-40d6-8c4e-74130281e509" />


# RESULT:
The commands/batch files are executed successfully.

