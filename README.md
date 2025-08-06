# 📊 Desafio Técnico Frontend — Dashboard de Métricas

## 🧠 Descrição

Este desafio tem como objetivo avaliar suas habilidades de desenvolvimento frontend implementando uma funcionalidade de visualização de métricas administrativas no dashboard principal da plataforma.

Você irá consumir um JSON de dados fornecido, seguir um layout no Figma e criar um painel com **cards informativos** e atualização **em tempo real**.

---

## 📌 Funcionalidade

### **História do usuário**

> Como administrador do sistema,  
> Eu quero visualizar métricas resumidas dos usuários,  
> Para que eu possa acompanhar o crescimento e status geral da plataforma.

---

## 🧪 Cenários esperados (BDD)

### ✅ Cenário 1: Exibir métricas resumidas em cards

- Dado que estou autenticado como administrador  
- Quando acesso o dashboard principal  
- Então devo visualizar:
  - Um card com o **total de usuários**
  - Um card com a **quantidade de usuários ativos**
  - Um card com a **quantidade de usuários inativos**
  - Um card com a **quantidade de administradores**

### 🔄 Cenário 2: Atualização em tempo real

- Dado que estou no dashboard  
- Quando há mudanças na base de usuários (criação, atualização de status, etc.)  
- Então os valores exibidos nos cards devem ser **atualizados automaticamente**, sem recarregar a página

---

## 🎨 Recursos fornecidos

| Recurso | Link |
|--------|------|
| 🔗 Figma com layout | [link-aqui](#) *(substituir)* |
| 📂 JSON com dados mockados | [link-aqui](#) *(substituir)* |

---

## ⚙️ Instruções técnicas

- Você pode usar o framework de sua preferência (React, Vue, etc.) — sugerimos React + Vite.
- O layout deve respeitar o Figma (responsividade e estilos).
- A atualização em tempo real pode ser feita com **polling**, **websocket simulado** ou **eventos artificiais** (ex: `setInterval` alterando o mock).
- Use boas práticas de componentização, organização e escrita de código.
- É **opcional**, mas bem-vindo:
  - Testes unitários (Jest, Testing Library, etc.)
  - Animações ou microinterações
  - Acessibilidade básica (alt, aria, contraste)

---

## 📦 Entrega

- Crie um repositório público com o nome `desafio-dashboard-metricas`.
- Inclua um `README.md` com:
  - Instruções de instalação e execução do projeto
  - Suas decisões técnicas e arquitetura
  - O que você faria diferente com mais tempo
- Compartilhe o link do repositório com o time avaliador.

---

## 🔍 O que será avaliado

| Critério | Peso |
|----------|------|
| Fidelidade ao layout (Figma) | ⭐⭐⭐⭐ |
| Lógica e organização do código | ⭐⭐⭐⭐ |
| Clareza da apresentação e decisões | ⭐⭐⭐ |
| Atualização dos dados em tempo real | ⭐⭐⭐⭐ |
| Boas práticas (componentes, estado, etc.) | ⭐⭐⭐⭐ |
| Testabilidade (se houver) | ⭐⭐ |
| Responsividade e UX | ⭐⭐⭐ |

---

## 💬 Dúvidas?

Em caso de dúvidas, entre em contato com o responsável pela vaga ou envie uma issue neste repositório (se aplicável).

Boa sorte e bom código! 🚀
