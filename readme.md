# Projeto gRPC - Curso FullCycle

<p align="center">
  <a href="https://www.linkedin.com/in/claudio-santos-3b071140/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://www.instagram.com/claudiosantos.al/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</p>

## Descrição do Projeto

<p align="justify">Este projeto tem a finalidade de demonstrar a comunicação utilizando o framework gRPC através de um Client e seu Server, utilizando as seguintes formas de comunicação: <b>Unary</b>, <b>Server Streaming</b>, <b>Client Streaming</b>.</p>

### Tecnologias

- [gRPC](https://grpc.io/)
- [Protocol Buffers](https://developers.google.com/protocol-buffers)
- [GoLang](https://go.dev/)

> Status do Projeto: Em desenvolvimento :warning:

### Instalação

**Ubuntu / WSL**: 

```
sudo apt install protobuf-compiler
```

Para finalizar, temos que adicionar a pasta "<i>/go/bin</i>" no PATH do Linux para que tudo que seja instalado nesta pasta esteja disponível como comandos no terminal. Adicione no final do seu <i>~/.bash</i>.

```
export PATH="$PATH:$(go env GOPATH)/bin"
```

Execute o comando abaixo para atualizar seu terminal:

```
source ~/.bashrc
```

**Mac**:

```
brew install protobuf
brew install protoc-gen-go
brew install protoc-gen-go-grpc
```

### Execução do Projeto

```
go run cmd/server/server.go
go run cmd/client/client.go
```
