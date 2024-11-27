# 📚 Projeto BackEnd - Geração Tech

Este projeto constitui o backend de uma aplicação desenvolvida durante a **_Formação em Desenvolvimento Web_** no programa **_Geração Tech_**. A aplicação foi construída utilizando **_Node.js_**, **_Express.js_** e **_Sequelize_**, oferecendo uma API RESTful com suporte à autenticação por meio de **_JWT (JSON Web Token)_**. Além disso, o projeto assegura o gerenciamento seguro de variáveis de ambiente com o auxílio do pacote **_Dotenv_**.

---

## 🚀 Tecnologias Utilizadas

- **Node.js**: Plataforma que permite executar JavaScript no lado do servidor para construir aplicações robustas.  
- **Express.js**: Framework que facilita a criação de rotas e o uso de middleware em aplicações web.  
- **Sequelize**: ORM (Mapeamento Objeto-Relacional) usado para gerenciar e interagir com bancos de dados, como o MySQL.  
- **JWT (JSON Web Token)**: Método de autenticação seguro baseado no uso de tokens.  
- **Dotenv**: Biblioteca que permite carregar variáveis de ambiente de um arquivo `.env` com segurança.  

---

## ⚙️ Funcionalidades

- **API RESTful**: Facilita a implementação das operações de criação, leitura, atualização e exclusão (CRUD) de recursos.  
- **Autenticação com JWT**: Proporciona segurança para rotas protegidas através de tokens.  
- **Gerenciamento Seguro de Ambiente**: Utiliza variáveis de ambiente para resguardar informações sensíveis.  

---

## 📦 Instalação

Siga os passos abaixo para clonar e executar o projeto localmente:

1. Clone o repositório:
   
   ```bash
   git clone https://github.com/Douglasffjw/Projeto-BackEnd.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd projeto-backend
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

## 🔧 Configuração

Crie um arquivo .env na raiz do projeto com as seguintes variáveis de ambiente:

1. Copiar código

```bash
APP_KEY_TOKEN="sua_chave_secreta"
DB_HOST="localhost"
DB_USER="seu_usuario"
DB_PASS="sua_senha"
DB_NAME="nome_do_banco"
DB_DIALECT="mysql"
```

2. Configure seu banco de dados MySQL com as credenciais fornecidas no arquivo .env.

## 🏃‍♂️ Execução

1. Inicie o servidor:

```bash
npm start
```
2. A API estará disponível no endereço:

```arduino
http://localhost:3000
```

## 🗂️ Estrutura do Projeto

```plaintext
├── src
│   ├── controllers     # Lógica dos controladores da API
│   ├── models          # Definições dos modelos Sequelize
│   ├── routes          # Definição das rotas da API
│   └── middlewares     # Middlewares como autenticação JWT
├── .env                # Arquivo de variáveis de ambiente
├── package.json        # Dependências e scripts do projeto
└── server.js           # Ponto de entrada da aplicação
```

## 🔒 Segurança

Autenticação JWT: Implementação de autenticação e proteção de rotas sensíveis.
Dotenv: Variáveis de ambiente mantêm seguras informações confidenciais como tokens e credenciais do banco de dados.
