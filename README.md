# css.fundamentos

Um guia visual e interativo de CSS — do zero ao olho de designer.

Criado com auxílio do [Claude](https://claude.ai) (Anthropic) para fins **100% didáticos**.

---

## 📖 Sobre o projeto

Este é um arquivo HTML único (`fundamentos-css.html`) que funciona como um site de referência completo sobre CSS. Cada seção demonstra um conceito **na prática**, com demos interativos, código comentado e syntax highlighting — feito para ser estudado diretamente no browser com o DevTools aberto ao lado.

Não há dependências, frameworks ou build step. Basta abrir o arquivo no browser.

---

## 📚 Conteúdo

### Fundamentos (Fase 0)
- **Box Model** — margin, padding, border, content e `box-sizing: border-box`
- **Flexbox** — demos de `justify-content`, `align-items`, `flex-grow` e `flex-direction`
- **CSS Grid** — sistema de 12 colunas, placement explícito, named areas, `auto-fill` vs `auto-fit`, responsividade com 4 abordagens (incluindo Container Queries) e simulador de breakpoints interativo

### Tipografia (Fase 1)
- **Tipografia** — pairing de fontes (Playfair Display + DM Sans), escala com `clamp()`, hierarquia e ritmo vertical

### Estilo Visual (Fase 2)
- **Cor & HSL** — CSS Custom Properties, modelo HSL e paleta de design tokens
- **Gradients** — `linear-gradient`, `radial-gradient`, `conic-gradient`, `repeating-*`, hard stops e demo interativa de color stops
- **Unidades CSS** — tabela completa com `px`, `rem`, `em`, `ch`, `vw`, `vh`, `dvh`, `svh`, `lvh`, `fr`, `clamp()`, `calc()` e mais
- **Texturas** — 9 padrões feitos 100% em CSS (dots, grid, stripes, checker, grain, noise...)
- **clip-path** — `circle()`, `ellipse()`, `polygon()`, `inset()`, morph no hover e link para o Clippy
- **::before & ::after** — 9 casos de uso com demos ao vivo (overlay, badge, tooltip, counter CSS, fade mask...)

### Animações (Fase 3)
- **@keyframes** — 10 animações com preview interativo (`fadeUp`, `pulse`, `bounce`, `shimmer`, `ping`...), lista de outros e links para MDN e Animate.css
- **Transitions & cubic-bezier** — 4 curvas diferentes com demo de hover

### Referência
- **Propriedades-chave** — 22 propriedades organizadas em 6 categorias com busca e filtro interativos
- **Olho de Designer** — hábitos, ferramentas e links úteis
- **Próximos passos** — 12 tópicos para continuar evoluindo (`filter`, `@layer`, `scroll-snap`, `mix-blend-mode`, View Transitions API...)

---

## ✨ Funcionalidades interativas

- **Navbar com dropdown** agrupado por categoria (com hamburger menu no mobile)
- **Simulador de breakpoints** na seção de Grid (mobile / tablet / desktop / wide)
- **Demo de color stops** com botões para trocar entre 2, 3, 4, 5 stops, hard stops e transparência
- **Preview de @keyframes** com animações pausadas que rodam no hover
- **Filtro e busca** nas Propriedades-chave
- **Resize interativo** de grid responsivo na seção de Grid
- **IntersectionObserver** em todas as seções — elementos revelam ao entrar na viewport
- **Caixa arrastável** para ver `auto-fill` em ação em tempo real

---

## 🛠 Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML semântico | `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>` |
| CSS puro | Todas as demos, animações, layouts e efeitos visuais |
| JavaScript vanilla | IntersectionObserver, hamburger menu, filtros, simuladores |
| Google Fonts | Playfair Display + DM Sans |

Nenhuma biblioteca externa de JS ou framework CSS foi utilizada.

---

## 🚀 Como usar

1. Clone ou baixe o repositório
2. Abra `fundamentos-css.html` diretamente no browser
3. Navegue pelas seções usando a navbar
4. **Abra o DevTools** (F12) e inspecione os elementos enquanto lê — é assim que o aprendizado acontece de verdade

---

## 🔗 Ferramentas mencionadas no guia

- [typescale.com](https://typescale.com) — escala tipográfica
- [cubic-bezier.com](https://cubic-bezier.com) — curvas de animação
- [bennettfeely.com/clippy](https://bennettfeely.com/clippy/) — gerador de clip-path
- [animate.style](https://animate.style) — biblioteca de referência de @keyframes
- [coolors.co](https://coolors.co) — paletas HSL
- [cssgrid-generator.netlify.app](https://cssgrid-generator.netlify.app) — gerador de CSS Grid
- [awwwards.com](https://awwwards.com) — inspiração de design
- [dribbble.com](https://dribbble.com) — referências visuais
- [MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web/CSS) — documentação oficial

---

## 📄 Licença

MIT — veja o arquivo [LICENSE](./LICENSE) para detalhes.

---

> Criado com auxílio do Claude (Anthropic) · Uso didático
