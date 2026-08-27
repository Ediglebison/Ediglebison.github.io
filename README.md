# Ediglebison de Sousa — Portfólio

Site pessoal e portfólio profissional, publicado como página estática via **GitHub Pages**.

## Sobre

Página de apresentação com as seções **Sobre**, **Habilidades**, **Projetos**,
**Experiência Profissional**, **Formação** e **Cursos**. Construída em HTML, CSS e
JavaScript puro — sem framework e sem etapa de build.

## Funcionalidades

- **Design responsivo e acessível**: skip link, foco visível, contraste AA e
  respeito a `prefers-reduced-motion`.
- **Tema claro/escuro**: botão de alternância com preferência persistida em
  `localStorage` e detecção de `prefers-color-scheme` na primeira visita.
- **Idade automática**: calculada via JavaScript a partir da data de nascimento,
  sem valor fixo no código.
- **Catálogo de projetos**: thumbnails com screenshot das páginas de exibição ou
  ícone SVG para projetos que possuem apenas repositório.

## Tecnologias

- HTML5 semântico
- CSS com custom properties (design tokens) para temas claro/escuro
- JavaScript vanilla (sem dependências de runtime)

## Estrutura

| Caminho            | Conteúdo                                   |
| ------------------ | ------------------------------------------ |
| `index.html`       | Página principal                           |
| `css/estilos.css`  | Estilos e temas (claro/escuro)             |
| `img/`             | Avatar, ícones e thumbnails dos projetos   |

## Como visualizar localmente

Abra `index.html` no navegador, ou sirva a pasta raiz:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Deploy

Publicado automaticamente pelo GitHub Pages a partir da branch principal
(raiz do repositório).

## Links

- Site: https://ediglebison.github.io
- GitHub: https://github.com/Ediglebison
- LinkedIn: https://www.linkedin.com/in/ediglebison/
