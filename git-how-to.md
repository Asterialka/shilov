#How do I create an ssh key?
To do this, we need to register in the terminal:
ssh-keygen -t ed25519 -C "email"
#How do I add it to github?
To do this, we need to go to settings-ssh-new_ssh and upload our public key there
Then use
ssh-add and everything is ready, you can use
