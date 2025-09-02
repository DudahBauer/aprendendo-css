# 🎨 Estudo de Animações CSS com Emojis

Um projeto simples e visual criado para praticar e demonstrar conceitos fundamentais de animações em CSS3. A página apresenta uma tabela com diferentes emojis, cada um com uma animação única e em loop.

---

### ✨ Demonstração Visual

<p align="center">
  <img src="demo.gif" alt="Demonstração das animações de emoji" width="400"/>
</p>

---

### 🚀 Funcionalidades

O projeto demonstra 3 tipos diferentes de animações puras com CSS:

* ❤️ **Pulsar:** Os emojis de coração usam `transform: scale()` para criar um efeito de pulsação suave.
* ⭐ **Piscar (Twinkle):** As estrelas usam a propriedade `opacity` para "sumir e aparecer", com `animation-delay` para que não pisquem todas ao mesmo tempo.
* ⚽ **Pular (Bounce):** As bolas de futebol usam `transform: translateY()` para criar uma animação de pulo contínuo.

---

### 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando apenas tecnologias web front-end básicas:

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

---

### 📖 Conceitos Praticados

O principal objetivo deste projeto foi aprofundar os conhecimentos em CSS, especialmente em:

* **Estrutura HTML Semântica:** Uso correto de `<table>`, `<caption>`, `<td>` e `<span>` para isolar elementos.
* **Layout com Flexbox:** Para centralizar a tabela principal na página.
* **Animações com `@keyframes`:** Definição de múltiplos estágios para uma animação complexa.
* **Propriedade `animation`:** Controle de duração, repetição (`infinite`), função de tempo (`ease-in-out`) e nome da animação.
* **Transformações 2D:**
    * `scale()`: Para aumentar e diminuir o tamanho dos elementos.
    * `translateY()`: Para mover elementos no eixo vertical.
* **Animação de `opacity`:** Para criar efeitos de fade-in e fade-out.
* **Seletores Avançados:** Uso de seletores descendentes (`.hearts span`) para aplicar estilos a elementos específicos.
* **Controle de Sincronia:** Uso de `animation-delay` para criar um efeito mais natural e assíncrono.

---

### 📂 Como Executar o Projeto

Você pode visualizar o resultado final de duas maneiras:

**1. Online (via GitHub Pages)**
Acesse a demonstração ao vivo em: `https://SEU-USUARIO.github.io/NOME-DO-SEU-REPOSITORIO/`

**2. Localmente**
```bash
# 1. Clone o repositório
git clone [https://github.com/SEU-USUARIO/NOME-DO-SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-SEU-REPOSITORIO.git)

# 2. Navegue até a pasta do projeto
cd NOME-DO-SEU-REPOSITORIO

# 3. Abra o arquivo index.html no seu navegador
