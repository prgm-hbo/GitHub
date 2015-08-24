====
Help
====

Creating a new branch as an orphan
==================================

https://coderwall.com/p/0n3soa/create-a-disconnected-git-branch

- Create a new branch with no parents (ex: gh-pages) ::

   git checkout --orphan <branche>

- Clear the working directory with ::

   git rm --cached -rf .

- Supprimer tous les fichiers du répertoire sous Windows (sauf .git)

- Make the first commit (README.md) ::

   "Initial commit"

- Clean the files leftover from "git rm" with "git clean" ::

   git clean -fdx

- Push the new branch to origin ::

   git push origin <branche>

Make the current commit the only (first) commit
===============================================

`A brute-force approach, also removes the configuration of the repo
<http://stackoverflow.com/questions/9683279/make-the-current-commit-the-only-initial-commit-in-a-git-repository>`_

- Remote repo on GitHub server
  
  Remove all commits from GitHub server: back to "Initial commit" !

  ::

      git push -f origin HEAD^:master

- Local repo on local disk
  
  Delete all, clone from server than add all files
  
  Supprime les fichiers
  $ git reset --hard
  
  Supprime l'historique
  des 2 derniers commits
  
  $ git reset --soft <commit-hash>
  $ git reset --soft HEAD~2
  
  
  $ git rebase --onto <commit-id>^ <commit-id>
  
  Old
  
   - Remove all history

     .. code-block:: bash
      
         rmdir .git
     
     or (...?)
     
     .. code-block:: bash
      
         $ git rm --cached -r .
         $ git reset --hard
      
   - Reconstruct the Git repo with only the current content

     ::
      
         $ git init
         $ git add .
         
   - Add repo to GitHub client and Publish

     or ::
     
         $ git commit -m "Initial commit"
         $ git remote add <repo> https://github.com/<user>/<repo>
         $ git push -u --force <repo> master

