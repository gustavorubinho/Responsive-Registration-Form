# Formulário de Cadastro Responsivo - Responsive Registration Form

Um projeto simples e elegante de um formulário de cadastro, desenvolvido com **HTML5** e **CSS3**, com foco em **Responsividade** (adaptação a diferentes tamanhos de tela - adaptation to different screen sizes).

## Tecnologias Utilizadas

* HTML5
* CSS3 (Flexbox, Media Queries)
* Fonte: [Montserrat](https://fonts.google.com/specimen/Montserrat) (Google Fonts)

## Como a Responsividade Funciona (Proporções)

Para garantir que o formulário fique perfeito em qualquer dispositivo, desde monitores ultrawide até celulares, o projeto utiliza **CSS Media Queries** (`@media screen`). A página altera suas proporções em 3 pontos de quebra (breakpoints) principais:

### 1. Telas Grandes (Desktop - Acima de 1330px)
* **Proporção:** O container ocupa 80% da tela.
* **Layout:** Dividido exatamente ao meio (50% / 50%). O lado esquerdo exibe a imagem de ilustração e o direito exibe o formulário.
* <img width="1438" height="812" alt="image" src="https://github.com/user-attachments/assets/f24fbd68-11c0-4859-acfc-3fac0025c69c" />


### 2. Telas Médias (Tablets e Laptops menores - Até 1330px)
* **Proporção:** A imagem lateral é ocultada (`display: none`).
* **Adaptação:** Como a imagem some, o formulário (`.form`) que antes ocupava 50%, passa a ocupar **100%** do espaço disponível no container. O tamanho total do container é reduzido para 50% da tela para o formulário não ficar muito esticado.
* <img width="1319" height="812" alt="image" src="https://github.com/user-attachments/assets/6b9ef42d-a05b-4bb0-955b-a6fb8e324ed8" />


### 3. Telas Pequenas (Tablets em pé e Telas menores - Até 1064px)
* **Proporção:** O container passa a ocupar **90%** da tela para aproveitar melhor o espaço.
* **Adaptação:** Os inputs (nome, email, senha), que antes ficavam lado a lado, mudam para uma disposição em coluna (`flex-direction: column`), ficando um embaixo do outro. A seção de escolha de gênero também se empilha verticalmente.
* <img width="790" height="807" alt="image" src="https://github.com/user-attachments/assets/3b4f99ac-3547-4fd6-8ef8-472836590f33" />


### 4. Celulares (Até 600px)
* **Proporção:** O container ocupa **95%** da tela, e o padding (espaçamento interno) é reduzido.
* **Adaptação:** O cabeçalho (título e botão "Entrar") se alinha em coluna e centralizado para não quebrar o layout. O formulário utiliza todo o espaço vertical disponível, e o container se adapta ao conteúdo (`min-height`) para não cortar nenhuma informação.
* <img width="498" height="808" alt="image" src="https://github.com/user-attachments/assets/4eaf327f-efbc-4685-93c7-1531ed9d9fba" />


## Como acessar o formulário

1. Clique no link (https://gustavorubinho.github.io/Responsive-Registration-Form/) ao lado do Read.Me

## Como executar o projeto

1. Faça o download ou clone o repositório.
2. Abra a pasta do projeto.
3. Dê um duplo clique no arquivo `index.html` para abri-lo em seu navegador padrão.
