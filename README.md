<!--
*** Obrigado por estar vendo o nosso README. Se você tiver alguma sugestão
*** que possa melhorá-lo ainda mais dê um fork no repositório e crie uma Pull
*** Request ou abra uma Issue com a tag "sugestão".
*** Obrigado novamente! Agora vamos rodar esse projeto incrível :D
-->

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Feedget - Feedback Widget</h3>
</p>

<!-- TABLE OF CONTENTS -->

## Tabela de Conteúdo

- [Tabela de Conteúdo](#tabela-de-conte%C3%BAdo)
- [Sobre o Projeto](#sobre-o-projeto)
  - [Feito Com](#feito-com)
- [Começando](#come%C3%A7ando)
  - [Pré-requisitos](#pr%C3%A9-requisitos)
  - [Estrutura de Arquivos](#estrutura-de-arquivos)
  - [Instalação](#instala%C3%A7%C3%A3o)
  - [Edição](#edi%C3%A7%C3%A3o)
  - [Publicação](#publica%C3%A7%C3%A3o)
- [Contribuição](#contribui%C3%A7%C3%A3o)

<!-- ABOUT THE PROJECT -->

## Sobre o Projeto

Este projeto visa a criação de um widget de Feedback que possa ser utilizado no momento em projetos web e mobile utilizando React.js e React Native, visto que o processo de instalação e configuração das libs no início de um projeto podem gerar certa complexidade e muitas vezes até erros que atrasam o processo, atrapalhando assim o fluxo de desenvolvimento.

### Feito Com

Abaixo segue o que foi utilizado na criação deste projeto Web:

- [React.js](https://pt-br.reactjs.org/) - O React é uma biblioteca JavaScript de código aberto com foco em criar interfaces de usuário em páginas web;
  - [React-dom](https://pt-br.reactjs.org/docs/react-dom.html) - O pacote react-dom provê métodos específicos para o DOM que podem ser usados no nível superior de sua aplicação como uma válvula de escape para sair do modelo do React se você precisar.
  - [React - Headlessui](https://headlessui.com/react/menu) - Os menus oferecem uma maneira fácil de criar componentes suspensos personalizados e acessíveis com suporte robusto para navegação pelo teclado.
- [Axios](https://axios-http.com/ptbr/) - Axios é um cliente HTTP baseado-em-promessas para o node.js e para o navegador. É isomórfico (= pode rodar no navegador e no node.js com a mesma base de código). No lado do servidor usa o código nativo do node.js - o modulo http, enquanto no lado do cliente (navegador) usa XMLHttpRequests.
- [Tailwindcss](https://tailwindcss.com/) - TailwindCSS é um framework como nenhum outro. Em vez de restringi-lo a um design de cenário, ele fornece as ferramentas e a padronização para construir exatamente o que você deseja.
  - [Forms](https://tailwindcss.com/docs/plugins#forms) - Plugin do TailwindCSS que adiciona uma camada de redefinição de formulário opinativo que torna mais fácil estilizar elementos de formulário com classes utilitárias.
  - [Scrollbar](https://github.com/adoxography/tailwind-scrollbar) - Plugin do TailwindCSS que adiciona utilitários de estilo para barras de rolagem no Firefox e navegadores baseados em webkit.
- [Phosphor Icons](https://github.com/phosphor-icons/phosphor-home#react) - Phosphor é uma família de ícones flexível para interfaces, diagramas, apresentações.
- [Html2canvas](https://www.npmjs.com/package/html2canvas) - O script permite que você faça "capturas de tela" de páginas da Web ou partes delas, diretamente no navegador do usuário.
- [TypeScript](https://www.typescriptlang.org/) - TypeScript é uma linguagem de programação de código aberto desenvolvida pela Microsoft. É um superconjunto sintático estrito de JavaScript e adiciona tipagem estática opcional à linguagem.
- [PostCSS](https://postcss.org/) - O PostCSS é uma ferramenta de desenvolvimento de software que usa plug-ins baseados em JavaScript para automatizar operações CSS de rotina. 
  - [Autoprefixer](https://www.npmjs.com/package/autoprefixer) - Plugin do PostCSS para analisar CSS e adicionar prefixos de fornecedores a regras CSS usando valores de  Can I Use . É recomendado pelo Google e usado no Twitter e no Alibaba.
- [Vite](https://vitejs.dev/) - É uma ferramenta de construção que visa fornecer uma experiência de desenvolvimento mais rápida e enxuta para projetos web modernos.

<!-- GETTING STARTED -->

## Começando

Para conseguir utilizar o projeto, siga os passos abaixo.

### Pré-requisitos

Antes de seguirmos para as configurações, é que a versão do Node que você tenha instalado seja a 14 ou superior, para isso você pode seguir o guia do link abaixo:

[Node 14.9.3 (LTS)](https://nodejs.org/download/release/v14.19.3/)

### Projetos

Segue abaixo caminho do README.md dos projetos:

```bash
feedget/
├── mobile/
  └── [README.md](https://github.com/arielramosdebraga/feedget/tree/main/mobile)
├── server/
  └── [README.md](https://github.com/arielramosdebraga/feedget/tree/main/server)
├── web/
  └── [README.md](https://github.com/arielramosdebraga/feedget/tree/main/web)
```

### Publicação

[Site da Aplicação Web](https://feedget-widget-feedback-or49ph2pf-arielramosdebraga.vercel.app/);
[Site do Servidor](https://feedget-widgetfeedback-production.up.railway.app/);

## Contribuição

Contribuições são o que fazem a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/FeatureIncrivel`)
3. Adicione suas mudanças (`git add .`)
4. Comite suas mudanças (`git commit -m 'Adicionando uma Feature incrível!`)
5. Faça o Push da Branch (`git push origin feature/FeatureIncrivel`)
6. Abra um Pull Request