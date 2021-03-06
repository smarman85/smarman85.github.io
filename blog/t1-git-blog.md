#Git Serious With Version Control
#### 09.18.14

What Is version control anyway?

  According to git-scm.com, “Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. “ This is a fancy way of saying if you mess up don’t worry about it, you have back ups.  Version control in a sense is like a time machine that lets you go back to previous sections of your work (Like back when your style sheets weren’t bloated with last minute fixes).

  Version control really starts to shine once it is introduced to a project where many developers are working on the same project. It allows multiple users to be working on the same project and not have any issues with things being overwritten or lost. In the event of an issue, you can roll back to a previous intact version.


How does it know what I change?

  Git uses an algorithm called <a href="http://en.wikipedia.org/wiki/SHA-1">SHA-1</a>, which is tech speak for Git making all the file contents into a pattern. It then uses that pattern to check against itself to see if anything has changed since the last commit.

  When you are making your commit, git begins to keeps track of four objects, a blob, a tree, a commit, and a tag. The contents of the file are saved within the blob by using the SHA-1 hash. This process gives the computer something to use to keep track of this file.

  The tree stores the names of files and directories, which reference blobs other directories and sub-directories. Information is stored in that same SHA-1 encoding. Any changes to the file name or structure, will result in a different SHA-1 code. This tells git, “Hey something is different with this file”!

  Commits represent the physical state of the tree at any given time( usually from the last commit or the current one.) And yet agin the information is stored in an SHA-1 encoded hash.

  Tags are a way of giving a special name to a commit. All this teamed together lets git know if you have made any code breakthroughs, and helps you get your work out to other developers on your team.


Still not git-ing on board?

  Aside from the benefits of having your code available to everyone on your team, git provides you with almost limitless options. Github gives you access to a huge number of open-sourced repos, which you can use to learn new tips and tricks from.

  Another great thing about Github, is the security it offers. Computers have made great strides in recent years, but they are not infallible. Github will be there to assure you that your code-baby that you have been working feverishly on for the past month and a half isn’t gone when you spill your coffee all over your logic board. There are many amazing reasons to use github to host your code, these are just a few to get you interested.



