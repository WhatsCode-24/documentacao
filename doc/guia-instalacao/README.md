# Guia de Instalação e Execução do Projeto

Este guia contém as instruções para instalação e execução do **backend** (TypeScript) e do **front-end** (JavaScript) do projeto. Siga os passos abaixo para configurar o ambiente corretamente.

## Backend (TypeScript)

### Passo 1: Instalar Serverless

Para usar o Serverless, você precisa instalá-lo globalmente em sua máquina na versão 3.38.0. Execute o comando abaixo:

```bash
yarn global add serverless@3.38.0
```

### Passo 2: Clonar o Repositório

Clone o repositório e navegue até o diretório do backend:

```bash
git clone https://github.com/WhatsCode-24/backend.git
cd backend
```

### Passo 3: Instalar Dependências

Instale as dependências necessárias para o backend com o comando:

```bash
yarn
```

### Passo 4: Configurar Variáveis de Ambiente

Preencha o arquivo .env com as informações do banco de dados e JWT.

### Passo 5: Executar o Backend

Para rodar o servidor em ambiente de desenvolvimento, utilize o seguinte comando:

```bash
yarn dev
```

### Passo 6: Testar a API

Você pode testar a API utilizando a collection Postman disponível no link abaixo:

[API - 6 SEM.postman_collection.json](https://github.com/user-attachments/files/16972617/API.-.6.SEM.postman_collection.json)

---

## Front-end (JavaScript)

### Passo 1: Clonar o Repositório

Clone o repositório e navegue até o diretório do front-end:

```bash
git clone https://github.com/WhatsCode-24/frontend.git
cd frontend
```

### Passo 2: Instalar Dependências

Instale as dependências necessárias para o front-end com o comando:

```bash
yarn
```

### Passo 3: Executar o Front-end

Para iniciar o servidor de desenvolvimento do front-end, utilize o comando:

```bash
yarn start
```

## Agora o seu ambiente está configurado e o projeto está pronto para uso.
