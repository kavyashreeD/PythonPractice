Steps to be followed to use github on android phones
1. create the github account
2. install termux API and termux  apps in to the android phone
3. upon installation use the below command to install packages that would help you to work with github These all would take some time:
	apt update && apt upgrade
	pkg install git
	pkg install python
	pkg install vim
4. go to the mail and click on the assignment link sent or just copy paste the link in the browser, it will ask to login to the github account using mail id and password, so creating the account has to be carried out in the first place, later  the repository gets loaded and you will be taken to the github, on the phone you get the desktop site, open the same in desktop mode.
 
5. copy the url from the repository  and use the git command to clone the repository in termux
	git clone <Paste the URL of the repository>
example: git clone https://kavyashreeD/TesingPython/kavyashreeD.git
 
 
6. Now use ls command, list all the files
7. use cd the directory name which has the assignment name, please note it does not show the directory name in the command prompt
8. now you are with in the directory, use ls command and you see the all the files which are present in the directory.
 
9.use vim command to open the python file, you see the editor, press the key ‘I ‘ to insert or edit the file, use ‘ESC’ + ‘:’ + ‘wq’ to save the file and exit from vim editor
Example: vim data.py
 
10. run the python code using the command below, and check if the program executes or if it throws error, if error than you have to go back to the editor using vim command and follow the same steps as mentioned above 
Python data.py
11. once the program you edited is correct than you should add the file in to the repository using the add command. Please note for all the git operations you can use all the git commands in termux.
git add data.py
check the status:
git status
the above command shows no commits yet so please commit the work you have done so far and push the code back to repository.
git commit –m “added”
 
12. push the repo back
git push
it will ask user name and password of the github account which you have created. Please note the password will not be seen on the termux, not even ‘*’ so enter the password correctly and press enter, it pushes the repo back
 
13. use the exit command to get exit from the termux

