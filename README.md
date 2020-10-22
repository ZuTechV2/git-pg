# Method 1: Add each file individually 
git add source-code/index.html 
git add README.md
# Method 2: Add all files in current directory 
git add .

If you already know the basic Git terms and how to commit, push, and pull, then you can skip down to the section named A Simple, Effective Git Workflow. If you are completely new to Git, this section will teach you everything you need to know to successfully use Git.
Source Code — this is a fancy term for “all the code that belongs to a project in its original state”
1. Repository — A “repo” is another word for a bunch of source code.
2. Branch — An essential concept of Git in general. Each repository can have multiple branches. Each branch can have unique source code.
3. Remote — this word could mean a lot of things, but in the context of Git, it refers to the version of the repo that is sitting on a server somewhere (in most cases, it refers to the version of a repo which lives on Github’s servers).
4. Local — this word could also mean a lot of things. It refers to the version of the repo that is sitting directly in front of you on your physical machine. It is literally the code that is written to the disk on the computer sitting in front of you. One caveat to this is if you are running Git from a virtual machine. In that case, your repo is being stored on a remote virtual machine and a remote server, but this does not really matter. Just think of the “remote” as “Github” and “local” as “my computer”.
5. Commit — This will make more sense in a moment, but it is the action of “saving” your changes with a “receipt of save”. This is different from saving a document to your computer because once you save that document, you cannot go back to the previous version before the save unless you had made another copy of the document. In Git, you can go back to the previous version of the save, which is referred to as “reverting to the previous commit”.
6. Push — Once you have “saved” (committed) at least one time, you can push those changes to your remote repo.
7. Pull — This means that you are retrieving new changes from your remote repository and updating them in your local version of the repo. You will see why this is useful when we start talking about multi-contributor code projects.
8. Clone — This means you are creating a “copy” of an entire repository. There can be an unlimited number of repo copies stored on an unlimited number of local machines that all push their changes up to the remote repo (i.e. Github).
9. Origin — This refers to the HTTP URL or SSH identifier for a specific remote repository and is how we push/pull to and from our local/remote repos.
