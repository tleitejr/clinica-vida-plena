# Clínica Vida Plena

Site institucional fictício de uma clínica médica (Clínica Geral e Pediatria), feito apenas com **HTML5** e estilos básicos em uma tag `<style>`, sem CSS externo e sem JavaScript.

> **Este projeto é um fork** de [digitalinnovationone/trilha-html-modulo-2](https://github.com/digitalinnovationone/trilha-html-modulo-2).
> Substitua o link acima pelo endereço do repositório de origem.
> Este fork mantém o objetivo do projeto original (exercício de HTML) e traz a implementação da Clínica Vida Plena.

## Sobre o projeto

O projeto nasceu de um desafio de front-end: criar um site "quase" completo usando somente HTML, abordando obrigatoriamente **formulários**, **estruturação e formatação de texto**, **mídias** e **tabelas**. Todos os dados (nome da clínica, equipe, telefones, CNPJ e endereço) são fictícios.

## Páginas

| Arquivo | Página | Conteúdo |
|---|---|---|
| `index.html` | Página Principal | Missão, diferenciais, especialidades, vídeo do YouTube e áudio |
| `sobre.html` | Sobre a clínica | História, valores, equipe e estrutura, com formatação de texto variada |
| `horario.html` | Horário de Atendimento | Texto sobre os serviços e tabela de horários |
| `contato.html` | Contato | Telefones, endereço, mapa do Google e formulário de contato |

Todas as páginas compartilham o mesmo template: **menu** no topo, **header** com imagem própria, **conteúdo** específico e **footer** com os dados de contato.

## Recursos de HTML utilizados

- **Estrutura semântica:** `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<address>`
- **Texto:** `<h1>` a `<h2>`, `<p>`, `<strong>`, `<em>`, `<mark>`, `<sub>`, `<blockquote>`, listas `<ul>` e `<ol>`
- **Mídia:** `<img>` com `alt`, `<figure>` e `<figcaption>`, `<audio>`, `<iframe>` do YouTube
- **Tabela:** `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<th scope>` e `<td>`
- **Formulário:** `<form method="post" action="#">`, `<label>` associado a cada campo, `<input type="text">`, `<input type="email">`, `<textarea>`, `required`, `placeholder`, botões `submit` e `reset`
- **Mapa:** `<iframe>` do Google Maps com `width`, `height`, `allowfullscreen`, `loading="lazy"` e `title`

## Estrutura de arquivos

```
clinica-vida-plena/
├── index.html
├── sobre.html
├── horario.html
├── contato.html
└── README.md
```

## Como executar

1. Clone o repositório (ou baixe os arquivos):
   ```bash
   git clone https://github.com/tleitejr/clinica-vida-plena.git
   cd clinica-vida-plena
   ```
2. Abra o arquivo `index.html` no navegador (clique duas vezes ou use "Abrir com").
3. Navegue pelas páginas usando o menu.

Não é preciso instalar nada. É necessário ter internet para carregar as imagens de placeholder, o vídeo, o áudio e o mapa.

## Personalização

- **Imagens:** os headers usam `https://placehold.co/`. Troque o `src` por imagens reais da clínica.
- **Vídeo:** altere o código no final da URL do `<iframe>` do YouTube em `index.html`.
- **Áudio:** substitua o arquivo de exemplo no `<source>` em `index.html`.
- **Endereço e mapa:** edite o endereço no footer e o parâmetro `q=` do `<iframe>` em `contato.html`.
- **Cores:** ajuste as variáveis em `:root` na tag `<style>` de cada arquivo.

## Limitações

- O formulário usa `action="#"` e não envia dados a nenhum servidor.
- O CSS está repetido em cada página, porque o desafio não permite CSS externo.

## Mantendo o fork atualizado

```bash
git remote add upstream https://github.com/digitalinnovationone/trilha-html-modulo-2.git
git fetch upstream
git merge upstream/main
```
