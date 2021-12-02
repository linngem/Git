# My favourite alias in Git
Some alias very useful for setting git

## Log
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"

## Status
git config --global alias.s status --short

## Alternative status
git config --global alias.s status -sb
