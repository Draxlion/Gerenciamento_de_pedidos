# 🧾 Sistema de Cadastro de Itens com Node.js + Front-End

Este projeto é um sistema básico de gerenciamento de itens, com **front-end simples em HTML/CSS/JS** e um **servidor em Node.js**.  
Ele permite:

- ✅ Cadastrar novos itens  
- 📋 Listar todos os itens  
- ❌ Excluir itens por índice

---

## 🚀 Tecnologias utilizadas

### Backend:
- Node.js
- Express (roteamento)
- Body-parser (ou middleware nativo do Express)
- Armazenamento em memória (array simples)

### Frontend:
- HTML5
- CSS3 (puro)
- JavaScript Vanilla (fetch API)

---

## 📁 Estrutura do projeto

📦 node
┣ 📂 site7
┃ ┣ 📜 cliente.html
┃ ┣ 📜 style.css
┃ ┣ 📜 bancoDeDados.sql
┃ ┗ 📜 index.js
┣ 📂 node.modules
┗ 📜 README.md

yaml
Copiar código

---

## 🔧 Como executar localmente

### 1. Clone o repositório

```bash
git clone https://github.com/Draxlion/Gerenciamento_de_pedidos.git
cd sistema-itens
2. Instale as dependências
bash
Copiar código
npm install
3. Inicie o servidor
bash
Copiar código
node server.js
O servidor será iniciado em: http://localhost:3000

4. Acesse o front-end
Abra seu navegador em:
http://localhost:3000

📌 Funcionalidades
➕ Cadastro de itens
Preencha o formulário com nome, quantidade e preço, e envie via botão "Adicionar".

📋 Listagem
Clica-se em "Listar Pedido" para carregar os itens salvos no servidor.

❌ Exclusão
Informe o índice do item a ser excluído e envie para removê-lo do sistema.

⚠️ Observações
Este projeto usa armazenamento em memória. Ao reiniciar o servidor, os dados são perdidos.

Ideal para fins educacionais e para entender a comunicação entre client e server com fetch + Node.js.

🤝 Contribuições
Contribuições são bem-vindas!
Sinta-se livre para abrir issues ou pull requests com melhorias, validações, ou adaptações com banco de dados.

Feito com ☕ e código por Bruna.
