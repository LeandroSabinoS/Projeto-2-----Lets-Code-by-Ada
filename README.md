# Projetos---Let-s-Code-by-Ada

 #### Arquivos
 #- É utilizado os dados (dataset) de frutas (`frutas.txt`) disponível em um arquivo separado para compor o banco de palavras possíveis.
 #- É utilizado um banco de imagens que ilustra a quantidade de erros durante a partida.


### Solução

Nesse projeto é desenvolvido um programa que permita aceitar ações da pessoa usuária (`input`).

Nesse processo, o programa deve selecionar uma palavra aleatória do arquivo `frutas.txt`.

A partir da palavra aleatória, a pessoa usuária pode inserir um caracter, e se tiver acerto, a palavra será preenchida. Em caso de erro, será retirada uma "vida" da pessoa usuária e o desenho da pessoa na forca deve ser preenchida.

Na tela, teremos:
- Desenho da forca.
- Letras já escolhidas.
- Uma linha mostrando a palavra.
  - No inicio cada letra da palavra a ser adivinhada é representada com `_`.
  - Ao acertar a letra presente na palavra, as posições referentes a essa letra serão substituidas e mostrada para a pessoa usuária.

Para auxiliar no desenvolvimento, podemos dividir o projeto nas seguintes fases:
- Escolha da palavra aleatória
- Representar essa palavra com `_`.
- Ao acertar uma letra substituir o `_` pela letra nas posições corretas.
- Ao chegar no máximo de erros, encerrar o jogo.
- Ao acertar a palavra, finalizar o jogo.
- Ao errar uma letra, apresentar essas para a pessoa usuária.
- Ao errar uma letra, modificar o desenho da forca.