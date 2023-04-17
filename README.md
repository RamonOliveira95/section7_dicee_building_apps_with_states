# section7_dicee_building_apps_with_states

# AULA 1 - 1.0.0
- Projeto criado com imagens de todos os lados de um dado;
- Foi adicionado uma linha com dois widgets de imagem para os dados ficarem lado a lado;
- Adicionado um Expanded antes de cada image para ocuparem o máximo da tela.

# AULA 2 - 1.0.1
- Adicionado um Center envolvendo a Row principal, fazendo com que os dados fiquem centralizados;
- Em cada Image foi adicionado um Padding de 16px para criar um espaçamento entre eles.

# AULA 3 - 1.0.2
- Retirado o Padding de cada image e adicionado um TextButton no lugar de cada um;
- Em cada TextButton foi adicionado um print informando que aquele botão foi pressionado.

# AULA 4 - 1.0.3
- Adicionado variável para receber o valor do dado;
- Esse número do dado será enviado para a parte que recebe a informação de qual imagem usar.

# AULA 5 - 1.0.3
- Alterado de Stateless Widget para Stateful Widget;
- Adicionado um setState dentro do onePress do TextButton, para identificar o que vai mudar na tela.

# Aula 6 - 1.0.4
- Adicionado a biblioteca 'dart:math', pois através dela será randomizado algum valor;
- Dentro do setState foi adicionado Random().nextInt(6) + 1 para randomizar algo entre 1 e 6, pois se não tivesse esse +1, ele randomizaria entre 0 e 5.

# Aula 7 - 1.0.5
- Adicionado o modo Random para as duas imagens quando clica em pelo menos uma delas. Não precisa mais clicar em uma e depois na outra;
- Criado função chamada randomDice() dentro de um setState para mudar as imagens quando forem clicadas.