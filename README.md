# Training

git hub training



Jargon

Working Tree --> local file explores



To do at the training

\[x] New file

\[x] What GitHub does

\[x] What makes a good commit

\[x] Publishing to repository

\[x] Cloning from repository

\[x] Reverting a publish

\[x] Analogy - Russian doll

\[x] Branches



**What git hub does:**

* You save normal files (.doc, .csv, .txt) to the local drive (file explorer)
* Make edits to those on the normal interface

 	- GitHub tracks these changes in the repository and will show you those changes

* When you want to commit and save these changes as like "official" changes/versions that you want to track

 	- Commit these to the repository with a bit of a summary to the update

 	- All these little changes won't be committed (like the typing, deleting etc)

 	- But the difference between the previous commit and the most recent commit will get saved



**What makes a good commit**

* Atomic and orthogonal

 	- does one whole thing

 	- one thing at a time - makes it easier to undo one thing at a time

* E.g.

 	- One whole new feature

 	- one bug fix



**Publishing to repository**

* Publish to repository and this is like a back-up
* Saves to the repository and is good for collaboration



**Cloning from repository**

* Then can clone from repository
* e.g. if you delete or lose laptop
* Can clone the repository from git back to the local drive



**Reverting a publish**

* If you commit and publish a commit
* And the right-click and revert commit, it will go back to the previous version and you can decide to publish this
* But this will undo any changes you have made



**How GitHub workflow works**

* Work on the thing locally in your files
* Save it in your files

 	- GitHub tracks these changes

 	- Can undo on the file itself

* Committing sends it to repository limbo

 	- Getting ready to send it to the online repository

 	- Can undo by "undo commit" so this won't get pushed

* Pushing sends it to online repository

 	- Uploaded to the repository and backed up

 	- Can undo by reverting

 	- This will revert back to what it was before the push

 	- Takes it back to repository limbo

 	- If you want this version, you can push this and it will go back to the version before

 	- If you don't want this, you can undo the commit and it will undo the revert



**Undo revert**



**Branches**

* Branches allow you to work on a shared document on a separate branch (like a copy)
* You can make changes it to it separately, and it won't do anything to the main files

 	- Depending on the branch that you are on GitHub desktop will change what you see in 	the file explorer

 	- Then you push the branch version to the repository

 	- And do a pull request

 	- This can be reviewed, checked and if ok it can be merged with the main version, and 	it will override the original but track the history of the versions before, if it needs 	going back to

* Once its been merged online, you need to pull it on the githib desktop
* Then the other branch is outdated and can be deleted 



**Merging and Merge requests** 

* 
