# Multi-Page Websites

## Topic: Computer File Paths

## Date: 14/01/2025 

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

- **Absolute File Path**: The file path that is relative to the root of the computer
  
  ``` C:/Thachdeptrai/ConAiDepTraiBang/Deptraivl.txt ```

- **Relative File Path**: The file path that is relative to the location where you are writing the code. It will be shorter and also more importantly
  ***Example***: We are writing code at folder ***ConAiDeptraiBang***. We can give the relative path by using:

  ``` ./somewheretogo/target_file.txt ```

- **Special Character**: Can make easier to navigate the file structure:
  1. **Double dots** *(..)*: When we write double dots of the beginning of the relative file path, what it means is to go up a level or go back to 1 folder.
  **Example:**

        ``` C:/Thachdeptrai/ConAiDepTraiBang/Deptraivl.txt ```

        We are currently in folder **ConAiDepTraiBang**, when we try to code in file *hehe.txt* in the folder Thachdeptrai. We can proceed with this relative file path along with special character:

        ``` ../hehe.txt ```

  2. **Dots** *(.)*: Tell us stay within the current directory and look over there.
  **Example:**

        ``` C:/Thachdeptrai/ConAiDepTraiBang/Deptraivl.txt ```

        We are currently in folder **ConAiDepTraiBang**, when we try to code in file *hehe2.txt* in the same folder **ConAiDepTraiBang**. We can proceed with this relative file path along with special character:

        ``` ./hehe2.txt ```

        **Note:** you can omit *./* when access to the file which is in the same directory. But sometimes it won't work. Hence, *./* is recommended with **100%** work of the time.  

---

### Summary Section (Summary of Notes)


