Assignment Prompt: 

Step 1: File system navigation commands
First, let’s make sure you know these fundamental file system navigation commands. Create your own reference table by filling in the commands below. Copy and paste the table into Word (or similar) and replace “…” with the command you would issue at the bash command line to achieve each navigation goal.

Navigation goal	Command to type
Move down a level in the directory structure	…
Move up a level in the directory structure	…
Check your current location in the file system	…
From wherever you are, go to your home directory	…
Go to a location using its absolute path	…
Go to a location using its relative path	…


Step 2: File and directory creation and deletion
Now create a reference table and paste it into Word (or similar) for file and directory creation and deletion.

File management goal	Command to type
Add a directory as a subdirectory of the current location called foo	…
Remove the empty subdirectory called foo	…
Create an empty file called foo.txt	…
Delete the file called foo.txt	…


Step 3: Recreate this directory structure
Starting at your home directory, recreate the file and directory structure in the diagram below. The files can be created with sample extension as you like. e.g. HW1.docx, HW2.xlsx, project1.pptx etc...

Linux Virtual File Management Lab 

 <img width="2667" height="1500" alt="Linux Virtual File Management Lab Structure ImageFile" src="https://github.com/user-attachments/assets/2c66ccaf-4b7d-46d9-8594-116b609ea522" />


When you have completed this task, use the command ls -lR and compare the results to the diagram. If they are equivalent, you’re done. Create a screenshot that displays the ls -lR output.

After you create your screenshot, traverse to your home directory and remove all of the files and directories you just created using one command. Include this command in your answers below. Use the text and --help switch to figure out how to construct this command.


Step 4: Sloppy cybersecurity scenario
There’s a special server on your company’s network called privateserver. The security team is lazy and not particularly good at their job. I mean, who names a private server privateserver right? Something else they did was to give it a network address that is hidden… sort of. All you’ve been told is that the network configuration files on our server should be correctly configured so that a DNS search is not required to connect to privateserver.

Use the Fox textbook (chapter 5) as a resource to investigate what network configuration files exist, and which one(s) may have the answer to how our server can communicate with privateserver. Which file (or files) is/are likely to contain the configuration that your sloppy cybersecurity team is referring to.

Investigate the relevant Linux files and summarize your troubleshooting results in the Word document.
Create a screenshot that confirms you found the configuration necessary for communicating with privateserver.
You still can’t log in to privateserver so maybe the problem is on that server. Which network configuration files should the admin of that server look at to determine if the problem is that our server is allowed or disallowed log in to privateserver?
