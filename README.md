# ANSIBLE
this is my Ansible respository!
GIT RESPOSITORY LINUX

Core consepts only 

$ which git # shows where git is stored if not you can install (sudo apt install git) 

syseng@DLS-PC027:~$ which git
/usr/bin/git

Create an account web browseer github.com   taylorle@outlook.com  =Ds_082013 username= l31tay

===========================================================commands to add and edit and upload===================================================================

  174  which git
  175  cat .ssh/id_ed25519.pub    #copy key and add to git account 
  176  git clone git@github.com:l31tay/ANSIBLE.git
  177  ls
  178  cd ANSIBLE
  179  LS
  180  ls
  181  cat README.md
  182  git config --global user.name "Lee Taylor"         #  add account 
  183  git config --global user.email "taylorle@outlook.com"#
  184  cat ~/.gitconfig
  185  nano README.md
  186  cat README.md
  187  git staus
  188  git status
  189  git diff README.md
  190  git add README.md
  191  git status
  192  git commir -m "update readme file, initial commit"
  193  git commit -m "update readme file, initial commit"
  194  git push origin master
  195  git status
  196  git checkout -b master
  197  git push origin master
  198  history

=============================================================================================================

================================ANSIBLE RUNNING COMMANDS========================================================================



$ ansible all -m apt -a update_cache=true --become --ask-become-pass            #ALLOWS YOU TO USE SUDO PRIVALLIGES

$ ansible all -m apt -a name=vim-nox --become --ask-become-pass                 #installing other package example

============================================Playbook=============================================================================

Create a playbook use comand below and format of the table 


$ nano install_apache.yml   # and create the file ====


========================================================================
=============================Table===========================================

---


#- hosts: all
#  become: true
# tasks:

#  - name: install apache2 package
#    apt:
#     name: apache2


===========================================================================
==============================================================================


