# 🎓 Guia SISU Aluno — Visualização de Classificação

Este projeto é um **guia interativo** que ensina como visualizar a **classificação no SISU** utilizando o **console do navegador**.  
Ele injeta uma interface visual diretamente no site oficial do **SISU Aluno**, exibindo a posição do candidato em cada curso e modalidade.

> ⚠️ Projeto com fins **educacionais**.  
> Não modifica dados, não burla sistemas e apenas exibe informações já disponíveis ao próprio usuário.

---

## 🚀 Funcionalidades

- 📊 Exibe a **classificação do aluno no SISU**
- 🧾 Mostra:
  - Curso
  - Instituição (IES)
  - Campus
  - Modalidade de concorrência
  - Posição e número de vagas
- 🪟 Interface visual moderna (popup + botão flutuante)
- 🖥️ Execução direta pelo **Console do navegador**
- 🌐 Compatível com navegadores modernos (Chrome, Edge, Firefox)

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Fetch API**
- **Manipulação do DOM**
- **SessionStorage**
- **API oficial do SISU Aluno**

---

## 📌 Como funciona

O script:
1. Obtém o **token de autenticação** armazenado no `sessionStorage` após o login no SISU.
2. Consome a API oficial de ranking do SISU.
3. Processa os dados retornados.
4. Cria uma **interface gráfica** sobre a página para exibir as classificações.

---

## ▶️ Como usar

### 1️⃣ Acesse o SISU Aluno
- Entre em: https://sisualuno.mec.gov.br
- Faça login com sua conta **Gov.br**

### 2️⃣ Abra o Console do navegador
Use um dos atalhos:
- **Windows / Linux:** `F12` ou `Ctrl + Shift + I`
- **Mac:** `Cmd + Option + I`

Clique na aba **Console**.

### 3️⃣ Execute o código
- Copie o código JavaScript do projeto
- Cole no Console
- Pressione **Enter**

### 4️⃣ Visualize sua classificação
- Um botão flutuante **“Classificação”** aparecerá no canto inferior direito
- Clique nele para abrir o painel com seus dados

---

## ⚠️ Observações Importantes

- O código **só funciona enquanto você estiver logado** no SISU Aluno
- Ao atualizar a página, é necessário executar o script novamente
- Se a classificação ainda não estiver disponível no sistema, nenhum dado será exibido

---

## 🧩 Possíveis Erros e Soluções

**❌ Token não encontrado**
- Certifique-se de estar logado e na página principal do SISU

**❌ Nenhum dado aparece**
- O SISU pode ainda não ter liberado a classificação

**❌ Código não executa**
- Verifique se está realmente na aba **Console**

---

## 📚 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:
- Estudo de **APIs públicas**
- Manipulação avançada do **DOM**
- Criação de **interfaces dinâmicas**
- Aprendizado prático de JavaScript no navegador

---

## ⚖️ Aviso Legal

Este projeto **não possui vínculo** com o MEC ou o Governo Federal.  
Utiliza apenas recursos disponíveis ao próprio usuário autenticado.

---

## 👨‍💻 Autor

Desenvolvido por **Erick**  
Projeto educacional e demonstrativo para estudos em desenvolvimento web e APIs.

