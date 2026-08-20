# 🌟 Minimalist Dynamic Glow Button

Um componente de botão moderno, minimalista e tecnológico com um efeito de "Glow Dinâmico" (Dynamic Shadow/Glow) que segue o movimento do cursor do mouse. Desenvolvido com HTML, CSS e JavaScript puros (Vanilla).

## 🚀 Funcionalidades

*   **Mouse Follow Glow:** Uma luz de fundo suave e tecnológica que rastreia a exata coordenada (X e Y) do cursor sobre o botão.
*   **Design Minimalista:** Estética limpa, com bordas translúcidas e efeito "glassmorphism" suave.
*   **Zero Dependências:** Funciona perfeitamente sem bibliotecas externas como React, Vue ou Tailwind.
*   **Pronto para Google Sites:** O código foi estruturado em um único bloco, ideal para a função "Incorporar Código" de construtores de sites.

## 🛠️ Tecnologias Utilizadas

*   **HTML5:** Estrutura limpa e semântica.
*   **CSS3:** Utilização de `radial-gradient` dinâmico, variáveis CSS (`--x`, `--y`) e transições suaves.
*   **JavaScript:** Cálculo em tempo real do `BoundingClientRect` para mapear o cursor do usuário.

## 💻 Como usar

### Uso padrão (Seu próprio projeto web)
Basta copiar a estrutura do arquivo `index.html` e adicionar ao seu projeto. 

### Uso no Google Sites
1. Abra a página de edição do seu Google Sites.
2. No menu lateral direito, clique em **Inserir > Incorporar**.
3. Selecione a aba **Incorporar código**.
4. Cole todo o código HTML fornecido neste repositório.
5. Clique em **Próximo** e depois em **Inserir**.

## 🎨 Customização

Você pode alterar facilmente a cor e o tamanho do brilho editando esta parte do CSS:

```css
background: radial-gradient(
  circle 70px at var(--x) var(--y), /* Altere "70px" para mudar o tamanho do brilho */
  rgba(0, 212, 255, 0.4),          /* Altere o RGB para mudar a cor do brilho */
  transparent 100%
);
