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

```
mkdir my-folder

```
<img width="492" height="39" alt="image" src="https://github.com/user-attachments/assets/d6d9927b-05e8-4b09-ba84-028a5e33b2b0" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

```
rmdir my-folder

```

<img width="492" height="39" alt="image" src="https://github.com/user-attachments/assets/40c765d4-5aa1-4f66-b76a-b600f470465a" />


## COMMAND AND OUTPUT


Create the file Rose.txt

```
type nul > Rose.txt
```
<img width="484" height="32" alt="image" src="https://github.com/user-attachments/assets/99712aa4-320a-4a10-be56-1453077283d6" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

```
echo Hello World > hello.txt
```
<img width="484" height="32" alt="image" src="https://github.com/user-attachments/assets/db01a7ac-140a-44c6-b1cd-1d23631a4a22" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

```
copy hello.txt hello1.txt
```
https://private-user-images.githubusercontent.com/182321167/565663860-c2351289-dca1-4f6b-a877-dab3d1f8dd2e.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzM5MTA2ODcsIm5iZiI6MTc3MzkxMDM4NywicGF0aCI6Ii8xODIzMjExNjcvNTY1NjYzODYwLWMyMzUxMjg5LWRjYTEtNGY2Yi1hODc3LWRhYjNkMWY4ZGQyZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzE5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMxOVQwODUzMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04OGEzZGFlMGRmMDYzMWRmMDFiMjQwZjBjYzkyYzU1ZGM3MWU1ZjhhZjAxNTNmYTBhODE4MmFjOGRjMWMyMmVlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.XWUnsOTR-z49r_HTjfpU27hp9TtQDWlE8-QHc35rXek

## COMMAND AND OUTPUT

Remove the file hello1.txt

```
del hello1.txt
```
https://private-user-images.githubusercontent.com/182321167/565663970-73c544c3-9ffc-4409-a0c2-8bd310b3149d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzM5MTA2ODcsIm5iZiI6MTc3MzkxMDM4NywicGF0aCI6Ii8xODIzMjExNjcvNTY1NjYzOTcwLTczYzU0NGMzLTlmZmMtNDQwOS1hMGMyLThiZDMxMGIzMTQ5ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzE5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMxOVQwODUzMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01NzcwYjk0MGVlNGRjMzg5NzM0MWQxNmNjZGQ0OTU0NDg3MDI5MjQxNjU1Yzg4ZGQzNDI3MTk0ZTUxM2QzNzY3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.BJ8yuD4VHe8Wo7x9BFBlBqqYMeVMfwI3xy7abiq3_-g


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

```
dir hello1.txt
```
https://private-user-images.githubusercontent.com/182321167/565664067-4423a77d-ab7f-4ad2-ab36-41d4f46c195f.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzM5MTA2ODcsIm5iZiI6MTc3MzkxMDM4NywicGF0aCI6Ii8xODIzMjExNjcvNTY1NjY0MDY3LTQ0MjNhNzdkLWFiN2YtNGFkMi1hYjM2LTQxZDRmNDZjMTk1Zi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzE5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMxOVQwODUzMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lYjQ1YjQ5Mzk5MTQyMmFjNzc0MTlhNjVhZGQ0MzcxMWVkYTJjMjc4YzZjNDViYzNhYmRhZWE4ODE1Yzc3NGRmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Ry1WYVoNm2OkrEpnuYETnGg6E7HIOOvFUMyJhvYdm8k

## COMMAND AND OUTPUT

List out all the associated file extensions 

```
assoc
```
https://private-user-images.githubusercontent.com/182321167/565664162-956e9fd4-5566-4ef1-9fd0-378b857b8de4.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzM5MTA2ODcsIm5iZiI6MTc3MzkxMDM4NywicGF0aCI6Ii8xODIzMjExNjcvNTY1NjY0MTYyLTk1NmU5ZmQ0LTU1NjYtNGVmMS05ZmQwLTM3OGI4NTdiOGRlNC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzE5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMxOVQwODUzMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01ZmIyM2ViOTBkMjAxN2UwNjU2MDY0MmI3NzQzY2U3ZGNkYjQxZTY1MjcxNzdiNDM2MjJkODBlNjdjMjViM2VhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.3S_M2Tm3byW-E_hKysS9_fV4Eg9MgAbI5nQfMUA-uSM

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

```
fc hello.txt Rose.txt
```

https://private-user-images.githubusercontent.com/182321167/565664642-19ab1fc8-1c33-4031-9cb7-085e7953a670.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzM5MTA2ODcsIm5iZiI6MTc3MzkxMDM4NywicGF0aCI6Ii8xODIzMjExNjcvNTY1NjY0NjQyLTE5YWIxZmM4LTFjMzMtNDAzMS05Y2I3LTA4NWU3OTUzYTY3MC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzE5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMxOVQwODUzMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jYWY0MDlmMzQ5MjM1MTA4MDI2ZDFlOThlMTM4ODIzMGEzYTdhNmY1ZGE3NTJhYWEzMDI1MTZlMTEwOGIyNjgwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.7hP_7ChIdkF3FBOhqR-uZWx46hOkYiIavG8cSkmOG6M

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





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




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

