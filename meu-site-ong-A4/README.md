# 🌿 ONG Esperança — Site Acessível

> Projeto institucional acessível da **ONG Esperança**, com foco em **solidariedade, voluntariado e inclusão**.

---

## 🚀 Funcionalidades

- Navegação **SPA (Single Page Application)** com JavaScript puro  
- Suporte a **modo escuro** e **alto contraste**  
- Formulários acessíveis com feedback dinâmico via `aria-live`  
- **Galeria com modal acessível**  
- Conteúdo carregado dinamicamente (sem recarregar a página)  
- Layout **totalmente responsivo e otimizado**  
- **Persistência de preferências** (modo contraste) com `localStorage`  
- Uso de **eventos de teclado e foco visível** para acessibilidade  

---

## 🧠 Estrutura do Projeto

meu-site-ong-A4/
├── index.html
├── accessibility.js
├── accessibility.css
├── css/
│ └── accessible.min.css
├── js/
│ ├── bundle.min.js
│ └── accessibility.min.js
├── img/
│ └── favicon.ico
├── ACCESSIBILITY.md
├── CONTRIBUTING.md
├── CODEOWNERS
├── package.json
└── README.md


---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
|-------------|------------|
| **HTML5 / ARIA** | Estrutura semântica e navegação acessível |
| **CSS3** | Design responsivo e contrastes de cor otimizados |
| **JavaScript (ES6+)** | Manipulação dinâmica do DOM e controle de estado |
| **LocalStorage API** | Armazenamento de preferências do usuário |
| **Node.js + Serve** | Servidor local simples para desenvolvimento |
| **ARIA Roles & Live Regions** | Comunicação acessível com leitores de tela |

---

## 💡 Destaques Técnicos

- Implementação modular e otimizada para acessibilidade (`accessibility.js`)  
- Alterações dinâmicas de tema e contraste com persistência local  
- Anúncio automático de mudança de página com `aria-live="polite"`  
- Foco visível personalizado e compatível com `Tab` e `Shift + Tab`  
- Estrutura SPA baseada em hash routing (`#/sobre`, `#/doacoes`, etc.)  
- Feedback imediato em formulários com mensagens de status acessíveis  

---

## ⚙️ Como Executar o Projeto

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/PSeS2025/meu-site-ong-A4.git
cd meu-site-ong-A4




