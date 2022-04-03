### docker_containers

#### Requisitos:

docker

git

#### Esse projeto consiste em criar imagem de container e buildar e em seguidar subir o mesmo, para iniciar baixe este repositório com o comando abaixo:
git clone https://github.com/deividduarte20/docker_containers.git

#### Entre no diretório baixado:
cd docker_containers/

#### Para fazer o build (construção) da imagem:
docker image build -t digite_seu_nome/conversao-temperatura:v1 .

#### Subir o container:
docker container run -d -p 8080:8080 digite_seu_nome/conversao-temperatura:v1

#### Verificar se o container está rodando:
docker ps

#### Para testar se a aplicação subiu acesse o navegador e digite:
localhost:8080




