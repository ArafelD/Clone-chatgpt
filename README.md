# Clone do ChatGPT

Um clone completo do ChatGPT desenvolvido com Node.js/Express no backend e React no frontend, utilizando a API oficial da OpenAI.

## 📋 Índice

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Pré-requisitos](#pré-requisitos)
- [Instalação e Configuração](#instalação-e-configuração)
- [Como Usar](#como-usar)
- [API Endpoints](#api-endpoints)
- [Contribuição](#contribuição)
- [Licença](#licença)

## 🔍 Visão Geral

Este projeto é um clone funcional do ChatGPT, recriando a experiência de conversa com uma IA usando a API oficial da OpenAI. A aplicação possui uma interface de usuário semelhante ao ChatGPT original, permitindo aos usuários enviar mensagens e receber respostas da IA em tempo real.

## ✨ Funcionalidades

- Interface de usuário semelhante ao ChatGPT original
- Comunicação em tempo real com a API da OpenAI
- Histórico de mensagens na sessão atual
- Suporte a markdown nas respostas
- Design responsivo para desktop e dispositivos móveis
- Tratamento de erros e feedback visual

## 🛠️ Tecnologias Utilizadas

### Backend
- Node.js
- Express
- JavaScript
- Cors
- Dotenv
- OpenAI API

### Frontend
- React
- TypeScript
- Styled Components
- Axios
- React Icons

## 📁 Estrutura do Projeto

```
chatgpt-clone/
├── backend/             # Servidor Node.js/Express
│   ├── src/
│   │   └── server.js    # Configuração do servidor e rotas
│   ├── .env             # Variáveis de ambiente
│   └── package.json     # Dependências do backend
│
└── frontend/            # Aplicação React
    ├── public/          # Arquivos estáticos
    ├── src/
    │   ├── components/  # Componentes React
    │   ├── services/    # Serviços de API
    │   ├── App.tsx      # Componente principal
    │   └── index.tsx    # Ponto de entrada
    └── package.json     # Dependências do frontend
```

## 📋 Pré-requisitos

- Node.js (v14 ou superior)
- npm ou yarn
- Chave de API da OpenAI

## 🚀 Instalação e Configuração

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/chatgpt-clone.git
cd chatgpt-clone
```

### 2. Configure o Backend

```bash
# Navegue até o diretório do backend
cd backend

# Instale as dependências
npm install

# Crie um arquivo .env na raiz do diretório backend
# Adicione sua chave de API da OpenAI
echo "PORT=5000
OPENAI_API_KEY=sua-chave-api-aqui" > .env
```

### 3. Configure o Frontend

```bash
# Navegue até o diretório do frontend
cd ../frontend

# Instale as dependências
npm install
```

## 🎮 Como Usar

### 1. Inicie o Backend

```bash
# No diretório backend
npm start
```

O servidor será iniciado na porta 5000 (ou na porta definida no arquivo .env).

### 2. Inicie o Frontend

```bash
# No diretório frontend
npm start
```

A aplicação React será iniciada e estará disponível em [http://localhost:3000](http://localhost:3000).

### 3. Interagindo com o Clone do ChatGPT

- Digite sua mensagem na caixa de texto na parte inferior da tela
- Pressione Enter ou clique no botão de envio para enviar sua mensagem
- A resposta da IA será exibida na conversa

## 📡 API Endpoints

### POST /api/chat

Envia uma mensagem para a API da OpenAI e retorna a resposta.

**Corpo da Requisição:**

```json
{
  "messages": [
    {"role": "user", "content": "Olá, como você está?"},
    {"role": "assistant", "content": "Estou bem, obrigado por perguntar! Como posso ajudar você hoje?"},
    {"role": "user", "content": "Explique o que é inteligência artificial."}
  ]
}
```

**Resposta:**

```json
{
  "role": "assistant",
  "content": "Inteligência Artificial (IA) é um campo da ciência da computação..."
}
```

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar este projeto.
1. Faça um fork do projeto
2. Crie sua branch de feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Desenvolvido com ❤️ por [Rafael Dias]

1. Faça um fork do projeto
2. Crie sua branch de feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Desenvolvido com ❤️ por [Rafael Dias](https://github.com/seu-usuario)
