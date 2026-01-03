# SyntaxWear — E-commerce (HTML & CSS)

Projeto front-end estático de uma loja de tênis e sneakers. Contém a página principal (`index.html`) e os estilos organizados por componentes em CSS.

**Resumo:**
- **Stack:** HTML5, CSS3 (organizado em variáveis, base e componentes)
- **Objetivo:** protótipo responsivo de página principal para um e‑commerce de calçados

**Funcionalidades principais:**
- Cabeçalho com navegação e menu mobile
- Hero com CTA
- Seções de categorias e grid de produtos
- Rodapé com newsletter e navegação secundária

**Estrutura do projeto**
- [index.html](index.html) — página principal
- [css/variables.css](css/variables.css) — tokens (fontes, cores e imports)
- [css/reset.css](css/reset.css)
- [css/base.css](css/base.css)
- [css/components/header.css](css/components/header.css)
- [css/components/hero.css](css/components/hero.css)
- [css/components/product-category.css](css/components/product-category.css)
- [css/components/product-grid.css](css/components/product-grid.css)
- [css/components/footer.css](css/components/footer.css)
- [images/](images/) — imagens organizadas em `banners/`, `favicons/`, `icons/`, `logo/`, `products/`

Como o repositório está atualmente:
- A tipografia principal é definida em `css/variables.css` (import Google Fonts e `--fonte-principal: 'Ubuntu'`).
- Estilos estão divididos entre `base.css` e arquivos por componente em `css/components/`.

Como visualizar localmente
- Método simples (abrir arquivo):

```none
Abra o arquivo `index.html` no navegador (duplo-clique).
```

- Servidor local (recomendado para rotas/requests e assets):

```powershell
# Com Python 3 instalado (na raiz do projeto)
python -m http.server 8000
# Depois abra http://localhost:8000 no navegador
```

- Ou use a extensão Live Server do VS Code para reload automático.

Guia rápido de desenvolvimento
- Estruture alterações visuais em `css/components/` por responsabilidade (header, hero, footer, product-grid, etc.).
- Mantenha tokens (cores, fontes, espaçamentos) em `css/variables.css` para fácil manutenção.
- Assets (SVG/PNG) ficam em `images/` — use SVG para ícones quando possível.

Boas práticas e sugestões
- Otimize imagens em `images/products/` antes do deploy (WebP quando possível).
- Separe estados e variações de componente com classes utilitárias no `base.css`.
- Para internacionalização, mova textos para templates ou JSON quando crescer.

Deploy
- Projeto estático — pode ser publicado no GitHub Pages, Netlify ou Vercel. Para GitHub Pages, basta criar branch `gh-pages` com build (ou usar branch `main` com Pages configurado).

Contribuição
- Fork → branch com feature → PR com descrição clara.
- Execute testes visuais locais e inclua screenshots se alterar layout.

Licença
- MIT (adicione `LICENSE` se desejar formalizar).

Contato
- Desenvolvedor/autor: seu projeto local. Para ajuda ou ajustes, responda neste repositório com issues ou peça alterações diretamente.

---
Arquivo gerado automaticamente pelo assistente para documentar o front-end estático.
