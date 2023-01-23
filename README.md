# Beginner
# Devops-Tools
## Road Map for a Devops
![Tux, the Linux mascot](/Beginner-/IMAGES/Devops-roadMap.png)
### Road Map for a Devops
![Tux, the Linux mascot](/Beginner-/IMAGES/devops-roadmap2.png)
### Devops Tools EcoSystem
![Tux, the Linux mascot](/Beginner-/IMAGES/devops-tools-ecosystem.png)
# **GIT**
# **What is meant by Version Control ?**
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.
# **Local Version Control Systems**
![Tux, the Linux mascot](/Beginner-/IMAGES/localversioncontrol.png)
One of the most popular VCS tools was a system called RCS, which is still distributed with many computers today. RCS works by keeping patch sets (that is, the differences between files) in a special format on disk; it can then re-create what any file looked like at any point in time by adding up all the patches.
# **Centralized Version Control Systems**
The next major issue that people encounter is that they need to collaborate with developers on other systems. To deal with this problem, Centralized Version Control Systems (CVCSs) were developed. These systems (such as CVS, Subversion, and Perforce) have a single server that contains all the versioned files, and a number of clients that check out files from that central place. For many years, this has been the standard for version control.
![Tux, the Linux mascot](/Beginner-/IMAGES/centralizedversioncontrol.png)
# **Distributed Version Control Systems**
This is where Distributed Version Control Systems (DVCSs) step in. In a DVCS (such as Git, Mercurial,Bazaar or Darcs), clients don’t just check out the latest snapshot of the files; rather, they fully mirror the repository, including its full history. Thus, if any server dies, and these systems were collaborating via that server, any of the client repositories can be copied back up to the server to restore it. Every clone is really a full backup of all the data.
![Tux, the Linux mascot](/Beginner-/IMAGES/distributedversioncontrol.png)
# **What is Git?**
Git is a version control system for software development. It allows multiple developers to work on the same codebase simultaneously, and keeps track of all changes made to the code over time.
Git allows developers to create "branches" of the codebase, which can be used to develop new features or fix bugs without affecting the main codebase. When a developer is finished working on a branch, they can "merge" their changes back into the main codebase, which is called "master" branch.
One of the main advantages of using Git is that it allows developers to easily revert back to previous versions of the code, in case something goes wrong. It also allows for easy collaboration with other developers, as changes made by one developer can be easily reviewed and approved by others.
Some popular Git hosting services include GitHub, GitLab and Bitbucket. These services provide a web-based interface for managing Git repositories and make it easy to collaborate with other developers.
# **The Command Line**
There are a lot of different ways to use Git. There are the original command-line tools, and there
are many graphical user interfaces of varying capabilities.
# **Installing Git**
## **Installing on Linux**
If you want to install the basic Git tools on Linux via a binary installer, you can generally do so through the package management tool that comes with your distribution. If you’re on Fedora (or any closely-related RPM-based distribution, such as RHEL or CentOS), you can use dnf:
## **$ sudo dnf install git-all**
If you’re on a Debian-based distribution, such as Ubuntu, try apt:
## **$ sudo apt install git-all**
