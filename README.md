# Vi Editor (VIM)

In this section, we will take a look at console based text editors in linux.
- It is not feasible using **`cat`** when dealing with large amounts of text or for writing code. This is why we use text editors

## Text Editor

There are several options available, we will be focusing on the **`VI Editor`**.
- Most popular text editor in linux is the **`VI`** Editor.
- The VI EDITOR is available in all most all of the linux distribution out of the box. 
- The command to open the vi editor is **`vi`** followed by the filename that you want to create or append.
  
  ```
  $ vi /home/michael/sample.txt
  ```
- The VI EDITOR has three operation modes.
  1. Command Mode
     - When the vi editor opens a file, it always goes to the **`COMMAND MODE`** first.
     - In this mode, the editor only understands the commands
  1. Insert Mode
     - To switch from command mode to **`INSERT MODE`** type lower case **`i`**
     - This mode allows you to write text into the file.
     - Once you are done with editing the file, to go back to command mode hit the **`ESC`** button.
     - While going into insert mode from command mode you may use other options such as **`I`**, **`o`**, **`O`**, **`a`**, or **`A`**
  1. Last Line Mode
     - Pressing the **`:`** key will take you to the **`LAST LINE MODE`** 
     - In this mode you can choose to save changes to the file, discard changes, or save and edit.
     - From the last line mode hit the **`ESC`** key to go back to the command mode.
     
     ![vi1](https://github.com/user-attachments/assets/8c7f242e-e447-4591-9b46-8326692f6708)
     
 ## Command Mode
   
   ![command1](https://github.com/user-attachments/assets/bbf8dff3-6db5-42fc-9d17-452964b2c24b)
   
   ![command2](https://github.com/user-attachments/assets/817d58cc-72f5-46b5-92e0-68acdcdcda20)
   
   ![command3](https://github.com/user-attachments/assets/39515766-078e-4b73-9abf-c952a5143ead)
   
   
 ## Insert Mode

   ![insert](https://github.com/user-attachments/assets/9b466946-016f-42ec-9a42-e185df198275)
    
 ## Last Line Mode
 
   ![lastline](https://github.com/user-attachments/assets/5a4225fc-659e-48a0-b2ea-bbf98d4490e4)
    
 
 #### There is another popular editor called **`VIM`** which is an improved version of **`VI`** with added features but very similar in appereance to VI.
 
 - In the most distros today, the VI is the symblic to the VIM editor
   
   ![VIM](https://github.com/user-attachments/assets/6dc2f675-4b09-4b49-94e2-33c324335dac)
   


