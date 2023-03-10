<h1 align="center">Aprendendo Docker</h1>

<h4 align="center"> 
	📖  Estudos 🐳
</h4>

## O que são containers?
Os containers são tecnologias que permitem isolar aplicações com todo o ambiente de execução delas, ou seja, com todos os arquivos necessários para executá-las. Dessa forma, fica mais fácil migrá-las de um ambiente para outro.

## O que é docker?
O software de TI "Docker” é uma tecnologia de containerização para criação e uso de containers.

## Comandos Básicos - Docker
~~~Shel
docker version
~~~
Verifica a versão do docker

~~~Shel
docker container ls
~~~
Lista os containers em execução

~~~Shel
docker container ls -a
~~~
Lista todos os containers em execução ou parados

~~~Shel
docker images
~~~
Lista as imagens atuais do host

~~~Shel
docker container inspect <Id Container>
~~~
Mostra informações detalhadas sobre um determinado container

~~~Shel
docker image inspect <Id Container>
~~~
Mostra informações detalhadas sobre uma determinada imagem

~~~Shel
docker container stop <Id Container>
~~~
Para um container

~~~Shel
docker container start <Id Container>
~~~
Inicia um container parado

~~~Shel
docker container rm <Id Container>
~~~
Remove um container

~~~Shel
docker image rm <Id Container>
~~~
Remove uma imagem

> 💡 A imagem só será removida se o container ligado a ela já estiver removido, caso contrário, você receberá uma mensagem de erro informando o container que você deverá remover antes de remover a imagem.

## Referências de Estudos
* [Curso descomplicando o docker - LinuxTips](https://www.linuxtips.io/pages/trilha-de-treinamentos)
* [Livro Descomplicando o docker - LinuxTips](https://github.com/badtuxx/DescomplicandoDocker)
* [O que é Docker? - RedHat](https://www.redhat.com/pt-br/topics/containers/what-is-docker)
* [O que são containers Linux? - RedHat](https://www.redhat.com/pt-br/topics/containers)
