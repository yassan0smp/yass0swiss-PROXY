```bash
sudo apt update
sudo apt install git
```
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@gmail.com"
```
```bash
git init
```
```bash
git add .
```
```
git commit -m "Initial commit"
```
- Create a repository in your github manually and copy the link of this repository
---
YOU NEED TO DO THE BELOW PROCESS ONLY ONE TIME, ALSO MAKE SURE TO SAVE THE GENERATED KEY IN SOMEWHERE ELSE
- Now visit [This Link](https://github.com/settings/tokens/new) (If it ask password, then provide password)
- In the `Note` section write anything
- In the `Select scopes` sections select `repo` section and then click on Generate token
- Copy that token, this token will be used as passoword during github files upload
---
```bash
git remote add origin https://YOUR_GITHUB_USERNAME:ACCESS_TOKEN@REPO_LINK_BEGIN_WITHOUT_HTTPS_AND_END_WITH_.git
```
- Example : `https://yassan0smp:ghp_9MTyjo33qcebDGPrLvpntALJ6wLgYv3Vow6U@github.com/yassan0smp/Swisstronik-Testnet.git`
```bash
git remote set-url origin https://YOUR_GITHUB_USERNAME:ACCESS_TOKEN@REPO_LINK_BEGIN_WITHOUT_HTTPS_AND_END_WITH_.git
```
```bash
git branch -M main
```
```bash
git push -u origin main
```
- It will ask your `github username` and `github password` but in the `password` section u need to paste `the generated token` you copied earlier
- Done !!

