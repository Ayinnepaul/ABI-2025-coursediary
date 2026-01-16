Git has local and remote repositories.
the 3 main components of the "local git" ie the version stored in your hard drive include:
the working directory --> the storage location of your files
the staging area --> where changes are organised for storage in the local repository
the local repository --> this is where the changes are stored (likely as binary files)


BASIC COMMANDS
git add "filename"" --> moves file to staging area
git status "filename" --> displays status of staging area contents
git commit "filename" --> moves file from staging area to local repository
git restore "filename" --> moves file from the staging area to the working directory
git push --> synchronises changes (commits) **to** the remote
git pull --> synchronises changes (commits) **from** the remote 
