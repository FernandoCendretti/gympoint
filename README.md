# GymPoint

## API Rest da Ferramenta de cotrole para Academias

## Instalação

```
$ git clone https://github.com/FernandoCendretti/gympoint.git
$ cd gympoint
$ npm install || yarn
```

É necessário ter o postgres instalado, caso tenha o Docker, basta executar os comandos:

```
sudo docker run --name meetapp -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

Para executar o sistema basta executar o comando:

```
yarn dev
```
