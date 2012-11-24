What is it
==========
The goal of this scripts is to have multiple hooks files for a repository.

How to use it
=============
In a single git repository

   cd your/new/repository
   git init .
   cd .git
   rm -r hooks
   git clone https://github.com/MatthieuBizien/git-hook-manager.git

In all yours new git repositories:

   cd /usr/share/git-core/templates/ # or something like that
   sudo git clone https://github.com/MatthieuBizien/git-hook-manager.git

