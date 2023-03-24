# wordpress_docker
Projeto de configuração básica do Wordpress com PHPMyAdmin e MYSQL 5.7

## Como instalar:

1. Certifique-se de que o Docker esteja instalado no seu Ubuntu. Se não estiver instalado, você pode instalar usando o seguinte comando:
```
sudo apt install docker.io
```

2. Crie um diretório para o seu projeto do WordPress:

```
mkdir wordpress-docker
cd wordpress-docker
```

3. Dentro da pasta wordpress-docker, rode o seguinte comando:
```
git clone https://github.com/diassisjose/wordpress_docker/blob/main/docker-compose.yml
```
PS: caso queira alterar quais portas deseja utilizar no projeto, edite o docker-compose.yml antes de iniciar o contêiner para facilitar sua vida. No entanto, isso pode ser feito posteriormente!

4. Agora inicie o contêiner:
```
docker-compose up -d
```

Pronto! Agora acesse o <a href="http://localhost:8000" target="_blank">localhost:8000</a>
