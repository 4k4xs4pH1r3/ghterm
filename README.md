# GitHub Terminal

This guide is for you can login in your GitHub account, using Linux terminal and Microsoft Visual Code, so execute as root:

#
      sudo apt install libsecret-1-0 libsecret-1-dev -y && cd /usr/share/doc/git/contrib/credential/libsecret && sudo make && git config --global credential.helper /usr/share/doc/git/contrib/credential/libsecret/git-credential-libsecret
#      
      git config credential.helper
#      
      git config --global user.name "yourusername"
#      
      git config --global user.email "youremail"
#      
      git config --global credential.helper cache
#      
      git config --list      
#      
      git config --global core.editor "code -wait --user-data-dir"
#
      git config --global -e
      
      
      Now follow this instructions https://github.com/microsoft/Git-Credential-Manager-for-Mac-and-Linux/blob/master/Install.md 
