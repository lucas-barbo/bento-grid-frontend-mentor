# Bento Grid Front-End Mentor

![grid-desktop](README/screencapture-grid-desktop.png)

Veja: [pagina online](https://lucas-barbo.github.io/bento-grid-frontend-mentor/)

## Sobre o projeto

Este é um desafio do [Frontend Mentor], uma página em display grid.

O objetivo é criar um container grid com 8 caixas de conteúdo, torná-la responsiva (desktop, tablet, celular) e tornar a interface desenvolvida o mais próxima possível do design do Figma.

O layout na tela desktop segue um padrão bento grid.

## Como foi desenvolvido

Para reproduzir esse design, usei uma estrutura semântica do HTML. Criei classes utilitárias para definir os estilos de fonte, o que me permite fazer as alterações facilmente de acordo com a responsividade, ao contrário de usar variáveis, o que me obrigaria a definir o estilo de cada tag de texto individualmente, aumentando as linhas de código.

Padrão BEM para definir as classes dos elementos, garantindo legibilidade, padronização e manutenção facilitada.

Usei a pseudo-classe :nth-child para estilizar cada elemento do grid individualmente sem a necessidade de criar classes específicas, e também usei o aninhamento de classes.

**Fique à vontade para sugerir alterações e melhorias.**