### apptky6
---

```
ssh-keygen -f ~/.ssh/id_rsa
ssh-keygen -f ~/.ssh/id_rsa_github
ls -al
vi ~/.ssh/config
/*
Host github.com
  User git
  HostName github.com
  IdentityFile ~/.ssh/id_rsa_github
IdentitiesOnly yes
*/
ssh -T git@github.com

CREATE APPTKY6

echo "### apptky6" >> README.md
git init .
git add .
git commit -m "1st"
git remote add origin git@github.com:takagotch/apptky6.git
git push -u origin master

```






