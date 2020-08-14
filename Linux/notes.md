# Notes

## Bash Profile

```bash
$ vi ~/.bash_profile
```

./bash_profile:
```bash
export GOPATH=~/go
export PATH=$PATH:/bin
export CLICOLOR=1

alias dcb='docker-compose build'
alias dcd='docker-compose down'
alias dch='docker-compose help'
alias dcps='docker-compose ps'
alias dcu='docker-compose up'
alias gitfetch='git fetch --all'
alias gitfetchpull='git fetch --all; git pull origin master'
alias ll='ls -l'
```
