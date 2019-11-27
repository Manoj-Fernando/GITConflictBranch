# GITConflictBranch
To check the conflict and resolve options.


Do the following for resolving the CONFLICTS:
=============================================

1. First commit your changes to the local / Stash the changes using the folllowing:
    git stash
    To Unstash => git stash pop

2. Now do a Pull or Fetch & Merge. (Conflict Will happen is changes were there in repo)

3. Open the editor of your choice 

  <<<<Head => Changes from upstream
  ======== => To differentiate your changes and upstream changes.
  >>>>>>>> => Your Changes
  
4. Manually resolve the conflicts and commit and push it in the normal way you do it.

5. Be Happy :)
