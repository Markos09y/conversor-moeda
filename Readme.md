Projeto conversor de moedas.

Descrição do Conversor de Moedas:

Interface do Usuário (HTML):

A interface consistiria em elementos HTML como <input> para inserir o valor a ser convertido, utilizando caixas de opções para selecionar as moedas de origem e destino, e um botão de "Converter".

Lógica de Conversão (JavaScript):

Ao clicar no botão "Converter", um evento seria acionado, chamando uma função em JavaScript para executar a conversão.

A função de conversão capturaria o valor inserido pelo usuário no campo texto, a moeda de origem e a moeda de destino selecionadas.

Em seguida, a função usaria uma API de taxas de câmbio(https://api.exchangerate-api.com/v4/latest/) para obter as taxas de conversão atualizadas entre as moedas selecionadas.

Com base nessas taxas de câmbio, a função faria o cálculo para converter o valor da moeda de origem para a moeda de destino.

Por fim, o resultado da conversão seria exibido na interface do usuário, abaixo do botão "Converter".

Exemplo de Fluxo:

O usuário acessa a página do conversor de moedas e vê campos para inserir o valor, selecionar a moeda de origem e a moeda de destino, juntamente com o botão "Converter".

O usuário digita o valor que deseja converter.
O usuário seleciona a moeda de origem (por exemplo, USD) e a moeda de destino (por exemplo, EUR).
Após selecionar as moedas e inserir o valor, o usuário clica no botão "Converter".

O JavaScript executa a lógica de conversão, obtém as taxas de câmbio atualizadas e calcula o valor convertido. O resultado da conversão é exibido na interface do usuário.

