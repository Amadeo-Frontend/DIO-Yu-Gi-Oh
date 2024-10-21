#  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Video%20Game.png" alt="Video Game" width="35" height="35" /> Yu-Gi-Oh Jo-Ken-Po Edition

Bem-vindo ao **Yu-Gi-Oh Jo-Ken-Po Edition**! Este jogo interativo combina a famosa mecânica de Jo-Ken-Po (Pedra, Papel e Tesoura) com personagens e cartas icônicas do universo de Yu-Gi-Oh. Prepare-se para testar suas habilidades estratégicas e desafiar o computador em emocionantes duelos!

## 🌟 Descrição do Projeto 

Neste projeto, os jogadores têm a oportunidade de escolher entre cartas icônicas do universo Yu-Gi-Oh, cada uma com suas características únicas. O objetivo é vencer o computador em um duelo, utilizando a lógica do jogo de Jo-Ken-Po, onde cada carta representa um tipo de movimento (Pedra, Papel ou Tesoura). O jogo não só é divertido, mas também ensina aos jogadores a importância da estratégia ao selecionar suas cartas.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura do jogo.
- **CSS3**: Estilização e animações.
- **JavaScript**: Lógica do jogo, manipulação do DOM e gerenciamento de áudio.

### 🔍 Como Funciona 

- **Escolha de Cartas**: O jogador inicia o jogo selecionando uma carta de seu baralho. As cartas disponíveis incluem:
  - **Blue Eyes White Dragon** (Paper)
  - **Dark Magician** (Rock)
  - **Exodia** (Scissors)

- **Resultados do Duelo**: Após a seleção, o computador também escolhe aleatoriamente uma carta. O resultado do duelo é determinado com base nas regras de Jo-Ken-Po:
  - Papel vence Pedra
  - Pedra vence Tesoura
  - Tesoura vence Papel

- **Atualização de Pontuação**: A pontuação do jogador e do computador é atualizada em tempo real, mostrando quem está ganhando a partida.

## 🚀 Recursos 

- **Interação em Tempo Real**: Os jogadores podem interagir com as cartas, passando o mouse sobre elas para visualizar detalhes, e clicando para selecionar sua jogada.
- **Feedback Visual e Sonoro**: Cada resultado do duelo é acompanhado de feedback visual e sonoro, aumentando a imersão e a emoção do jogo.


### 📝 Principais Componentes

1. **Gerenciamento de Estado**: O objeto `state` mantém todas as informações do jogo, como pontuação, cartas selecionadas e elementos da interface do usuário.

2. **Lógica de Duelos**:
   - A função `checkDuelResults` determina o resultado do duelo com base nas cartas selecionadas. Dependendo da escolha do jogador e da carta do computador, ela atualiza a pontuação e reproduz o áudio correspondente.
   - A função `playAudio` gerencia a reprodução de sons, garantindo que o áudio atual seja tocado sem sobreposição.

3. **Manipulação do DOM**: Funções como `drawCards` e `removeAllCardsImages` manipulam o DOM para exibir as cartas na tela e atualizar a interface em tempo real.

4. **Interatividade do Usuário**: O uso de eventos, como `click` e `mouseover`, proporciona uma experiência interativa, permitindo que os jogadores interajam com as cartas e recebam feedback instantâneo.

## 🤝 Contribuições

Contribuições são bem-vindas! Se você encontrar um bug, tiver uma sugestão de melhoria ou quiser adicionar uma nova funcionalidade, sinta-se à vontade para criar um issue ou pull request. Siga estas etapas:

1. Faça um fork do repositório.
2. Crie um novo branch com sua contribuição (`git checkout -b feature/minha-contribuicao`).
3. Faça commit das suas alterações (`git commit -am 'Adiciona minha contribuição'`).
4. Faça push para o branch (`git push origin feature/minha-contribuicao`).
5. Abra um Pull Request.

## ⚙ Suporte

Se você encontrar algum problema ou tiver dúvidas sobre o uso deste projeto, por favor, abra um issue para discussão.

Desenvolvido com <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Sparkling%20Heart.png" alt="Sparkling Heart" width="25" height="25" /> por Amadeo Bon para contribuir com a comunidade. Boa navegação!
