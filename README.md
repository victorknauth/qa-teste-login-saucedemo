# Projeto 1 – Teste de Login - SauceDemo 🧪🔐

## 📌 Descrição do Projeto

Este projeto foi criado com o objetivo de realizar testes manuais na funcionalidade de login da plataforma [SauceDemo](https://www.saucedemo.com/). Durante o processo, foram verificados cenários de login bem-sucedido,
falhas com dados inválidos e identificado um bug real na plataforma.

---

## 🛠️ Ferramentas Utilizadas

- ✅ Navegador Opera
- ✅ VS Code (organização e versionamento)
- ✅ Git e GitHub (controle de versão)
- ✅ Print com ferramenta de captura
- ✅ Plataforma [SauceDemo](https://www.saucedemo.com/)

---

## 🧪 Cenários de Teste

### ✔️ Cenário 1 – Login com dados válidos

- **Usuário:** standard_user  
- **Senha:** secret_sauce  
- **Resultado esperado:** redirecionamento para a tela de produtos  
- **Resultado obtido:** conforme esperado ✅

---

### ❌ Cenário 2 – Login com dados inválidos

- **Usuário:** usuário_incorreto  
- **Senha:** senha_incorreta  
- **Resultado esperado:** exibir mensagem de erro  
- **Resultado obtido:** conforme esperado ✅

---

### ⚠️ Cenário 3 – Login com usuário válido e senha errada

- **Usuário:** standard_user  
- **Senha:** senha_incorreta  
- **Resultado esperado:** exibir mensagem de erro  
- **Resultado obtido:** ⚠️ **BUG encontrado:** tela recarrega uma mensagem com a box dela cortando as palavras da mensagem (print na pasta `evidencias/`)

---

### Foi criado uma branch beta de testes, para não modificar a branch principal (main), para fim de fazer testes sem comprometer o resultado final.

## 🐞 Bug Encontrado

Durante os testes, foi identificado um comportamento inesperado ao tentar realizar login com uma senha incorreta usando um usuário válido.

📸 Evidência: veja o print na pasta `evidencias/teste login erro.png`

---

## 🌐 Repositório no GitHub

🔗 Acesse o projeto aqui: https://github.com/victorknauth/qa-teste-login-saucedemo

---

## ✍️ Autor

**Victor Camargo Knauth**  
Estudante de QA | Em transição para área de tecnologia  
📧 Email: vcknauth1993@yahoo.com.br 
🔗 [LinkedIn] https://www.linkedin.com/in/victor-camargo-knauth-8355122bb

