# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
### NAME: DAPPILI VASAVI
### REGISTER NUMBER: 212223040030

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT
```
C:\Users\Keert\OneDrive\Desktop\MyLab
```
<img width="424" alt="image" src="https://github.com/user-attachments/assets/af778ab1-6069-4211-acc5-22754db6a2bd">


Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
```
cd  C:\Users\Keert\OneDrive\Desktop\MyLab
```
<img width="422" alt="image" src="https://github.com/user-attachments/assets/c771d83f-93b9-4ec3-aee5-2a4a182459ba">

```
type nul > MyFile.txt

```
<img width="435" alt="image" src="https://github.com/user-attachments/assets/3ca18c70-971d-444d-8294-d2372cae0aac">


List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
```
dir C:\Users\Keert\OneDrive\Desktop\MyLab
```
<img width="573" alt="image" src="https://github.com/user-attachments/assets/65698e54-5d4b-47e5-9f2a-182936b8cbe1">



Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
```
mkdir C:\Users\Keert\OneDrive\Desktop\Backup
```
<img width="603" alt="image" src="https://github.com/user-attachments/assets/f64f77d0-4c87-433e-aee0-9b19deb64f86">

```
copy MyFile.txt C:\Users\Keert\OneDrive\Desktop\Backup
```
<img width="661" alt="image" src="https://github.com/user-attachments/assets/1c7584ce-6f9b-4bcf-a997-025f13962b46">

Move the "MyLab" directory to the "Documents" folder.

## COMMAND AND OUTPUT
```
mkdir C:\Users\Keert\OneDrive\Desktop\Document
move MyLab Document
```
<img width="419" alt="image" src="https://github.com/user-attachments/assets/f38280a6-4a5a-47a6-99b5-4ca9f34a2f72">


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir C:\Users\Keert\OneDrive\Desktop\docbackup
copy C:\Users\Keert\OneDrive\Desktop\BackupScript.bat C:\Users\Keert\OneDrive\Desktop\docbackup
echo Backup completed successfully!
```
## OUTPUT


<img width="908" alt="image" src="https://github.com/user-attachments/assets/c945e2ac-c85c-4159-a252-bf7d0c8f38c9">

```
del C:\Users\Keert\OneDrive\Desktop\docbackup
```
<img width="560" alt="image" src="https://github.com/user-attachments/assets/9f32293e-3cf0-444f-a9e5-e392f2979f86">




# RESULT:
The commands/batch files are executed successfully.

