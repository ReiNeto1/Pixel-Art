# Pixel-Art🎨

## LEIA-ME

* Projeto:  
 Este é um projeto de estudo em JavaScript que permite criar pixel art diretamente no navegador. O projeto foi desenvolvido com o objetivo de praticar habilidades em HTML,
 CSS e JavaScript, além de manipulação de eventos e DOM. O usuário pode escolher o tamanho da nota, selecionar núcleos, desenhar pixels e até baixar suas criações em formato de imagem

## Função

Definir o tamanho
Selecione a cor da pintura
Visualizar
Limpar todo o desenho ou desligar
Redimension
Baixar arte em formato de imagem PNG

## Técnica

* HTML
* CSS
* Java
* Fonte
* HTML2tela
  



## Técnica Usada

* A principal técnica usada no JavaScript deste projeto de Pixel Art é a manipulação do DOM (Document Object Model) , que envolve a criação, alternância e interação com os elementos HTML dinamicamente. Isso inclui:

## Criação dinâmica de elementos :

* O JavaScript cria grades de pixels e seus contêineres de formato dinâmico, permitindo ao usuário definir o tamanho da grade e manipular a arte pixel por pixel. A função createElement()é usada para gerar novos elementos HTML (como os "pixels") e inserir no documento.

## Eventos de interação do usuário :

* Eventos como mousedown, mouseovere mouseupsão usados ​​para permitir que o usuário pinte os pixels ao clicar e arrastar. Também há manipulação de eventos para apagar pixels ou alternar entre modos de pintura e borracha.

## Manipulação de estilos e cores :

* Os núcleos dos pixels são alterados diretamente através da manipulação de CSS inline no JavaScript usando o style.backgroundColor. O usuário pode selecionar um cor e esse cor é aplicado diretamente aos pixels clicados.

## Armazenamento e reutilização de núcleos :

* O projeto registra as cores usadas pelo usuário, permitindo que elas sejam reutilizadas com um simples clique, o que melhore a usabilidade.

## Exportação para imagem :

* A biblioteca html2canvasfoi utilizada para capturar o conteúdo do canvas de pixel art e exportá-lo como uma imagem PNG, ou que demonstre a integração de bibliotecas externas com o projeto.

Essas técnicas juntas permitem uma aplicação interativa e dinâmica, essencial para projetos voltados à manipulação visual como este.


** Baseado da aula foi do git:
 ## Manualdodev 