# install git
sudo apt-get install git

# generate & get ssh key
1.ssh-keygen                # enter enter enter  ....
2.cd ~/.ssh
3.ls			    # if id_rsa.pub cannot be found, try 1 again
4.cat ~/.ssh/id_rsa.pub     # copy this key to Github->Settings->SSH and GPG keys->SSH

# start your project
1.mkdir <dir_name>
2.cd <dir_name>
3.git init
4.git remote add origin <https://github.com/freshn/***********.git>

# online to local
git pull origin master

# locqal to online
git add <file_name> or . 
git commit -m "<description>"
git push origin master

