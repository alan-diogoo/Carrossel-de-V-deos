# Carrossel de Vídeos

Este é um projeto HTML, CSS e JavaScript que implementa um carrossel de vídeos com funcionalidade de navegação horizontal por meio de botões de seta e toque em dispositivos móveis. O carrossel exibe vídeos do YouTube em cartões interativos.

## Funcionalidades

- Exibe uma lista de vídeos do YouTube em um carrossel horizontal.
- Os botões de seta permitem navegar entre os vídeos no carrossel.
- Funcionalidade de toque em dispositivos móveis para navegação.

## Como Usar

1. Clone ou faça o download deste repositório para o seu computador.
2. Abra o arquivo `index.html` em um navegador da web compatível.

## Estilos

O carrossel é estilizado usando CSS, com as seguintes características principais:

- Layout responsivo para uma experiência agradável em diferentes tamanhos de tela.
- Cartões de vídeo com sombra suave e animação de elevação ao passar o mouse.
- Botões de navegação do carrossel com animações sutis ao passar o mouse.
- O carrossel se adapta automaticamente a telas menores, como dispositivos móveis.

## JavaScript

O JavaScript controla a funcionalidade do carrossel, permitindo a navegação por botões de seta e toque. As principais funções incluem:

- `updateCarouselPosition()`: Atualiza a posição do carrossel com base na largura do slide atual.
- Manipuladores de evento de toque para capturar gestos de toque e atualizar a posição do carrossel.
- Funções de manipuladores de clique para os botões "Anterior" e "Próximo" para navegação.

## Recursos Adicionais

- O carrossel atualmente exibe quatro vídeos do YouTube, mas você pode adicionar ou remover vídeos adicionais ajustando a seção `<div class="carousel">` no HTML.
- Certifique-se de que seus vídeos do YouTube tenham a opção de incorporação habilitada para que possam ser exibidos corretamente no carrossel.

## Suporte ao Navegador

Este projeto foi testado e é compatível com navegadores modernos, incluindo Google Chrome, Mozilla Firefox, Microsoft Edge e Safari.

## Nota

Este projeto foi criado apenas para fins de demonstração e não possui recursos de reprodução de vídeo em tela cheia ou reprodução automática. Certifique-se de seguir as diretrizes de incorporação e uso de conteúdo do YouTube ao utilizar vídeos em projetos reais.
