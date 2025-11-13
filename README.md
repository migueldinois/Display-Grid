# Display-Grid 🧩

![Estudo - CSS Grid](https://img.shields.io/badge/Estudo-CSS%20Grid-blue)
![Status](https://img.shields.io/badge/Status-Em%20desenvolvimento-yellow)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

Descrição: projeto de estudo para praticar e documentar conceitos de CSS Grid e layout responsivo. Este repositório contém exemplos práticos, exercícios e pequenas demos organizadas por pastas para facilitar o aprendizado.

### Conteúdo rápido

- **Objetivo:** aprender e experimentar técnicas de layout com CSS Grid e flexbox complementarmente.
- **Público:** estudantes e desenvolvedores que estão começando a entender Grid Layout.
- **Formato:** exemplos estáticos (HTML/CSS), com comentários e screenshots quando úteis.

## Estrutura do repositório 📁

- `01_Intro-css-grid/` — Introdução ao Grid, conceitos básicos e exemplos simples.
- `02_Container-alinhamentos/` — Técnicas de alinhamento de itens e containers.
- `02.1_Container-alinhamentos/` — Variedades de alinhamento e exemplos adicionais.
- `02.2_Media-layout/` — Exemplos com media queries e layouts responsivos.
- `03_Layout-grid-flexbox/` — Casos combinados Grid + Flexbox e padrões de layout.

> Dica: abra os arquivos `index.html` dentro de cada pasta no navegador para visualizar as demos.

## Como usar (rápido) ▶️

1. Clone o repositório ou faça o download.
2. Abra a pasta do projeto no seu editor (por exemplo, VS Code).
3. Abra um HTML no navegador (arraste o arquivo ou use uma extensão Live Server).

Exemplo de comando (PowerShell) para abrir com o Live Server no VS Code:

```powershell
code .
# então ative Live Server ou abra o arquivo HTML no navegador
```

## Exemplo rápido de CSS Grid

HTML mínimo:

```html
<div class="grid">
  <div>1</div>
  <div>2</div>
  <div>3</div>
  <div>4</div>
</div>
```

CSS mínimo:

```css
.grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 12px;
}
.grid > div {
  background: #0ea5e9;
  color: #fff;
  padding: 16px;
  text-align: center;
}
```

## Badges e ícones 🎨

- Use emojis para marcar seções e tornar o README mais agradável: 🚀, 🧩, 📁, ⚙️
- Para badges dinâmicos, use o serviço `shields.io` como já demonstrado no topo.

## Boas práticas de estudo ✅

- Faça pequenas alterações nos exemplos e observe o resultado no navegador.
- Comente seu CSS para lembrar decisões de layout.
- Compare Grid e Flexbox para entender quando usar cada um.

## Contribuição 🤝

Contribuições são bem-vindas: abra issues com dúvidas, sugestões de exercícios ou PRs com correções e melhorias.

### Guias rápidos para PR

- Faça um fork e trabalhe em branch nomeada `feature/nome-da-feature`.
- Explique a mudança no título do PR e adicione um comentário descrevendo o que foi feito.

## Licença

Este projeto está sob a licença MIT — veja o arquivo `LICENSE` (se não existir, posso adicionar um template).

## Contato

- Autor: estudo pessoal
- Email: (adicione seu contato) ou use o perfil do GitHub.

---

Se quiser, eu posso:

- adicionar um `LICENSE` (MIT) automaticamente;
- gerar imagens/snapshots de exemplos e adicioná-los em `assets/`;
- traduzir o README para inglês.

— Boa prática: mantenha o README enxuto e direcionado ao objetivo de estudo.
