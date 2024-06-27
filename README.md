How I did the following tasks:	 


I created a new repository onto my Github account named PLPBasicGitAssignment, plus added a README file, I then opened my Command Prompt and typed: 


mkdir PLPBAsicGitAssignment  


To create the folder in my local machine after I typed:


cd  PLPBasicGitAssignment


To steer the created folder after typed:


git init


After I typed: 


git remote add origin https://github.com/mbalipaile/PLPBasicGitAssignment.git
for me to connect to my GitHub respository. I then created a txt file via my command prompt which I then typed:


echo "Hello Git!"> hello.txt 


Then after I typed:


git commit -m "Add hello.txt with a greeting"


To make commit changes. Thereafter I typed: 


git push -u origin main


Then it gave me an error message which was: error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/mbalipaile/PLPBasicGitAssignment.git'


Then I had to troubleshoot and looked if I was in the correct directory, which I was, then I typed:


git branch


Which gave me: * master


Then I decided to push it into the master branch instead so I typed: 


git push -u origin master


Which appeared onto my master branch and everything was pused to my master branch. 
Thats how I completed my tasks and pushed everything to my Master branch. Thank you. 
