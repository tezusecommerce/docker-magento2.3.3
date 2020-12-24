# Magenteiro Magento 2

Para começar, clone o projeto com seus submódulos.
`git clone https://github.com/tezusecommerce/docker-magento2.3.3.git`

## Instruções de instalação Docker
1. Execute `echo "127.0.0.1 ::1 docker.tezus" | sudo tee -a /etc/hosts`
2. Após execute `bin/setup docker.tezus` e aguarde até finalizar, após abra `https://docker.tezus`.
3. Caso necessário execute na raiz do projeto `bin/composer install` e em seguida `bin/setup docker.tezus` novamente.

## Ferramentas Utilizadas
    - PHP 7.3
    - Elasticsearch 6.8
    - Percona 5.7
    - Nginx 1.18-3
    - Redis 5.0
    - RabbitMQ 3.7
