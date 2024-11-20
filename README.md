# previsao.do.tempo

Esse projeto é uma página simples de previsão do tempo, feita em HTML, com integração de estilo e funcionalidades de interação. A estrutura principal é composta por:

HTML:

A página começa com a declaração do tipo de documento <!DOCTYPE html> e define o idioma como português brasileiro com <html lang="pt-br">.
No <head>, são configurados o conjunto de caracteres (UTF-8), a visualização responsiva para dispositivos móveis, e o carregamento de fontes do Google Fonts (Open Sans e Poppins).
O arquivo style.css é incluído para estilizar o conteúdo da página, e o script.js para funcionalidades de interação (com o atributo defer para garantir que o script só seja carregado após o HTML).
O título da página é definido como "Previsão do Tempo".
Corpo da página:

O conteúdo é encapsulado em uma estrutura <div> com a classe caixa-maior.
Um campo de input permite ao usuário digitar o nome de uma cidade, com um botão de busca ao lado, que possui um ícone de lupa.
Abaixo, há uma <div class="caixa-media"> que exibe informações sobre o tempo da cidade, incluindo:
O nome da cidade (atualmente fixado em "São Paulo").
A temperatura (atualmente fixada em "21ºC").
Um ícone e texto descrevendo as condições do tempo (atualmente "Nublado").
A umidade do ar (atualmente "76%").
Funcionalidade (JavaScript):

O botão de busca possui um evento onclick que chama a função cliqueiNoBotao(), definida no arquivo script.js (a funcionalidade dessa função não está implementada neste trecho de código, mas, provavelmente, ela iria buscar os dados de previsão do tempo para a cidade digitada pelo usuário).
Resumindo, esse projeto tem o objetivo de fornecer informações sobre a previsão do tempo, permitindo ao usuário consultar a previsão de uma cidade específica, embora a interação completa ainda precise de implementação no código JavaScript.
