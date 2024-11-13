# 🛩️ Resgate na Ilha - Jogo de Terminal em C++

##  Sobre o Projeto
Este projeto foi desenvolvido como parte da disciplina de Programação Orientada a Objetos (POO). É um jogo simples, executado no terminal, onde o jogador controla um helicóptero com o objetivo de resgatar pessoas em uma ilha.

###  Objetivo do Jogo
Pilote o helicóptero e resgate o maior número de pessoas possível enquanto enfrenta os desafios apresentados durante a missão. A estratégia e o controle eficiente do helicóptero são fundamentais para o sucesso da operação de resgate.

##  Tecnologias Utilizadas
- **C++**: Linguagem de programação utilizada para o desenvolvimento do jogo.
- **Programação Orientada a Objetos**: Estruturação do código com classes e objetos para uma melhor organização e reutilização de código.

##  Estrutura do Projeto
- **`main.cpp`**: Arquivo principal que executa o jogo.
- **`app.cpp` e `app.h`**: Gerenciamento das funcionalidades principais da aplicação.
- **`fase.cpp` e `fase.h`**: Implementação e definição das fases do jogo.
- **`game_base.h`**: Definição da base de lógica do jogo.
- **`helicopter.h`**: Código relacionado à movimentação e controle do helicóptero.
- **`person.h`**: Implementação das pessoas a serem resgatadas.
- **`rescue_base.h`**: Código referente à base de resgate.
- **`sprite.cpp` e `sprite.h`**: Manipulação de sprites para simular gráficos no terminal.
- **`sprite_animado.cpp` e `sprite_animado.h`**: Implementação de sprites animados para uma experiência visual aprimorada.
- **`sprite_base.h`**: Estrutura básica dos sprites.

##  Como Executar
1. Certifique-se de ter um compilador C++ (como `g++`) instalado em seu sistema.
2. Compile o projeto usando o seguinte comando no terminal:
   ```bash
   g++ main.cpp app.cpp fase.cpp objeto_jogo.cpp sprite.cpp sprite_animado.cpp -o jogo
   ```
3. Execute o jogo com:
   ```bash
   ./jogo
   ```

##  Notas
Este jogo foi projetado para ser executado no terminal, portanto, não possui interface gráfica além dos elementos textuais. A jogabilidade envolve comandos básicos de controle do helicóptero e uma simulação de resgate.
