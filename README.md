# README

## Explicação geral
O repositório apresentado consiste em uma aplicação web simples construída usando o framework Flask, uma ferramenta popular em Python para desenvolvimento web. O principal arquivo, app.py, define rotas que servem uma página principal (index.html) e conteúdo estático, como imagens e estilos, a partir de um diretório public.

O arquivo index.html é um currículo web, detalhando minhas habilidades, histórico educacional e histórico de emprego.

Para facilitar o deployment, o projeto é acompanhado de um Dockerfile que encapsula a aplicação em um contêiner Docker. Este Dockerfile usa uma imagem base Python 3.9, instala as dependências necessárias listadas em requirements.txt e expõe a porta 80. O contêiner é configurado para executar a aplicação Flask em modo de produção.

## Link da imagem
<a href="https://hub.docker.com/r/lyorrei/curriculo">Meu currículo (clique aqui)</a>


Link completo: https://hub.docker.com/r/lyorrei/curriculo"

## Como rodar a aplicação

### Pré-requisitos:

- Docker instalado em seu sistema.

### Instruções:

1. **Clonar o repositório**: 
   Clone o repositório para sua máquina local usando `git clone https://github.com/lyorrei-inteli/curriculo.git`.

2. **Navegar até a pasta do projeto**: 
   Mude para o diretório do projeto clonado com `cd curriculo`.

3. **Construir a imagem Docker**: 
   Construa a imagem Docker usando o comando `docker build -t curriculo .`

4. **Rodar o contêiner**:
   Inicie um contêiner usando a imagem construída com `docker run -p 80:80 curriculo`.

5. **Acessar a aplicação**:
   Abra seu navegador e navegue para `http://localhost:80` para visualizar a aplicação.
