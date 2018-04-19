# Async socks proxy #

Fast and simple to setup socks proxy. By default only Telegram networks are permitted.

## Starting up ##
    
1. `git clone https://github.com/alexbers/tgsocksproxy.git; cd tgsocksproxy`
2. *(optional, recommended)* edit *config.py*, set **USER**, **PASSWORD** and **PORT**
3. `docker-compose up --build -d`
4. *(optional, shows telegram link to set the proxy)* `docker-compose logs`
