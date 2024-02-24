# game-ember-quest

## Descrição

Game 2D no estilo "Mario Bross" desenvolvido em flutter 3.16.2, utilizando a lib [Flame](https://docs.flame-engine.org/latest/) seguindo o [tutorial](https://docs.flame-engine.org/latest/tutorials/platformer/platformer.html#ember-quest-game-tutorial).

[VERSÃO DE TESTE PARA WINDOWS](https://firebasestorage.googleapis.com/v0/b/mywebsite-ca4bd.appspot.com/o/game_amber_quest.rar?alt=media&token=9d3b1975-4833-4693-824b-af35387f77d0)
Basta descompactar com o WinRAR ou WinZip e executar o arquivo "game_rpg.exe".

## Requisitos

### Funcionais
- RF001: movimentar o personagem para direita e esquerda.
- RF002: saltar com o personagem.
- RF003: gerar "Game Over".
- RF004: exibir quantidade de itens coletados.
- RF005: exibir quantidade de vidas.
- RF006: iniciar game.

### Não Funcionais
- RNF001: suporte às plataformas Windows e Web.
- RNF002: personagem deve se mover para a direita usando a tecla (D) ou a seta da direita do teclado.
- RNF003: personagem deve se mover para a esquerda usando a tecla (A) ou a seta da esquerda do teclado.
- RNF004: personagem deve usar a tecla SPACE do teclado.
- RNF005: O cenário de ser um scroll infinito na horizontal com obstáculos e inimigos posicionados de forma aleatória.
- RNF006: O objetivo do game deve ser a coleta de "Stars" à medida que o personagem avança pelo cenário.
- RNF007: O personagem deve iniciar o game com 3 vidas, ao colidir um inimigo, uma vida deve ser subtraída, se o total de vidas for 0 (zero), o jogo deve dar game over.
- RNF0083: ao cair em um espaço vazio, o game deve dar game over.

## Recursos Necessários

Para executar a aplicação localmente, você vai precisar:

- [JDK DO FLUTTR NA VERSÃO 3.16.2](https://flutter-ko.dev/development/tools/sdk/releases)
  
## Rodando a aplicação localmente

- Clone o projeto para sua máquina.
- Importe para a sua IDE.
- Faça o download das dependências.
- No terminal da sua IDE na pasta raiz do projeto, para rodar no Windows, use.
- 
  ```shell
    flutter run -d windows 
   ```
  e para web use
  ```shell
    flutter run -d web-server --web-hostname=127.0.0.1 --web-port=8080
  ```
  o game vai estar disponível em http://localhot:8080

## Deploy da aplicação

Para efetuar o deploy é bem simples.
- Para Windows, use o comando abaixo, após finalizar o Build, vá até a pasta "build\windows\x64\runner\Release" dentro da pasta da raiz do projeto e execute o arquivo game_rpg.exe
  ```shell
  flutter build windows
  ```

- Para Web use o comando a baixo, após finalizar o Build a até a pasta "build\web", dentro dela contem tudo necessário para rodar o game em um servidor web.
  ```shell
  flutter build web
  ```

## Copyright

Desenvolvido por [André Ramos](https://andrefsramos.tech/) | [Linkedin](https://www.linkedin.com/in/andrefsramos-tech/).
