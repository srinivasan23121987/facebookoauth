# Facebook-Oauth

GIT config Global

git config user.name her_username
git config user.email her_email
git commit --amend --reset-author
git config --global credential.helper cache
git config --global credential.https://github.com.username foo
git clone https://github.com/foo/repository.git


GIT-Credential-remove

start the ssh-agent in the background
ssh-agent -s

Agent pid 59566
So, Ctrl+Alt+Del and hit End Process to stop each 'ssh-agent.exe' process.

In 'Git Bash':

Start the 'ssh-agent.exe' process

eval $(ssh-agent -s)
And install the SSH keys

ssh-add "C:\Users\MyName\.ssh\id_rsa"

* Adjust the path above with your username, and make sure that the location of the* /.ssh directory is in the correct place. I think you choose this location during the Git installation? Maybe not...

Save the file in the editor. If it's Emacs: CTRLX CTRLS to save then CTRLX CTRLC to quit or if it's vi: 

:wq


