# SportClub

Página institucional responsiva para a academia SportClub, desenvolvida como projeto de Front-End do TDE. O site apresenta a proposta da academia, seus programas e um formulário de interesse.

## Tecnologias

- HTML5 para a estrutura semântica da página.
- CSS3 para identidade visual, Flexbox, CSS Grid, variáveis e media queries.
- Bootstrap 5.1.3 carregado por CDN, com Navbar, Cards, Buttons, formulários e sistema de colunas.

## Estrutura do projeto

```text
index.html    Página principal
css/pg.css    Estilos personalizados e responsividade
img/          Imagens usadas na interface
```

## Como visualizar

Abra `index.html` em um navegador com acesso à Internet para carregar o Bootstrap e a fonte usada nos títulos. Não há etapa de instalação ou compilação.

## Escolhas de interface

A página preserva a identidade rosa e azul do projeto original. O rosa (`#f26a8c` e `#fc8e93`) destaca a energia da marca; o azul escuro (`#263b60`) organiza títulos e áreas de contraste. A fonte Bebas Neue é usada nos títulos, enquanto os textos longos usam uma fonte sem serifa para facilitar a leitura.

O conteúdo foi organizado em apresentação, descrição da academia, programas, comunidade e formulário. As colunas do Bootstrap estruturam as seções; CSS Grid organiza a área de contato; Flexbox alinha a navegação, os botões e o conteúdo dos cartões. As media queries ajustam a composição em telas menores.

## Formulário

O formulário mostra os campos de interesse e utiliza controles do Bootstrap. O botão de envio permanece desativado até que seja definido um endereço de contato ou um serviço de recebimento. Nenhuma informação preenchida é transmitida.
