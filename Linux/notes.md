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

## List Ports

```bash
$ sudo lsof -i -P -n | grep LISTEN
```

## Kill Process

```bash
$ sudo kill <process id>
```

[davidokwii.com/kill-process-running-under-certain-port/](davidokwii.com/kill-process-running-under-certain-port/)


## Prevent Chrome from Autoupdating

```bash
$ sudo chmod -R 000 ~/Library/Google
```

## Allow Chrome to Autoupdate

```bash
$ sudo chmod -R 755 ~/Library/Google
```

