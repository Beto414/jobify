# Projeto Jobify

Este repositório documenta minha jornada de aprendizado e aprofundamento em tecnologias **Full Stack**, com foco em **Node.js** (backend) e **React.js** (frontend). O projeto Jobify visa a construção de uma aplicação completa para gerenciamento de vagas de emprego, demonstrando a integração eficiente entre diferentes camadas tecnológicas.

---

## Tecnologias Utilizadas

Este projeto utiliza as seguintes tecnologias em seu desenvolvimento:

- **Frontend**: React.js
- **Backend**: Node.js
- **Linguagem de Programação**: JavaScript
- **Banco de Dados**: MongoDB

---

## Objetivos do Projeto

Os principais objetivos deste projeto incluem:

- Consolidar conhecimentos e práticas avançadas em React.js (desenvolvimento frontend).
- Aprender e aplicar conceitos fundamentais e avançados de Node.js (desenvolvimento backend).
- Criar aplicações completas (Full Stack), estabelecendo a conexão e comunicação entre frontend e backend.
- Aperfeiçoar as boas práticas de desenvolvimento de software, incluindo organização de código, design patterns e performance.

---

## Funcionalidades (em progresso)

As funcionalidades implementadas e em desenvolvimento são listadas abaixo:

- [x] Estrutura inicial e organização do frontend utilizando React.
- [x] Componentização modular e gerenciamento de estado da aplicação frontend.
- [ ] Configuração e desenvolvimento do backend em Node.js, expondo uma API RESTful.
- [ ] Implementação da integração e comunicação entre o frontend e o backend.
- [ ] Desenvolvimento de módulos de autenticação de usuários (ex: JWT) e integração com o banco de dados MongoDB.
- [ ] Implementação das operações CRUD (Criar, Ler, Atualizar, Deletar) para gerenciamento de vagas de emprego.

---

## Como Executar o Projeto

Para configurar e executar o projeto Jobify em sua máquina local, siga os passos abaixo:

1.  **Clonar o Repositório:**
    Abra seu terminal e execute o comando:

    ```bash
    git clone https://github.com/Beto414/jobify
    cd jobify
    ```

2.  **Configuração do Frontend:**
    Navegue até o diretório `frontend` e instale as dependências:

    ```bash
    cd frontend
    npm install
    npm start
    ```

    O frontend será iniciado e acessível em `http://localhost:3000`.

3.  **Configuração do Backend (em construção):**

    - Navegue até o diretório `backend`:
      ```bash
      cd ../backend
      ```
    - Crie um arquivo `.env` na raiz do diretório `backend`. Este arquivo conterá as variáveis de ambiente necessárias para a aplicação, como `MONGO_URI` (URI de conexão do MongoDB) e `JWT_SECRET` (chave secreta para tokens de autenticação).
    - Instale as dependências:
      ```bash
      npm install
      ```
    - Inicie o servidor backend:
      `bash
    npm run dev
    `
      O backend será iniciado e estará disponível em `http://localhost:5000` (ou na porta configurada nas variáveis de ambiente).

    **Importante:** O frontend e o backend devem ser executados em terminais separados e simultaneamente para que a aplicação funcione corretamente.

---

## Autor

**Antonio Roberto Garcia (Beto)**
Desenvolvedor em formação, com especial interesse e foco em JavaScript, React.js e Node.js. Este projeto é parte fundamental da minha evolução prática no desenvolvimento full stack e na criação de soluções de software robustas.

- **LinkedIn**: [antoniorobertogarcia](https://www.linkedin.com/in/antoniorobertogarcia)
- **E-mail**: antoniorgms@gmail.com
- **GitHub**: [Beto414](https://github.com/Beto414)

---

## Licença

Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo `LICENSE` na raiz deste repositório.
