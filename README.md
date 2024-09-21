1. 'git init' -> powers yourfolder to managed by git, and initialise the empty git repository.
              It also contain .git file which hold all the relevent logics to maintain the 
              versions of your project

2. 'Working arra' -> There can be bunch of files that are not currently handled by the git.
                     It states that the change done or to be done in those files are not managed by the git yet.
                     A file which is in working area is not considered in staged area.
                     untracked files are in working area only

3. 'Staging Area' -> what all files are going to be part of the next version we will create.
                     this staging area is the place where git knows what changes will be done from the last version 
                     to this version

4. 'repository Area' -> This area actually contains the details of all your previous registered version
                        And files in this area, git already knows their version history

5. 'git add <file>' -> adds file from working to the stage area

6. 'git rm --cached <file>' -> moves file from the staged are to the working area

7. 'Commint' -> Commit is a particular version of the project. it captures the snapshot 
                of the projects stage changes and create a version of it.

8. 'git commit' -> registers staging changes to a commit

9. 'git log' -> list down all commit of the repository. if you want to exit the git log prompt press 'q'.

10. 'git restores <file>' -> it removes all file changes from the staging area to be committed

11. 'git restore --staged <file>' -> it remove file from changes from staging area to the working area

12. diff between git rm and git restore
    ans: when we need to convert the whole file back to untracked then we do git rm. otherwise to move 
    betwwen staging and working area we do git restore

13. 'git diff' -> used to know the difference between two commited versions

14. 'git commit -m"<your commit message>"' -> if we want to avoid opeing of the vimo/nano code editor for commit message

    d8538270c05028271365149ea3b681215b0c8114    e6e1b1b6ca7e4085e5b539647a590eb2ef5a3841


15. 'git remote' -> list down all the connection names

16. 'Remote connection' -> it  helps you to link two git repositories for uploading and downloading changes from each otherwise 

17. 'git remote rm <name of remote>' -> this command deletes a remote connection

18. 'git remote rename <oldname> <newname>' -> this command renames the git remote

19. 'git remote add <name of remote> <link of remote>' -> this commmand helps us to add a new link to the remote repo and give a name to it

NOTE : the name of the remote connection is always used to establish communnication between repos.