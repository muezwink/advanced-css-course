git config --global user.name "muezwink"
git config --global user.email "muezwink@gmail.com"

git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status 
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"

git clone https://github.com/jonasschmedtmann/advanced-css-course.git advanced-css-course

echo "# advanced-css-course" >> README.md
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/muezwink/advanced-css-course.git
git push -u origin master