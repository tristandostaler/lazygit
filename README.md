# lazygit
http://stackoverflow.com/questions/19595067/git-add-commit-and-push-commands-in-one

function lazygit() {
    git add .
    git commit -a -m "$1"
    git push
}

lazygit "My commit msg"
