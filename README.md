<h1>Manage Directories and files</h1>

Creating, removing, and editing directories and files are essential tasks for effective data management. Maintaining an organized structure not only streamlines access to information but also makes it easier to identify potential issues and ensure the security of the data.

<h2>Objective</h2>

Organize the `/home/analyst` directory by making specific changes to its structure and contents. These changes include creating a new `logs` subdirectory, removing the `temp` subdirectory, moving the `Q3patches.txt` file to the `reports` subdirectory, deleting the `tempnotes.txt` file, and creating a new `tasks.txt` file in the `notes` subdirectory with a note detailing the tasks performed.

<h3>Create a Directorey</h3>

  - Create a new subdirectory called logs in the `/home/analyst` directory.
    - Using command `mkdir logs`

![Screenshot 2025-03-26 223954](https://github.com/user-attachments/assets/4d021666-9d57-4c15-9f7b-402a0b060c29)

<h3>Remove a Directory</h3>

  - Remove the `/home/analyst/temp` directory.
    - using command `rmdir temp`

![Screenshot 2025-03-26 224605](https://github.com/user-attachments/assets/7a71ecaa-d195-484d-b476-8d19ba8c3915)

<h3>Move a File</h3>

  - Navigate to the `/home/analyst/notes` directory.
    - using command `cd notes`

![image](https://github.com/user-attachments/assets/8f95d254-274e-49d9-8306-fe16ccfaf821)

  - Move the `Q3patches.txt` file from the `/home/analyst/notes` directory to the `/home/analyst/reports` directory.
    - using command `mv Q3patches.txt /home/analyst/reports/`
      
![image](https://github.com/user-attachments/assets/6d024c28-3ac3-4f49-91bb-15720cbb45a4)

<h3>Remove a File</h3>

  - Remove the `tempnotes.txt` file from the `/home/analyst/notes` directory
    - using command `rm tempnotes.txt`

![image](https://github.com/user-attachments/assets/d3d945cb-696c-4d03-81d6-3553d40c2e32)

![image](https://github.com/user-attachments/assets/fd524a19-ba6b-4e9f-8fd2-b64acfb067b2)

<h3>Create New File</h3>

  - Create a file named `tasks.txt` in the `/home/analyst/notes directory`
    - Use the `touch` command to create an empty file called `tasks.txt` in the `/home/analyst/notes`

![image](https://github.com/user-attachments/assets/8fa122a1-41ad-403c-9956-8b4f7942560f)

<h3>Edit a File</h3>

  - Use the nano text editor to edit the tasks.txt file
    - Open the `tasks.txt` file that is located in the `notes` directory.
    - Input command `nano tasks.txt`

![image](https://github.com/user-attachments/assets/43a3383d-48bb-4a66-a0d0-2dd1e706b931)

    Type   'Completed tasks
    1. Managed file structure in /home/analyst'

Press CTRL=x to exut nano.

<h1>Conclusion</h1>

I have gained practical experience with basic Linux Bash shell commands, including creating and removing directories, copying, moving, and deleting files, as well as editing files using the nano text editor.


