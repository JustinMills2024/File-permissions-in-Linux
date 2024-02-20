<h1> File permissions in Linux</h1>
<h2>Project description</h2>
<br>The research team at my organization needs to update the file permissions for certain files and directories within the projects directory. 
The permissions do not currently reflect the level of authorization that should be given. Checking and updating these permissions will help keep their system secure.</br> 

<br>To complete this task, I performed the following tasks:</br>

<ul>
  <li>Check file and directory details</li>
  <li>Change file permissions</li>
  <li>Change file permissions on a hidden file</li>
  <li>Change directory permissions</li>
</ul>
<h2> Check file and directory details</h2>
The following code demonstrates how I used Linux commands to determine the existing permissions set for a specific directory in the file system.

<img src="https://github.com/JustinMills2024/File-permissions-in-Linux/assets/159082478/582df23a-cf0e-414b-843f-0fbf1bd738be" alt="Image 1">

<h2>Change file permissions</h2>

<br>The organization determined that other shouldn't have write access to any of their files. To comply with this, I referred to the file permissions that I previously returned. I determined project_k.txt must have the write access removed for other.

The following code demonstrates how I used Linux commands to do this:</br>

<img src="https://github.com/JustinMills2024/File-permissions-in-Linux/assets/159082478/1467273f-5057-4542-b20f-cb159f11ba83" alt="Image 2">

<h2>Change file permissions on a hidden file
</h2>
The research team at my organization recently archived project_x.txt. They do not want anyone to have write access to this project, but the user and group should have read access. 

The following code demonstrates how I used Linux commands to change the permissions:

<img src="https://github.com/JustinMills2024/File-permissions-in-Linux/assets/159082478/59cdb654-03d5-4d49-9eaa-73d2d43b846d" alt="Image 3">

<h2>Change directory permissions
</h2>
My organization only wants the researcher2 user to have access to the drafts directory and its contents. This means that no one other than researcher2 should have execute permissions.

The following code demonstrates how I used Linux commands to change the permissions:

<img src="https://github.com/JustinMills2024/File-permissions-in-Linux/assets/159082478/ecbcb83e-f6b1-44ae-afde-756733f9d0ff" alt="Image 4">

<h2>Summary</h2>
I changed multiple permissions to match the level of authorization my organization wanted for files and directories in the projects directory. The first step in this was using ls -la to check the permissions for the directory. This informed my decisions in the following steps. I then used the chmod command multiple times to change the permissions on files and directories.




