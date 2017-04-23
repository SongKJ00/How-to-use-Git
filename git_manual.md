1. sudo apt-get install git-core	//To install git 
2. git config --list	//A list of basic configuration
3. git config --global user.name "name"
   git config --global user.email "emailaddress"
 	//Add user's information.
4. git config --global color.ui "auto"	//set color for easy determine
5. mkdir Test	//make a new directory 
6. sudo git init	//create a new git repository
7. vi README	//create a new file which you will add to repository
8. sudo git commit -m "explanation of this file" //step of comfirmation by using command 'commit'
9. sudo git log	//confirm changed log
10. sudo git remote add origin remoteserveraddress	//let git know where the remote server address is ex) sudo git remote add origin https://github.com/SongKJ00/How-to-use-Git.git
11. sudo git push origin master //update your file to github repository
