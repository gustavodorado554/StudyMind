# StudyMind - Assistente Virtual de Estudos

## Arquivos
- index.html -> Front-end completo
- server.js -> Back-end Node.js + Express + OpenAI
- package.json -> Dependências
- .env -> Configuração da chave da API

## Instalação

1. Abra a pasta no VS Code.
2. Abra o terminal.
3. Execute:

npm install

4. Crie um arquivo chamado `.env`.
5. Copie o conteúdo de `.env.example` e configure sua chave.
6. Inicie o servidor:

npm start

7. Abra o arquivo `index.html` no navegador.

O backend roda em:
http://localhost:3000

## Endpoint

POST /chat

Entrada:
{
  "mensagem": "Explique porcentagem",
  "historico": []
}

Saída:
{
  "response": "..."
}
