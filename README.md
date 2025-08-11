# Landing Page – Trilha de CSS

Landing page simples feita com **HTML5** e **CSS3**.

## Como usar
1. Baixe/clones este projeto.
2. Abra `index.html` no navegador.  
   (Opcional: use a extensão Live Server do VS Code.)

## Estrutura
/
├─ index.html
├─ style.css
├─ reset.css
└─ assets/
├─ logo.png
├─ banner.png
├─ professional-challenges.png
├─ woman-code.png
└─ dio-logo.png

markdown
Copiar
Editar

## 🧩 Tecnologias
- HTML5 semântico
- CSS3 (variáveis, responsividade, efeitos visuais)
- Reset CSS (importado em `style.css`)

## 🖌️ Destaques de UI/UX
- Título com **gradiente** usando `background-clip: text`.
- Seção “Transforme o mundo” com **parallax** (`background-attachment: fixed`).
- Botão com **shadow interno** e **hover** suave.
- Layout **responsivo** com `clamp()` e _breakpoint_ para telas pequenas.

## ⚙️ Personalização rápida
Cores principais em `:root` dentro do `style.css`:
```css
:root {
  --primary: #33A8DB;
  --primary-2: #31A8DD;
  --primary-80: #33A8DB80;
  --text: #ffffff;
}
