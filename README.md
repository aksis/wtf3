# wtf3
wtf3@DockerHub

## Usage

### Unix shell alias

```
alias vshell='docker run --rm -i -t wtf3/core'
alias node='docker run --rm -i -t -v "$(pwd)":/app -w /app wtf3/node'
alias php='docker run --rm -i -t -v "$(pwd)":/app -w /app wtf3/php'
alias composer='docker run --rm -i -t -v "$(pwd)":/app -w /app wtf3/composer'
```

#### Test

```
vshell
node -v
php -v
composer -V
```
