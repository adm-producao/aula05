# Aula 05 — Plano Mestre de Produção

## Objetivo

Apresentação xaringan da Unidade 05, dedicada ao Plano Mestre de Produção (PMP), aos seus elementos críticos e a exemplos de cálculo.

## Arquivos principais

- `index.Rmd`: fonte da apresentação.
- `index.html`: apresentação renderizada e publicada pelo GitHub Pages.
- `ufcimg-slides-v2.css`: identidade visual e regras de diagramação ativas.
- `ufcimg-slides.css`: versão anterior, mantida para rastreabilidade.
- `slides.css` e `xaringan-themer.css`: estilos complementares existentes.
- `setup.Rmd`: configuração dos pacotes e opções do R Markdown.

## Ajuste de diagramação de 09/11/2026

Foram criadas classes específicas para slides densos e tabelas largas. As alterações:

- mantêm todas as tabelas dentro da largura útil do slide;
- reduzem espaçamento e tipografia somente nos slides que exigem maior densidade;
- reorganizam o slide 14, com cabeçalhos em duas linhas e notas sintéticas abaixo da tabela;
- compactam o quadro de congelamento do horizonte;
- reequilibram as colunas do exemplo de smartphone;
- preservam o conteúdo analítico e a identidade visual UFCIMG.
- usam um nome versionado para o CSS, evitando que o navegador reutilize a folha de estilos anterior após a publicação.

## Reprodução

No diretório do projeto, execute:

```r
rmarkdown::render("index.Rmd", output_file = "index.html")
```

Depois, confira visualmente os slides 7, 10, 13, 14, 16 e 18 em uma janela 16:9. A validação deve observar largura das tabelas, altura total do conteúdo, legibilidade e ausência de colisão com o rodapé.

## Limitações

A apresentação depende das fontes remotas definidas nos arquivos CSS. Caso elas não sejam carregadas, a substituição por fontes locais pode alterar discretamente as quebras de linha.
