# Introduction to GitHub

### Table of content 
- [Introduction](#introduction) 
- [What is GitHub?](#whatisgithub) 
- Why GitHub
- Git vs. GitHub
- Clone (Show how to do cloning)
- Pull request (Show how to do a pull request)
- Commit (Show how to do a commit)
- [GitHub Desktop vs. Github CLI](#githubdesktopgithubcli) 
- Conclusion

### <a name='introduction'>Introduction</a>
Git is a widely used version control system, designed for collaboration.
GitHub is weg-based hosting platform for git.

### <a name='whatisgithub'>What is GitHub</a>
According to W3Schools, GitHub is a code hosting platform for collaboration and version control. GitHub lets you (and others) work together on projects.

### Why GitHub?
There are other hosting platforms using git, but GitHub is peculiar with its user friendly interface; features like public repository, issues, pull request, milestones.

### Git vs. GitHub
Git: Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows. 

GitHub: GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features. 

S.No. | Git | GitHub
1. | Git is a software. | GitHub is a service.
2. | Git is a command-line tool | GitHub is a graphical user interface
3. | Git is installed locally on the system | GitHub is hosted on the web
4. | Git is maintained by linux. | GitHub is maintained by Microsoft.
5. | Git is focused on version control and code sharing. | GitHub is focused on centralized source code hosting.
6. | Git is a version control system to manage source code history. | GitHub is a hosting service for Git repositories.
7. | Git was first released in 2005. | GitHub was launched in 2008.
8. | Git has no user management feature. | GitHub has a built-in user management feature.
9. | Git is open-source licensed. | GitHub includes a free-tier and pay-for-use tier.
10. | Git has minimal external tool configuration. | GitHub has an active marketplace for tool integration.
11. | Git provides a Desktop interface named Git Gui. | GitHub provides a Desktop interface named GitHub Desktop.
12. | Git competes with CVS, Azure DevOps Server, Subversion, Mercurial, etc. | GitHub competes with GitLab, Git Bucket, AWS Code Commit, etc.

https://www.google.com/amp/s/www.geeksforgeeks.org/difference-between-git-and-github/amp/


### Clone (Show how to do cloning)
The git clone command is used to create a copy of a specific repository or branch within a repository.

 git clone https://github.com/github/training-kit.git

https://github.com/git-guides/git-clone


### Pull request (Show how to do a pull request)
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.

Find a project you want to contribute to
Fork it
Clone it to your local system
Make a new branch
Make your changes
Push it back to your repo
Click the Compare & pull request button
Click Create pull request to open a new pull request

https://www.google.com/url?sa=t&source=web&rct=j&url=https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests&ved=2ahUKEwjIzrje0M_6AhWQgv0HHfswDn4QFnoECBgQAQ&usg=AOvVaw3116VoAsTnmTzTPvlC3Vuf

https://opensource.com/article/19/7/create-pull-request-github


### Commit (Show how to do a commit)

The git commit command captures a snapshot of the project's currently staged changes. Committed snapshots can be thought of as “safe” versions of a project—Git will never change them unless you explicitly ask it to. Prior to the execution of git commit, The git add command is used to promote or 'stage' changes to the project that will be stored in a commit. These two commands git commit and git add are two of the most frequently used.
https://www.atlassian.com/git/tutorials/saving-changes/git-commit
git commit -m "commit message"


### <a name='githubdesktopgithubcli'>GitHub Desktop vs. Github CLI</a>

GitHub CLI is an open source tool for using GitHub from your computer's command line. When you're working from the command line, you can use the GitHub CLI to save time and avoid switching context.

Gitub CLI is different from Git CLI. GitHub CLI is specific to GitHub, uses gh; while Git CLI can be used for other Git hosting platforms like Bitbucket, uses git.

GitHub CLI includes GitHub features such as:

- View, create, clone, and fork repositories
- Create, close, edit, and view issues and pull requests
- Review, diff, and merge pull requests
- Run, view, and list workflows
- Create, list, view, and delete releases
- Create, edit, list, view, and delete gists
- List, create, delete, and connect to a codespace
https://docs.github.com/en/get-started/using-github/github-cli

GitHub Desktop is an application that enables you to interact with GitHub using a GUI instead of the command line or a web browser. GitHub Desktop encourages you and your team to collaborate using best practices with Git and GitHub.
https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop

### Conclusion
Git is different from Github. Also Git CLI is differennt from GitHub CLI.

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
