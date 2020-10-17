# Working directory
cd app

# Update bashrc to simplify commands
alias dc='docker-compose -f ../docker/docker-compose.yml --env-file ../docker/.env'
alias d='docker'
alias comp='docker-compose -f ../docker/docker-compose.yml --env-file ../docker/.env exec php-fpm composer $*'
alias c='docker-compose -f ../docker/docker-compose.yml --env-file docker/.env exec php-fpm php bin/console $*'