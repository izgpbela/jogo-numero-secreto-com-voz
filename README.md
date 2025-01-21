# Jogo do Número Secreto

Este projeto é um jogo simples de adivinhação de números, onde o jogador deve adivinhar um número secreto gerado aleatoriamente pelo sistema. O jogo fornece dicas se o número secreto é maior ou menor que o chute do jogador.

## Estrutura do Projeto

A estrutura do projeto é a seguinte:

js-curso-2-aula_2/ ├── app.js ├── img/ │ ├── JS Game_files/ │ │ ├── app.js │ │ └── style.css │ └── JS Game.html ├── index.html └── style.css


### Arquivos

- [`js-curso-2-aula_2/index.html`](js-curso-2-aula_2/index.html): Arquivo HTML principal que contém a estrutura do jogo.
- [`js-curso-2-aula_2/img/JS Game_files/style.css`](js-curso-2-aula_2/img/JS Game_files/style.css): Arquivo CSS principal que estiliza o jogo.
- [`js-curso-2-aula_2/app.js`](js-curso-2-aula_2/app.js): Arquivo JavaScript principal que contém a lógica do jogo.
- `img/JS Game_files/app.js`: Arquivo JavaScript alternativo (não utilizado).
- `img/JS Game_files/style.css`: Arquivo CSS alternativo (não utilizado).
- `img/JS Game.html`: Arquivo HTML alternativo (não utilizado).

## Lógica do JavaScript

O arquivo [`js-curso-2-aula_2/app.js`](js-curso-2-aula_2/app.js) contém a lógica principal do jogo. Aqui está um resumo das funções principais:

- `gerarNumeroAleatorio()`: Gera um número aleatório entre 1 e 10 que não foi sorteado anteriormente.
- `exibirTextoNaTela(tag, texto)`: Exibe um texto em um elemento HTML especificado pela tag e utiliza a API de síntese de fala para ler o texto em voz alta.
- `mensagemInicial()`: Exibe a mensagem inicial do jogo.
- `verificarChute()`: Verifica se o chute do jogador está correto e fornece dicas se o número secreto é maior ou menor.
- `limparCampo()`: Limpa o campo de entrada do chute.
- `reiniciarJogo()`: Reinicia o jogo, gerando um novo número secreto e resetando as tentativas.

## Como Jogar

1. Abra o arquivo [`js-curso-2-aula_2/index.html`](js-curso-2-aula_2/index.html) em um navegador web.
2. O jogo exibirá uma mensagem inicial pedindo para você escolher um número entre 1 e 10.
3. Digite um número no campo de entrada e clique no botão "Chutar".
4. O jogo fornecerá dicas se o número secreto é maior ou menor que o seu chute.
5. Continue chutando até acertar o número secreto.
6. Quando você acertar, o jogo exibirá uma mensagem de vitória e o número de tentativas que você levou para acertar.
7. Clique no botão "Novo jogo" para reiniciar o jogo e tentar novamente.

## Exemplo de Jogo

1. Mensagem inicial: "Escolha um número entre 1 e 10".
2. Jogador chuta o número 5.
3. O jogo responde: "O número secreto é maior que o chute!".
4. Jogador chuta o número 8.
5. O jogo responde: "O número secreto é menor que o chute!".
6. Jogador chuta o número 7.
7. O jogo responde: "Você acertou! Você descobriu o número secreto com 3 tentativas restantes!".
8. Jogador clica no botão "Novo jogo" para reiniciar.

Divirta-se jogando o Jogo do Número Secreto!
