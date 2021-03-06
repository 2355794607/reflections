What happens when you initialize a repository? Why do you need to do it?
    When initalize a repository, git will create a .git directory that contains bunch of metadata about the history of the repository. A directory that haven't been initalized is just a normal directory, it can't be tracked by git.
How is the staging area different from the working directory and the repository?
What value do you think it offers?

    Staging area is the preparation area for files to be committed. Only files in this area are going to be included in the commit executed next time. It helps to divide changes in the working directory into several commits, each of which consists of a group of changes that represent a logical change to the relavant files.

How can you use the staging area to make sure you have one commit per logical
change?
    If I've made more than one logical change since committing, I can add all the changes affected by the first logical change to the staging area, then commit those without committing the others.
What are some situations when branches would be helpful in keeping your history
organized? How would branches help?
    When you want to try adding an experimental feature while keeping your code working without breaking. To do so, keep your master branch clean of any untested changes, instead make an experimental branch for any new feature that needs experimenting. After the new functionality gets stable enough to go into the master branch, you could merge the experimental branch into the master.
How do the diagrams help you visualize the branch structure?
    The diagrams show what the parent of each commit is and when the branch was created.
What is the result of merging two branches together? Why do we represent it in
the diagram the way we do?
    Merging two branches incorporates the changes from two branches into a new commit. This allows developers to create new features or work independently of one another and then combine their efforts into a working version without stepping on each other's toes. It is represented in the diagram as two branches coming together because that is effectively what is happening.

What are the pros and cons of Git’s automatic merging vs. always doing merges
manually?
    Pros: 
    	Saves your time, especially when each non-conflicting merge is trivial.
    	Makes you concentrate on the changes which actually contain conflicts.
    Cons:
    	The atuo merging is not perfect at all, you should clean the conflicts manually.