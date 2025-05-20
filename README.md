# 💻 Tech Challenge - Fase 4

Bem-vindo ao repositório do **Tech Challenge - Fase 4**!  
Siga os passos abaixo para configurar e rodar o projeto corretamente no seu ambiente.

---

## ✅ Pré-requisitos

Antes de começar, verifique se você possui as seguintes ferramentas instaladas:

- [Node.js](https://nodejs.org/) versão **20.18.1 ou superior**
- [Docker](https://www.docker.com/)

---

## 🚀 Como executar o projeto

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/rickcarloz/tech_challenge_app
cd tech_challenge_app
```

---

### 2️⃣ Configure as variáveis de ambiente

1. Localize o arquivo `.env.example` na raiz do projeto.  
2. Faça uma cópia dele e renomeie para `.env`.

#### ⚠️ Atenção:
A variável `EXPO_PUBLIC_CORS_ORIGIN` **deve ser configurada com o IP local da sua máquina**, por exemplo:

```env
EXPO_PUBLIC_CORS_ORIGIN=http://192.168.0.6:3000
```

As demais variáveis podem ser mantidas com os valores do arquivo `.env.example`.

---

### 3️⃣ Instale as dependências

No diretório do projeto, execute:

```bash
npm install
```

---

### 4️⃣ Inicie o backend e o banco de dados com Docker

Execute o comando abaixo para subir os containers:

```bash
docker compose up -d
```

---

### 5️⃣ Rode o aplicativo

Para iniciar a aplicação:

```bash
npm run start
```

---

### 6️⃣ Acesse com o usuário padrão

Utilize as credenciais abaixo para realizar login:

- **E-mail:** `admin@admin.com`  
- **Senha:** `123456`

---
