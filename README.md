# 121_Sample_Codes

## Steps to Clone Repository in Local Machine:
1. Open git bash
2. Go to the directory where you want to save the project ```cd <directory/here>```
3. To clone the project run the following cmd ```git clone <link of the project>```
4. The should now be download to your local machine

## How to Work with GitHub
1. Start by going to the directory of the project you are working on ```cd <directory/here/project-name>```
2. Open the project using any IDE (VS Code, Eclipse, Notpad++, etc)
3. Before on a project it is a standard to first pull the latest branch ```git pull```
4. Now checkout the branch where you want to place your code ```git checkout <branch-name>```
5. Add the changes you want to apply
6. Create a new branch for the changes you've applied ```git checkout -b <branch-name>```
7. Add the files that you what to commit ```git add .```
8. Commit the changes ```git commit -m "<description of changes>```
9. After commiting all the changes you can now push your changes into the remote branch ```git push <origin> <branch-name>```
10. By this time you should now ba able to see your changes in the github project
### The following steps may now vary (depends on company, team, standard, etc)
11. Create a Pull Request (PR/MR)
12. Select the base branch (where you want to apply the changes) and compare branch (branch containing your changes)
13. Add a title and description for your PR
14. Assign the PR to your Tech Lead (TL) or any one who can review you code
15. After reviewing and resolving comments your branch will now be merge to the base branch 
