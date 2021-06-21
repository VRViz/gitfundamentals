# git init   __% create local git repository in /folder
# git status __% shows present branch status
# git add readme.md  __% adds newly created file into staging area prior to commiting
# git add .   __% adds all changes into staging area  (remember to save the worked on file [STRG+S])
# git commit -m "specific commit message"   ___% commits all stages from staging area to present branch with -m <-message
# git checkout -b branch1   ___% create new branch with the name branch1
# git checkout master   ___% switch branch to master
# git merge master   ___% merge present branch with master branch
# git remote add origin https://github.com/VRViz/gitfundamentals.git   ___% add remote github repository
# git push -u origin master   ___% push all commits to remote origin master repository  (-u means saved settings, so >git push< will in future be enough to commit to origin master)