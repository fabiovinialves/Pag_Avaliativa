# 🧾 React Multi-Step Form

Formulário **multi-etapas** (multi-step) desenvolvido em **React + Vite**, com navegação entre etapas, controle de estado centralizado e componentes reutilizáveis.

O projeto simula um fluxo de preenchimento em etapas (ex.: dados do usuário → avaliação → confirmação).

---

<img width="500" height="500" alt="Tela" src="https://github.com/user-attachments/assets/3813e952-dc2e-4a9e-8895-37a14bfbc587" />

## ✅ Funcionalidades

- Formulário em **múltiplas etapas**
- **Navegação** entre etapas (voltar/avançar)
- Estado centralizado com `useState`
- Hook customizado `useForm` para controlar:
  - etapa atual
  - componente atual
  - validação de limites (primeira/última etapa)
- Ícones com `react-icons`
- Estilização por componente (CSS separado)

---

## 🧩 Estrutura das Etapas (Components)

- `UserForm` → dados do usuário (nome, e-mail)
- `ReviewForm` → avaliação/feedback (opções + comentário)
- `Thanks` → tela final/agradecimento
- `Steps` → indicador visual das etapas

---

## 🛠️ Tecnologias

- React
- Vite
- JavaScript
- CSS
- React Icons

---

## ⚠️ Atenção: pasta correta para rodar

O projeto está dentro de uma pasta **aninhada**.  
Você deve executar os comandos na pasta que contém o `package.json` com o script `dev`:

✅ **Caminho correto:**
react_multistep_form/react_multistep_form

Se você rodar no diretório pai, vai aparecer:
`npm error Missing script: "dev"`.

---

## ▶️ Como executar
```
1) Entre na pasta correta:
   
cd react_multistep_form/react_multistep_form

2) Instale as dependências:
   
 npm install

3) Rode o projeto:

npm run dev
  
```
-> Acesse no navegador o link que o terminal mostrar

![License](https://img.shields.io/badge/License-MIT-0a0a0a?style=for-the-badge&logo=opensourceinitiative&logoColor=white)

Projeto com finalidade educacional/portfólio.

