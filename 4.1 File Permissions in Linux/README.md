# Scenario

I am a security professional at a large organization. I work mainly with their research team. Part of my job is to ensure users on this team are authorized with the appropriate permissions. This helps keep the system secure. 

My task is to examine existing permissions on the file system. I’ll need to determine if the permissions match the authorization that should be given. If they do not match, I’ll need to modify the permissions to authorize the appropriate users and remove any unauthorized access.

# Step-By-Step Instructions

## Step 1: Access supporting material

Link to supporting material: <a href="Current file permissions.pdf">Current file permissions</a>

## Step 2: Check file and directory details

Check the permissions set for files and subdirectories in the projects directory. Make sure all permissions are displayed, including hidden files. Or, use the content of Current file permissions document to determine the current permissions. 

Describe the command used to check permissions in the Check file and directory details section of "File permissions in Linux".

Then, use either the output of this command to indicate the current permissions.

## Step 3: Describe the permissions string

Choose one example from the output in the previous step. In the Describe the permissions string section of "File permissions in Linux", write a short description that explains the 10-character string in the example. 

## Step 4: Change file permissions

The organization does not allow other to have write access to any files. Based on the permissions established in Step 2, identify which file needs to have its permissions modified. Use a Linux command to modify these permissions.

Describe the command used and its output in the Change file permissions section of "File permissions in Linux".

## Step 5: Change file permissions on a hidden file

The research team has archived .project_x.txt, which is why it’s a hidden file. This file should not have write permissions for anyone, but the user and group should be able to read the file. Use a Linux command to assign .project_x.txt the appropriate authorization.

Describe the command used and its output in the Change file permissions on a hidden file section of "File permissions in Linux".

## Step 6: Change directory permissions

The files and directories in the projects directory belong to the researcher2 user. Only researcher2 should be allowed to access the drafts directory and its contents. Use a Linux command to modify the permissions accordingly.

Describe the command used and its output in the Change directory permissions section of "File permissions in Linux".

## Step 7: Finalize your document

To finalize the document and make its purpose clear to potential employers, be sure to complete the Project description and Summary sections of "File permissions in Linux". 
In the Project description section, give a general overview of the scenario and what was accomplish through Linux. Write two to four sentences.
In the Summary section, provide a short summary of the previous tasks and connect them to the scenario. Write approximately two to four sentences.
