# Windows-basic-commands-batchscript
## Ex08-Windows-basic-commands-batchscript

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
Developed by: KAMALESH R

Register No:212223230094
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/KAMALESHNITHYA/Windows-basic-commands-batchscript/assets/145743119/0d087fc1-a7c2-4e5d-8585-6e8577e86c63)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/KAMALESHNITHYA/Windows-basic-commands-batchscript/assets/145743119/0d9e652f-12c1-4881-b24f-c0a2f996bc3b)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab
![image](https://github.com/KAMALESHNITHYA/Windows-basic-commands-batchscript/assets/145743119/dfb70b1f-c284-4adc-84e5-eb7ae871b225)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
%userprofile%\Desktop\Backup
![image](https://github.com/KAMALESHNITHYA/Windows-basic-commands-batchscript/assets/145743119/1425229a-27c5-4ecb-b74e-a0b0eb6c991f)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/KAMALESHNITHYA/Windows-basic-commands-batchscript/assets/145743119/a7cd11b6-056d-4e8a-9372-588420dbe890)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!




## OUTPUT

![image](https://github.com/KAMALESHNITHYA/Windows-basic-commands-batchscript/assets/145743119/21021648-743f-4fc8-a36c-d14360fc19aa)




# RESULT:
The commands/batch files are executed successfully.

