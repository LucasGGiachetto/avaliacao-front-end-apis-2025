# 📚 Desafio Frontend - Gerenciamento de Posts

## 🎯 Objetivo
O objetivo deste desafio é avaliar habilidades em desenvolvimento de páginas web front-end. Deverá ser criado uma UI simples que consome uma API pública, exibe os dados em uma lista, permite a navegação para uma tela de detalhes e possui uma funcionalidade de busca.

Usuário: emilys
Senha: emilyspass

---

## 🛠 Stack Recomendada
| Área          | Tecnologias                          |
|---------------|--------------------------------------|
| **Core**      | HTML5, CSS3, JavaScript ES6+        |
| **Framework** | Vanilla JS (React/Vue opcional)     |
| **Estilo**    | CSS Modules ou SASS                  |
| **Build**     | Vite (opcional)                     |

---

## 📋 Funcionalidades Principais

### 🔐 Módulo de Autenticação
- **Login seguro** via API DummyJSON
- **Armazenamento** JWT no LocalStorage
- **Refresh token** automático
- Validação de formulário em tempo real

### 📝 Gestão de Posts
- Listagem paginada em grid/cards
- Modal de detalhes com efeitos de transição
- Busca instantânea (debounce 300ms)
- Filtros por conteúdo/título
- Estados de loading/error/vazio

  ## Estrutura do Projeto
```
/index.html
/pages/
  /login.html
  /posts.html
/styles
  /main.css
/scripts
  /login.js
  /posts.js
```
