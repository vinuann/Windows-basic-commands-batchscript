# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

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
```mkdir %userprofile%\Desktop\MyLab```
![image](https://github.com/user-attachments/assets/e9d97e3c-381a-4c17-970f-37be4345c963)


Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
```cd %userprofile%\Desktop\MyLab```
![image](https://github.com/user-attachments/assets/f95ac6d6-229c-44ef-a555-3a10d838acac)

type nul > MyFile.txt
![image](https://github.com/user-attachments/assets/96593a28-de66-4e27-a950-811859911b61)



List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
```dir %userprofile%\Desktop\MyLab```
![image](https://github.com/user-attachments/assets/7cc69887-2067-4814-bc51-1ab1056491c7)


Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
```mkdir %userprofile%\Desktop\Backup```
![image](https://github.com/user-attachments/assets/4ae106dc-3fcb-485f-b8f5-c54d30a60720)

copy MyFile.txt %userprofile%\Desktop\Backup
![image](https://github.com/user-attachments/assets/2fda686f-a7fa-4dcf-84c0-24e398b78765)



Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT
```mkdir %userprofile%\Desktop\Documents```
![image](https://github.com/user-attachments/assets/3a644893-1312-4001-95c5-0ccfca3b3792)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```









## OUTPUT
![image](https://github.com/user-attachments/assets/2ce915e4-9d1f-42ff-b496-75d71838080e)






# RESULT:
The commands/batch files are executed successfully.

