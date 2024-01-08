## Git Setup

### How to generate https and connect with github

1. git config --global user.name "iamarbabkhan"
2. git config --global user.email "arbabkhan579@gmail.com"
3. ssh-keygen -t rsa -b 4096 -C "arbabkhan579@gmail.com"
4. eval "$(ssh-agent -s)"
5. ssh-add ~/.ssh/id_rsa
6. cat ~/.ssh/id_rsa.pub
7. git remote add origin https://github.com/iamarbabkhan/demo.git
8. cd repo
9. git init
10. git add .
11. git commit -m "commit message"
12. git push origin main

### How to resume work using https with github
1. cd repository
2. git remote -v
3. git fetch --all
4. git config --global credential.helper cache
5. git config --global credential.helper 'cache --timeout=3600'
