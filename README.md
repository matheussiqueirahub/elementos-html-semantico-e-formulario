# Matrix — Formulário Semântico

> HTML semântico, acessível e responsivo com um toque de Matrix (code rain em canvas). Perfeito para compor seu portfolio.

## Destaques

- Semântica: `header`, `nav`, `main`, `section`, `fieldset`, `legend`, `footer`.
- Acessibilidade: rótulos associados, `aria-live` para feedback, foco visível, skip link, `prefers-reduced-motion` respeitado.
- Formulário completo: nome, e‑mail, senha, país (select), mensagem (textarea) e botões de enviar/limpar.
- Validações nativas + UX: mensagens amigáveis, contador de caracteres e persistência local (localStorage).
- Visual Matrix: animação de code rain (canvas) discreta, tipografia monoespaçada e acentos neon.

## Estrutura

- `index.html` — marcação semântica e acessível.
- `styles.css` — tema Matrix, alto contraste, responsivo.
- `script.js` — code rain, validações e pequenos detalhes de UX.

## Como rodar localmente

1. Abra o arquivo `index.html` no navegador.
2. Opcional: sirva com um HTTP server simples (ex.: `npx serve`), mas não é obrigatório.

## Publicar no GitHub Pages

Crie um repositório no seu GitHub (ex.: `matrix-form`). Depois, dentro da pasta `matrix-form`:

```bash
git init
git add .
git commit -m "feat: formulário semântico Matrix + animação e acessibilidade"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/matrix-form.git
git push -u origin main
```

No repositório no GitHub: Settings → Pages → Build and deployment → Source: `Deploy from a branch` → `main` → `/ (root)` e salve. A URL ficará algo como `https://SEU_USUARIO.github.io/matrix-form/`.

## Personalização rápida

- Título e textos: edite no `index.html`.
- Cores: ajuste as variáveis CSS em `styles.css` (ex.: `--accent`).
- Animação: para desabilitar permanentemente o code rain, remova a chamada `startMatrixRain()` no `script.js`.

---

Feito com carinho pela web aberta. Divirta‑se! 🟩

