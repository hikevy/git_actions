mv ~/.ssh/id_rsa ~/.ssh/id_rsa_backup
ssh-keygen -t ed25519
cat ~/.ssh/id_ed25519.pub
ssh -T git@github.com