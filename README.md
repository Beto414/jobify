# Jobify - Aplicação Full-Stack de Rastreamento de Vagas

**Jobify** é uma aplicação Full-Stack completa construída com o MERN Stack (MongoDB, Express.js, React, Node.js). Este projeto representa um passo significativo na minha jornada de aprofundamento em tecnologias de desenvolvimento web, com o objetivo de criar uma solução robusta e eficiente para o gerenciamento de candidaturas de emprego.

A aplicação permite que os usuários monitorem todo o ciclo de vida de suas candidaturas, desde o envio inicial até as entrevistas e decisões finais, através de uma interface moderna e reativa.

---

## ✨ Funcionalidades Principais

- ✅ **Autenticação Segura**: Sistema completo de registro e login com senhas hasheadas (Bcrypt) e tokens JWT armazenados em cookies HTTP-only para máxima segurança.
- ✅ **Dashboard Interativo**: Visualize estatísticas de candidaturas (pendentes, entrevistas, recusadas) e um gráfico de atividades mensais.
- ✅ **Gerenciamento de Vagas (CRUD)**: Adicione, visualize, edite e exclua vagas de emprego de forma intuitiva e persistente.
- ✅ **Busca e Filtragem Avançada**: Pesquise vagas por cargo ou empresa, filtre por status e tipo, e ordene os resultados para encontrar o que precisa.
- ✅ **Perfil de Usuário Personalizável**: Atualize suas informações e faça upload de uma foto de perfil, com armazenamento de imagens na nuvem (Cloudinary).
- ✅ **Tema Escuro/Claro**: Alterne entre os temas para uma melhor experiência visual, com a preferência salva no `localStorage`.
- ✅ **Painel de Administrador**: Rota protegida para administradores visualizarem estatísticas gerais da aplicação (total de usuários e vagas).
- ✅ **Design Responsivo**: Interface totalmente funcional e agradável em dispositivos móveis e desktops.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando um ecossistema moderno de tecnologias JavaScript.

#### Backend

- **Node.js**: Ambiente de execução JavaScript.
- **Express.js**: Framework para a construção da API REST.
- **MongoDB**: Banco de dados NoSQL para armazenamento de dados.
- **Mongoose**: ODM para modelagem dos dados do MongoDB.
- **JSON Web Token (JWT)**: Para autenticação segura baseada em tokens.
- **Cloudinary**: Para armazenamento e gerenciamento de imagens na nuvem.
- **Segurança**: `helmet`, `express-mongo-sanitize`, `express-rate-limit`.

#### Frontend

- **React.js**: Biblioteca para construção da interface de usuário.
- **Vite**: Ferramenta de build para um desenvolvimento frontend ultrarrápido.
- **React Router**: Para roteamento com `loaders` e `actions`, permitindo uma UX moderna.
- **React Query (TanStack Query)**: Para gerenciamento de estado do servidor, cache e sincronização de dados.
- **Axios**: Cliente HTTP para realizar requisições à API.
- **Styled Components**: Para estilização CSS-in-JS.
- **Recharts**: Para a criação de gráficos interativos.

---

## 🚀 Como Rodar o Projeto Localmente

Siga os passos abaixo para configurar e executar o projeto em sua máquina.

### Pré-requisitos

- [Node.js](https://nodejs.org/en/) (versão 18 ou superior)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) (conta gratuita é suficiente)
- [Cloudinary](https://cloudinary.com/) (conta gratuita para upload de imagens)

### 1. Clonar o Repositório

```bash
git clone https://github.com/Beto414/jobify.git
cd jobify
```

### 2. Configurar Variáveis de Ambiente

Na **raiz do projeto**, crie um arquivo chamado `.env` e adicione as seguintes variáveis, substituindo os valores pelos seus.

```env
# Porta do Servidor
PORT=5100

# String de conexão com o MongoDB Atlas
MONGO_URL=mongodb+srv://<user>:<password>@cluster0.mongodb.net/jobify?retryWrites=true&w=majority

# Chaves secretas para o JWT (use uma string longa e aleatória)
JWT_SECRET=your_super_secret_jwt_key
JWT_EXPIRES_IN=1d

# Credenciais do Cloudinary para upload de imagens
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
```

### 3. Instalar as Dependências

Este projeto usa um script para instalar as dependências do servidor e do cliente de uma só vez.

````bash
npm run setup-project```

### 4. Executar a Aplicação

Use o script `dev` para iniciar o servidor backend e o servidor de desenvolvimento do frontend simultaneamente.

```bash
npm run dev
````

- O **Backend** estará rodando em `http://localhost:5100`
- O **Frontend** estará acessível em `http://localhost:5173`

Acesse `http://localhost:5173` no seu navegador para ver a aplicação em funcionamento.

### 5. (Opcional) Popular o Banco de Dados com Dados de Exemplo

Para testar a aplicação com um volume maior de dados (gráficos, paginação, etc.), você pode popular o banco de dados com vagas de exemplo.

> **Importante:** Primeiro, você deve registrar um novo usuário na aplicação com o email `alicia@gmail.com`. O script associará os dados a este usuário.

Após registrar o usuário de teste, execute o seguinte comando na raiz do projeto:

```bash
node populate.js
```

---

### ✨ Explore o App com o Usuário de Teste

Não quer se registrar? Sem problemas! Na página de login, clique no botão **"Explore the App"**.

Isso fará o login com um usuário de demonstração pré-configurado (`alicia@gmail.com`), permitindo que você navegue por todas as funcionalidades da aplicação imediatamente.

> **Atenção:** O usuário de demonstração possui permissões de **apenas leitura**. Você não poderá adicionar, editar ou excluir vagas com esta conta.

---

## 👤 Autor

**Antonio Roberto Garcia (Beto)**

Desenvolvedor em formação, com especial interesse e foco em JavaScript, React.js e Node.js. Este projeto é parte fundamental da minha evolução prática no desenvolvimento full stack e na criação de soluções de software robustas.

- **LinkedIn**: [antoniorobertogarcia](https://www.linkedin.com/in/antoniorobertogarcia)
- **GitHub**: [Beto414](https://github.com/Beto414)
- **E-mail**: antoniorgms@gmail.com

---

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo `LICENSE` na raiz deste repositório.
