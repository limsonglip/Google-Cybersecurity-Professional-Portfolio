# Scenario

I am a security professional working at a health care company. As part of my job, I'm required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with personal patient records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. There's also a remove list that identifies which employees I must remove from this allow list.

My task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, I should remove those IP addresses from the file containing the allow list.

# Step-By-Step Instructions

## Step 1: Open the file that contains the allow list

The file is called "allow_list.txt". Assign a string containing this file name to the import_file variable. Then, use a with statement to open it. Use the variable file to store the file while working with it inside the with statement.

Describe the Python syntax, functions, and keywords needed to accomplish this in the Open the file that contains the allow list section.

## Step 2: Read the file contents

Next, use the .read() method to convert the contents of the allow list file into a string so that it can be read. Store this string in a variable called ip_addresses.

Describe the Python syntax, functions, and keywords needed to accomplish this in the Read the file contents section.

## Step 3: Convert the string into a list

In order to remove individual IP addresses from the allow list, the IP addresses need to be in a list format. Therefore, use the .split() method to convert the ip_addresses string into a list.

Describe the Python syntax, functions, and keywords needed to accomplish this in the Convert the string into a list section.

## Step 4: Iterate through the remove list

A second list called remove_list contains all of the IP addresses that should be removed from the ip_addresses list. Set up the header of a for loop that will iterate through the remove_list. Use element as the loop variable.

Describe the Python syntax, functions, and keywords needed to accomplish this in the Iterate through the remove list section.

## Step 5: Remove IP addresses that are on the remove list

In the body of the iterative statement, add code that will remove all the IP addresses from the allow list that are also on the remove list. First, create a conditional that evaluates if the loop variable element is part of the ip_addresses list. Then, within that conditional, apply the .remove() method to the ip_addresses list and remove the IP addresses identified in the loop variable element.

Describe the Python syntax, functions, and keywords needed to accomplish this in the Remove IP addresses that are on the remove list section. 

In addition, include a sentence that explains that applying the .remove() method in this way is possible because there are no duplicates in the ip_addresses list.

## Step 6: Update the file with the revised list of IP addresses

Now that these IP addresses have been removed from the ip_address variable, complete the algorithm by updating the file with this revised list. To do this, first convert the ip_addresses list back into a string using the .join() method. Apply .join() to the string "\n" in order to separate the elements in the file by placing them on a new line.

Then, use another with statement and the .write() method to write over the file assigned to the import_file variable.

Describe the Python syntax, functions, and keywords needed to accomplish this in the Update the file with the revised list of IP addresses section.

## Step 7: Finalize your document

To finalize the document and make its purpose clear to potential employers, be sure to complete the Project description and Summary sections. In the Project description section, give a general overview of the scenario and what you accomplished in Python. Write three to five sentences. In the Summary section, provide a short summary of the algorithm by highlighting its main components. Write four to six sentences.

View how I updated a file through a Python algorithm <a href="Update a file through a Python Algorithm.pdf">here</a>.
