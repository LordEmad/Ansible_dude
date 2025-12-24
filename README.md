# Ansible_dude
holaaaaaaaaaaaaaa Amigoss
18/12/2025 10:57
--------------------------------

git clone git@github.com/LordEmad/Ansible_dude.git

git config --global user.name "dody"
git config --global user.email  "emad@gmail.com"
cat ~/.gitconfig


vi README.md 
git status
git diff README.md
git add README.md 
git status
git commit -m "Updatef Successfully"
git push origin main 


ansible all -m dnf -a "update_cashe=true"

                     --------------------First Playbook----------------------

- hosts: all
  become: true
  tasks:

     - name: install httpd package
       dnf:
          name: httpd
          state: present
       
       -------------------------------------Second Playbook----------------------

       
