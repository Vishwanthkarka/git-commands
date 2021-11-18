# git-commands

ls : list the directives 

mkdir project : making the project directives

cd project : changing the directive

cd..  : to move one step back to the directive

git init : to initilize empty git repositry or creating a hiden file in which the history of the files stored

ls -a : show the hiden files which starts which .

touch names.txt : To create text file

git status : to see the starts about files and folder 

rm folderORfile : to remove file or folder

e:  : to change the drive 

clear : to clear screen

git add . or file_name  : to add file in staging area (. strings for all the files in the same directive)

git commit -m "file_name file is added" : creating commit (m stands for message)

git log : to find list of git commits

git reset some_hashes_446665  : except the given hash of the commit all will be deleted 

git staged : you wanted to save but dont as a commit we use staged 

git  staged clear : to clear the staged

git branch name_of_branch : To create a branch (combination of the commit call branch )

git branch  : TO check the list of the branch out (The default branch is master)

git checkout name_of_branch : To move in to the branch 

git merge name_of_branch : to merge name_of_branch in to master branch 


---------   Github    ----------

git remote add origin http//github.com/your_rep.git  : this will help in uploading the content to github

git remote -v  : to view acces like fetch and push 

git push origin master  OR git push orgin feature_branch: to push to the github (if you view enter your personal acess token move to settings > Development settings > personal token )

IMP : same command is use to push updated content 

IMP : To push the another_branch we use git push origin another_branch

Imp : the folder which start with your name is called origin 

git clone https//github/username/repo.git  : this for cloning the project to local position

git remote  add upstream https//:github.com/othersproject/project_name.git  : upstream is mean by from where we had fock it 

IMP : make sure to create a branch for every bug or feature (pull request is branch )

git origin name_of_branch -f : f for force when you wanted to repush the changes or deleted few commit we need to do force push

git fetch --all --prune  : to fetch all the branch and , prune mean deleted branches also
