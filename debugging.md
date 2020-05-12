HOW TO DEBUG
										rebeccabartels

So you have an error.  NOW WHAT? 
Step 1: Take a breath
Errors are normal and not bad.  You will be seeing and solving them always. 


Step 2: COPY AND PASTE IS YOUR BEST FRIEND.Open up your browser and Copy And Paste your Error message in the URL-bar then press Enter. 
Just copy and paste the whole thing in the URL bar and see what it gets you! 
If nothing of value appeared from your search, 
then try Copying and Pasting line by line to see what may pull up the most relevant and helpful resources
Take note of the terms that pull up the most results.  
	Optional: Make a document and store those key terms that helped you find this bug. 
	Optional: Store the solution in a cheat-sheet of your own to reference later (a google-doc, a journal, an encrypted .txt file hidden in a Swedish server, whatever) 

Step 3: Learn your “GOOD” and “EH” sources 
Searching on BING/GOOGLE/YAHOO or whatever browser will list hundreds of results. Here are a few tips on how to shave the records down by adding parameters: 
Date: Look for the most recent entries / resources by date 
Content: Learn how to read the commentary on Stack Overflow and Reddit debugging forums.  This will make isolating your answer easier. 
Safety: Stay away from outdated websites or non-secure websites
If the program you’re building has documentation, read it before you install so you know what you’re up against.  Sometimes, just reading the docs ahead of time can save you a bunch of errors. 
Short-Cuts: Utilize “CTRL + F” when you are on a webpage with a long list of results.  Here are some more shortcuts that will cut your debugging down if you commit these to memory: 
CTRL + F will FIND string input on the page immediately. You can paste key terms or code into CTRL + F and then see if the terms appear on the page rather than scrolling through and reading everything.  (We’re hackers, we like to get things done quick.)  
CTRL + T will open a new tab
CTRL + N will open a new browser window 
Shift CTRL + i will open the DEV console




Step 4: USE Key-Words to Filter your Queries 
Being a good debugger means isolating the most relevant keywords of your error messages into your browser and seeing if anything appears that fit your parameters. 
IMPORTANT: Make sure to include your OS model and your program in your query 
Example: 
I’m downloading metasploit on ubuntu and encounter an error. My search query should include “metasploit” and “ubuntu” and ubuntu’s version and then the error and or keywords.  That way, your results will only pull up your OS specs and not others. 
Example: 
Selecting previously unselected package code. (Reading database ... 340375 files and directories currently installed.) Preparing to unpack code_1.30.2-1546901646_amd64.deb ... Unpacking code (1.30.2-1546901646) ... dpkg: dependency problems prevent configuration of code: code depends on libgconf-2-4; however: Package libgconf-2-4 is not installed. dpkg: error processing package code (--install): dependency problems - leaving unconfigured Processing triggers for gnome-menus (3.13.3-11) ... Processing triggers for desktop-file-utils (0.23-4) ... Processing triggers for mime-support (3.61) ...


Where is the error? Locate in red. You could search for this in many ways, one way is to just copy and paste the error after your machine declaration like below: 
Kali 2020.1a VSCODE error dependency problems prevent configuration of code: code depends on libgconf-2-4; however: Package libgconf-2-4 is not installed. dpkg: error processing package code (--install): dependency problems - leaving unconfigured 
	You could probably shave this error down even more and find one of the possible solutions. 


Step 5: Trial and Error
Take the results from your resources and plug them into your terminal/program to try to resolve. Take note of the result and try to understand it.  
Don’t be afraid of moving on if something doesn’t work. 
Don’t be afraid to play with the code and modify it upon entry into the terminal.  Sometimes, certain commands don’t have permissions enabled to execute properly. Adding “sudo” before your command may resolve this issue because “sudo” gives administrative privileges to you temporarily executing the command. 
After you have found a line of code that works, document it and save the page you found it on in your organized bookmarks.  It’s important to keep track of these errors because the more you solve, the more you will memorize.  Having an organized bookmarks bar will help you keep track of what has worked for you in the past and can help you quicken your search queries in the future. 


Step 6: Approach the TA’s and the Instructor with your findings! 
Let’s say you still haven’t found the solution.  After doing ALL OF THE ABOVE, you will have tried and failed at a few things.  Keep track of those few things, what happened, and present them to the instructors.  This will help us help you faster and will put you in more control of your own debugging process, which is the goal! We want you to be bug masters! 

Step 7: CELEBRATE! 
For every bug you solve, you deserve a pat on the back. Don’t be afraid to celebrate the tiny victories! With each bug you defeat, you level up as a hacker, AKA Bug Annihilator, or whatever you want to call it!


Step 8: Contribute! 
If you notice a bug reoccurring for several people or yourself, if you solve it, you will be helping your classmates.  Take this opportunity to work as a team and support each other by sharing your debugging experience in the class slack! 
If you solve a very serious or big bug, you can contribute to the curriculum to make the process better for future students. 
Have a suggestion on how to improve this guide? Let us know what narrowed down your query results. 
If your bug hasn’t been documented before on the internet, you can even submit a bug report for an application to the actual company. 
Happy debugging! 


