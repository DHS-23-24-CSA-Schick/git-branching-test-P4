# git-branching-test
Used as a class test repo for experimenting with branching and permissions

For this assignment, each table group should have one student clone this repository:
```bash
git clone https://github.com/DHS-23-24-CSA-Schick/git-branching-test-P4.git
```
Next, move into the top level of the code and do the following:
```bash
git status
```
At this point both git status and git branch will tell you what branch you are on
```bash
git branch                           
```
Use your firstname and Lastname
```bash
git checkout -b FnameLastname
```
put all elbow partner names into the text file and save
```bash
nano firstname-lastname.txt
```
```bash
git add firstname-lastname.txt
```
```bash
git commit -m "adding our team's test file for ...."  (include initials) 
```
```bash
git push --set-upstream origin FnameLastname
```
Then look at the repo through the github web interface to see if your pull request was sucessful.  You may need me to check,
or your buildmasters (I will give them admin rights)

  
