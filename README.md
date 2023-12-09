# how-to-use-two-git-account-
instruction guide

1- genrate  a SSH Key using  ssh-keygen -t rsa -b 4096 -C "personal_email_id"
2 - save it in the ~/.ssh folder
3- make a config file 
   Host "name you want" github.com
    HostName github.com
    PreferredAuthentications publickey
    IdentityFile file path for ssh private
4 - add the ssh key to the git account
5-  to access that repo 
    copy the ssh link url
    then use 
    git clone git@"name you gave in host config".com:repo link
    
    
    
