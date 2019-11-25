# Git-VSCode-Tutorial

How to use Git and Github with Visual Studio Code

** MAC IOS Instructions **

1. Install Git (https://git-scm.com)

2. Create SSH Keys
Terminal Commands:
```javascript
ssh-keygen -t rsa -b 4096 -C "YOUR_EMAIL@gmail.com"
eval "$(ssh-agent -s)"
ssh-add -K ~/.ssh/id_rsa_codrkai
pbcopy < ~/.ssh/id_rsa_codrkai.pub
```

3. Go to Git Hub --> Settings --> SSH & GPG Keys --> New SSH Key, then press CTRL + V to paste the key in. The key should have been copied to your clipboard when you entered the terminal command PBCOPY...

Your Github should now be linked with your SSH Public Key. Now create a Repository and click on "Clone" to copy the SSH URL. Go to VS Code and paste in the Git:Clone URL to start...


Some Basic Git Commands
```javascript
git status
git add .
git commit -m "ADD A COMMENT"
git push origin master
```
