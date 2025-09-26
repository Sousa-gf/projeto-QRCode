# 🚀 Gerador de QR Code & Senhas

Um projeto em **Node.js** que combina duas ferramentas em uma só aplicação:

- 🔹 **QR Code:** Gera QR Codes direto no terminal ou em formato visual.
- 🔹 **Senhas Seguras:** Cria senhas personalizadas a partir de configurações no `.env`.

---

## 📂 Estrutura

```
src
├── prompts          # Prompts interativos (menus e inputs)
├── services
│   ├── password     # Lógica para gerar senhas
│   └── qr-code      # Lógica para gerar QR Codes
├── index.js         # Ponto de entrada
└── .env             # Configurações de ambiente
```

---

## ⚙️ Configuração

Crie um arquivo `.env` na raiz do projeto:

```env
PASSWORD_LENGTH=12
UPPERCASE_LETTERS=true
LOWERCASE_LETTERS=true
NUMBERS=true
SPECIAL_CHARACTERS=true
```

---

## 🛠 Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/nome-do-repositorio.git

# Acesse a pasta do projeto
cd nome-do-repositorio

# Instale as dependências
npm install
```

---

## ▶️ Uso

Execute o projeto:

```bash
node src/index.js
```

Escolha no menu inicial:

1️⃣ **QR Code** – Digite um link e gere o QR Code.  
2️⃣ **Password** – Crie uma senha segura com base no `.env`.

---

## 📦 Dependências

- [chalk](https://www.npmjs.com/package/chalk) → Estiliza mensagens no terminal
- [prompt](https://www.npmjs.com/package/prompt) → Inputs interativos
- [qrcode-terminal](https://www.npmjs.com/package/qrcode-terminal) → Geração de QR Codes no terminal
- [dotenv](https://www.npmjs.com/package/dotenv) → Gerencia variáveis de ambiente

---

## 📝 Licença

Este projeto está sob a licença MIT.  
Sinta-se livre para usar e modificar! 😎
