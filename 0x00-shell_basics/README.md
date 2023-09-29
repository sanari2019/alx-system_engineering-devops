## Script List

Here is a list of the available scripts in this repository along with brief descriptions:

1. **0-current_working_directory**
   - **Description:** Prints the absolute path name of the current working directory.

2. **1-listit**
   - **Description:** Displays the contents list of the current directory.

3. **2-bring_me_home**
   - **Description:** Changes the working directory to the user's home directory without using shell variables.

4. **3-listfiles**
   - **Description:** Displays current directory contents in a long format.

5. **4-listmorefiles**
   - **Description:** Displays current directory contents, including hidden files, in long format.

6. **5-listfilesdigitonly**
   - **Description:** Displays current directory contents in long format with user and group IDs displayed numerically, including hidden files.

7. **6-firstdirectory**
   - **Description:** Creates a directory named `my_first_directory` in the `/tmp/` directory.

8. **7-movethatfile**
   - **Description:** Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

9. **8-firstdelete**
   - **Description:** Deletes the file `betty` in `/tmp/my_first_directory`.

10. **9-firstdirdeletion**
    - **Description:** Deletes the directory `my_first_directory` in the `/tmp/` directory.

11. **10-back**
    - **Description:** Changes the working directory to the previous one.

12. **11-lists**
    - **Description:** Lists all files (including hidden ones) in the current directory, parent of the working directory, and the `/boot` directory, in long format.

13. **12-file_type**
    - **Description:** Prints the type of the file named `iamafile` located in the `/tmp` directory.

14. **13-symbolic_link**
    - **Description:** Creates a symbolic link to `/bin/ls`, named `__ls__`, in the current working directory.

15. **14-copy_html**
    - **Description:** Copies HTML files from the current working directory to the parent of the working directory, but only if they don't exist or are newer.
16.** Task 15: Let’s move ** :Description: Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
Script: 100-lets_move
**Task 16: Clean Emacs**: Description: Create a script that deletes all files in the current working directory that end with the character ~.
Script: 101-clean_emacs

**Task 17: Tree **: Description: Create a script that creates the directories welcome/, welcome/to/, and welcome/to/school in the current directory.
Script: 102-tree
**Task 18: Life is a series of commas, not periods**:Description: Write a command that lists all the files and directories of the current directory, separated by commas (,).
Script: 103-commas

**Task 19: File type: School**
Description: Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
Magic File: school.mgc

## Usage

To run any of these scripts, use the following command in your terminal:

```bash
./script-name
