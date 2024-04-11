# Git and Version Control

## What is Version Control?

Version control, also known as source control, is the practice of tracking and managing changes to software code. 
Version control systems are software tools that help software teams manage changes to source code over time. 
As development environments have accelerated, version control systems help software teams work faster and smarter. 
They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

Version control software keeps track of every modification to the code in a special kind of database. 
If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake 
while minimizing disruption to all team members. 
Popular version control systems include Git, Subversion (SVN), Mercurial, and Perforce. 
Git, in particular, has become widely adopted due to its speed, flexibility, and distributed nature. 
It's commonly used in software development but can also be applied to manage various types of files and projects.


## What is Git? How does it work?

Git is a DevOps tool used for source code management.
It is a free and open-source version control system used to handle small to very large projects efficiently. 
Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development. 
Linus Torvalds created Git in 2005 for the development of the Linux kernel.<br><br>
*Let’s explain a scenario before Git:*

* Developers used to submit their codes to the central server without having copies of their own.
* Any changes made to the source code were unknown to the other developers.
* There was no communication between any of the developers.

![Picture1](https://www.simplilearn.com/ice9/free_resources_article_thumb/business.JPG)

*Now let’s look at the scenario after Git:*
* Every developer has an entire copy of the code on their local systems.
* Any changes made to the source code can be tracked by others.
* There is regular communication between the developers.

![Picture2](https://www.simplilearn.com/ice9/free_resources_article_thumb/business-org.JPG)

## Examples of basic workflow commands in git

````
git init
````
The git init command creates a new Git repository. 
It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.
Most other Git commands are not available outside of an initialized repository, 
so this is usually the first command you'll run in a new project.
````
git status
````
The git status command displays the state of the working directory and the staging area. 
It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git. 
Status output does not show you any information regarding the committed project history.
For this, you need to use ```git log```.
````
git add
````
The git add command adds a change in the working directory to the staging area. 
It tells Git that you want to include updates to a particular file in the next commit.
However, git add doesn't really affect the repository
in any significant way—changes are not actually recorded until you run git ```git commit```.
````
git commit -m
````
A "git commit" is a command in the Git version control system that records changes made to the files in a repository. 
When you commit changes in Git, you are essentially saving a snapshot of the current state of your project.
Each commit has a unique identifier (hash) and includes information such as the author, timestamp, and a message describing the changes made in that commit.



