# Portfólio

Site pessoal para apresentar projetos, estudos e experiência profissional, com foco em front-end e em gestão de projetos ágeis.

## Problema

Reunir em um só lugar a trajetória técnica e os estudos de gestão (Scrum, PMO, documentação e entrega), com uma apresentação clara e responsiva.

## Stack

- HTML5
- CSS3, com Bootstrap e Font Awesome; o estilo próprio está em `css/style.scss`, compilado para `css/style.css`
- JavaScript, com jQuery e Bootstrap

**Em andamento:** migração para Next.js + React + TypeScript. O código atual ainda é o site estático descrito acima.

## Como rodar

Não há build nem dependências. Clone o repositório e abra o `index.html` no navegador:

```bash
git clone https://github.com/Lucas-64/portfolio.git
cd portfolio
```

Para atualizar a página automaticamente ao editar, use a extensão Live Server no VS Code.

## Estrutura

```text
├── index.html      página inicial
├── about.html      sobre
├── service.html    serviços
├── contact.html    contato
├── guard.html
├── css/            Bootstrap, Font Awesome, style.css e style.scss
├── js/             jQuery, Bootstrap e custom.js
├── fonts/          fontes Font Awesome e Octin Sports
└── images/         imagens das seções e dos projetos
```

## Status

Em andamento: o layout e o conteúdo estão publicados no repositório, e a migração para Next.js está sendo feita.

## Próximos passos

- Concluir a migração para Next.js + React + TypeScript.
- Adicionar novos estudos de caso de gestão de projetos.
- Melhorar a responsividade e a organização visual.
