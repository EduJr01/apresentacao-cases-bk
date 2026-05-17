# 🎬 Apresentação Cinematográfica de Cases - Burger King

Esta é uma aplicação interativa e imersiva de alto nível desenvolvida para apresentar cases históricos de marketing do **Burger King**. O projeto utiliza as tecnologias web mais modernas para criar uma experiência fluida, contínua e visualmente impactante.

---

## ✨ Recursos de Destaque

*   **⚡ Transição de Slides Fluida (View Transitions API):** Efeito de "empurrão" lateral contínuo combinado com efeito Morph, fazendo com que todos os slides pareçam parte de um único ecossistema em constante transformação.
*   **🎭 Orquestração de Animações (Anime.js):** Efeitos de entrada *staggered* (cascata) com física de mola elástica (`easeOutElastic`) aplicados nos blocos de texto e badges a cada transição de slide.
*   **📺 Player de Vídeo Premium Customizado:**
    *   **Timeline Interativa:** Navegação rápida de clipe com clique ou arrasto.
    *   **Controles Pop-up (Glassmorphism):** Barra de controle flutuante com desfoque de fundo avançado, que surge suavemente apenas ao passar o mouse.
    *   **Ajuste de Velocidade:** Controles dedicados de velocidade de reprodução (`1x`, `1.5x`, `2x`).
    *   **Tela Cheia Imersiva:** Modo tela cheia total adaptado para vídeos verticais (`object-fit: contain`) mantendo os botões premium customizados visíveis na base da tela.
    *   **Loop & Replay:** Atalhos rápidos para estudar frames específicos de cada campanha.
*   **🎨 Estética Dark Premium:** Paleta de cores escura e contrastante com tons de laranja neon, inspirados na identidade visual do Burger King.

---

## 🛠️ Tecnologias Utilizadas

*   **HTML5** (Estruturação Semântica & Player de Vídeo nativo)
*   **Vanilla CSS3** (Flexbox/Grid, Custom Properties, Glassmorphism, CSS Transitions/Animations)
*   **Vanilla JavaScript** (Orquestração de Estados, Event Listeners do Player)
*   **Anime.js** (Motor de Animação de Alta Performance)
*   **View Transitions API** (Transições Contínuas entre Slides)

---

## 🚀 Como Executar Localmente

Como a aplicação faz uso da **View Transitions API** e busca vídeos locais em caminhos relativos, o navegador pode bloquear requisições sob o protocolo `file://` (CORS). **Recomendamos servir a aplicação através de um servidor local.**

### Opção 1: Usando Live Server (VS Code)
1. Instale a extensão **Live Server** no VS Code.
2. Abra a pasta do projeto.
3. Clique em **Go Live** na barra inferior do editor.

### Opção 2: Servidor HTTP Simples (Node.js)
Caso tenha o Node.js instalado, você pode usar o `npx`:
```bash
npx serve .
```

### Opção 3: Servidor Python
Caso tenha o Python instalado:
```bash
# Python 3
python -m http.server 8000
```
Depois, acesse `http://localhost:8000` no seu navegador de preferência.

---

Desenvolvido com carinho para transformar dados em cinema. 🍔🍿
