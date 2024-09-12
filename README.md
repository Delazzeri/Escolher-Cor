Este código altera a cor de fundo da página e exibe o nome da cor selecionada ao clicar em um botão.

- Array de Cores:

O array `colors` contém uma lista de cores (ex.: `'Red'`, `'Blue'`, `'Yellow'`, etc.).

- Elementos Selecionados:

A constante `btn` seleciona o botão da página usando o ID `'btn'`.
A constante `color` seleciona um elemento com a classe `'color'`, onde o nome da cor será exibido.

- Alteração da Cor ao Clicar:
  
Um evento `click` é associado ao botão (`btn`).
Ao clicar, a função `getRandomColor()` é chamada para gerar um índice aleatório que corresponde a uma cor no array.
A cor correspondente é aplicada ao fundo da página (`background`) e o nome da cor é exibido no elemento selecionado pela classe `.color`.

- Função de Cor Aleatória:
  
A função `getRandomColor()` gera um número aleatório entre 0 e o comprimento do array de cores, retornando o índice de uma cor aleatória.

Resumindo, ao clicar no botão, uma cor aleatória é selecionada e aplicada ao fundo da página, e o nome da cor é mostrado na interface.
