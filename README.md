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
<img width="772" height="243" alt="image" src="https://github.com/user-attachments/assets/9cc6b0ce-6a53-47ac-b281-becc6e10ca1e" />



## COMMAND AND OUTPUT

Remove the directory "my-folder"

```
rmdir my-folder

```

<img width="488" height="235" alt="image" src="https://github.com/user-attachments/assets/392857bf-0668-47ec-af75-9528f2b8bc04" />



## COMMAND AND OUTPUT


Create the file Rose.txt

```
type nul > Rose.txt
```

<img width="758" height="96" alt="image" src="https://github.com/user-attachments/assets/fb066baa-9096-4ffb-a852-52da78e229d5" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

```
echo Hello World > hello.txt
```
<img width="600" height="113" alt="image" src="https://github.com/user-attachments/assets/a4105850-97e4-4318-b50c-5896794bd28e" />



## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

```
copy hello.txt hello1.txt
```
<img width="593" height="144" alt="image" src="https://github.com/user-attachments/assets/6330e504-e779-4b3f-84ff-6c3e46a227d8" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

```
del hello1.txt
```

<img width="644" height="237" alt="image" src="https://github.com/user-attachments/assets/580d3e26-7df2-46d1-b892-ae1ebc5b6b40" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

```
dir hello1.txt
```
<img width="463" height="183" alt="image" src="https://github.com/user-attachments/assets/8034e202-f6a6-485b-b634-3387b67fc5af" />

## COMMAND AND OUTPUT

List out all the associated file extensions 

```
assoc
```
<img width="568" height="610" alt="image" src="https://github.com/user-attachments/assets/87ca4a88-22a9-41be-8ec8-6f72a32aee28" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

```
fc hello.txt Rose.txt
```

<img width="574" height="189" alt="image" src="https://github.com/user-attachments/assets/3d37a249-0cae-4e32-891c-070dd45be5ae" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

```
@echo off
set name=Saveetha
echo Hello, %name%!
pause
```

## OUTPUT
<img width="672" height="98" alt="image" src="https://github.com/user-attachments/assets/b0d7ea6b-6ab1-49fd-b8ba-3eece5d87352" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

```
@echo off
:main
set /p number=Enter a number: 
rem Calculate remainder when divided by 2
set /a remainder=%number% %% 2
if %remainder%==1 (
    echo %number% is an odd number.
) else (
    echo %number% is not an odd number.
)
:choice
set /p continue=Do you want to check another number? (Y/N): 
if /i "%continue%"=="Y" goto main
if /i "%continue%"=="N" goto end
echo Invalid choice, please enter Y or N.
goto choice
:end
echo Thank you for using the odd number checker!
pause

```


## OUTPUT

<img width="679" height="186" alt="image" src="https://github.com/user-attachments/assets/5a74cc9a-9ef6-4895-b348-11660acdeed7" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

```
@echo off
for %%i in (1 2 3 4 5) do (
    echo Number: %%i
)
pause
```

## OUTPUT

<img width="690" height="172" alt="image" src="https://github.com/user-attachments/assets/e3b4cd8f-9e26-4e73-b633-fbac88dc413a" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

```
@echo off
if exist sample.txt (
    echo sample.txt exists.
) else (
    echo sample.txt does not exist.
)
pause

```

## OUTPUT
<img width="605" height="98" alt="image" src="https://github.com/user-attachments/assets/4d14b6dc-5826-4d2a-9866-c70649b59b5b" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

```

@echo off
:menu
echo 1. Say Hello
echo 2. Create a File
echo 3. Exit
set /p choice=Choose an option: 
if "%choice%"=="1" goto hello
if "%choice%"=="2" goto createfile
if "%choice%"=="3" goto end

:hello
echo Hello, World!
goto menu

:createfile
echo Creating a file...
echo This is a new file > newfile.txt
goto menu
:end
echo Goodbye!
pause

```

## OUTPUT

<img width="629" height="407" alt="image" src="https://github.com/user-attachments/assets/15ceb65c-c174-4c45-a5f9-b0035066ebee" />


# RESULT:
The commands/batch files are executed successfully.

