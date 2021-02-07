# Definition
* **Repository:**
    *It's a collection of commits, branches and tags to identify commits. A repository contains all of your project files and each file's revision history.*

* **Clone:** 
    *Cloning is creating a local copy of the repository in your computer. We can make changes locally and push it to the main repository.*
  
* **Fork:**
    *Instead of using a single server-side repository to act as the “central” codebase, forking gives every developer a server-side repository. This means that each contributor has not one, but two Git repositories: a private local one and a public server-side one.*
  
* **Branch:**
    *A branch represents an independent line of development.The most recent commit on a branch is referred to as the tip of that branch. The tip of the branch is referenced by a branch head, which moves forward as additional development is done on the branch.It is like a pointer to a commit.*
  
* **Commit:**
    *It stores the current contents of the index in a new commit along with a log message from the user describing the changes*
  
* **Merge:**
    *To bring the contents of another branch into the current branch. In the case where the merged-in branch is from a different repository, this is done by first fetching the remote branch and then merging the result into the current branch. In simple words, it is joining two or more commit histories.*
  
* **Checkout:**
    *Checkout is the act of switching between different versions of a target entity. The git checkout command operates upon three distinct entities: files, commits, and branches.*
  
* **Push:**
    *The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repository. Remote branches are configured using the git remote command. Pushing has the potential to overwrite changes,* **caution should be taken when pushing**.
  
* **Pull:**
    *The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Once the content is downloaded, git pull will enter a merge workflow. A new merge commit will be-created and HEAD updated to point at the new commit.*
  
* **Git Remote:**
    *Git remote is a pointer that refers to another copy of the repository that is usually hosted on a remote server. With git remote, we can add/remove/show.*
  1. Git Add: The git remote add command will create a new connection record to a remote repository. After adding a remote, you'll be able to use as a convenient shortcut for in other Git commands.
    2. Git Remove: Git remote is a pointer that refers to another copy of the repository that is usually hosted on a remote server.
    3. git-show is a command line utility that is used to view expanded details on Git objects such as blobs, trees, tags, and commits. git-show has specific behavior per object type. Tags show the tag message and other objects included in the tag.