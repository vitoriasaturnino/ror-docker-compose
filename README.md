# Primeiro projeto Ruby on Rails dockerizado

Aplicação criada no intuíto de estudar as tecnologias Docker e Docker Compose.

## Para levantar a aplicação:

- Como pré requisitos é preciso ter o **Docker** e o **Docker Compose** instalados em sua máquina. Caso ainda não temha instalado siga este [tutorial](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-install-Docker-and-docker-compose-on-Ubuntu);

- Após concluir a instalação rode o comando `$ sudo docker build -t myapp . && docker run -it myapp` para buildar a imagem e levantar o container;

- No seu navegador acesse [localhost:3000](localhost:3000) e veja a plicação rodando.

<!--
add command rake db:create in entrypoint.sh

Docker build and run inone command -->
