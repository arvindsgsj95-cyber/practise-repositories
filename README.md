# practise-repositories
practise-repositories
cd /opt/

sudo dnf update -y

sudo dnf install git nginx -y

sudo systemctl start nginx

sudo systemctl enable nginx

ls -ld /var/www/html

mkdir -p /var/www/html

git clone https://github.com/arvindsgsj95-cyber/practise-repositories.git

dir

cd github-repository/

git status

mkdir arvind

chmod 655 arvind

cd arvind/

vi index.html
<h1>CI CD Working Successfully</h1>

ls

git add index.html

git status

git commit -m "change by arvind"

git branch

git push

ssh-keygen -t rsa -b 4096

ll

cat ~/.ssh/id_rsa.pub

sudo dnf install nodejs -y

node -v

npm -v

npm init -y

vi .gitignore

-------------

node_modules

.env

---------------

git branch

git status

git add .gitignore

git commit -m "arvind"

git branch

git remote add origin https://github.com/arvindsgsj95-cyber/practise-repositories.git

git remote -v

git config --global pull.rebase false

git pull origin main --allow-unrelated-histories

git push -u origin main

 
