# Instruções para rodar o projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Instale as dependências:**

   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento:**

   ```bash
   npm run dev
   ```

4. **Acesse o projeto:**
   Abra o navegador e acesse `http://localhost:5173` (ou a porta indicada no terminal).

---

**Pré-requisitos:**

- Node.js e npm instalados na máquina.
- Git para clonar o repositório.
- (Opcional) Editor de código, como VS Code.# layout-adm-tailwind

## Comandos úteis do GitHub

- **Criar um novo repositório no GitHub:**  
   Acesse [github.com](https://github.com/) e clique em "New repository".

- **Adicionar repositório remoto:**  
   `bash
  git remote add origin https://github.com/seu-usuario/seu-repositorio.git
  `

- **Enviar alterações para o GitHub:**  
   `bash
  git add .
  git commit -m "Mensagem do commit"
  git push origin main
  `

- **Baixar alterações do repositório remoto:**  
   `bash
  git pull origin main
  `

  - **Criar uma nova branch:**

    ```bash
    git checkout -b nome-da-branch
    ```

  - **Trocar de branch:**

    ```bash
    git checkout nome-da-branch
    ```

  - **Listar todas as branches:**

    ```bash
    git branch
    ```

  - **Deletar uma branch local:**

    ```bash
    git branch -d nome-da-branch
    ```

  - **Enviar uma branch para o repositório remoto:**

    ```bash
    git push origin nome-da-branch
    ```

  - **Trocar de branch e atualizar com as últimas alterações do remoto:**
    ```bash
    git checkout nome-da-branch
    git pull origin nome-da-branch
    ```
