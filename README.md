# Bem-vindo(a) ao repositório do Space Runner!

Space Runner é um jogo espacial emocionante onde o jogador assume o controle de uma nave em um ambiente repleto de obstáculos perigosos. O objetivo é destruir o máximo possível de obstáculos e sobreviver pelo maior tempo possível, pontuando tanto pelas destruições quanto pela duração da sobrevivência.

O jogador deve manobrar a nave para desviar dos obstáculos, movendo-se para a direita ou para a esquerda, enquanto tenta manter a nave intacta. A qualquer momento, uma colisão com um obstáculo fará com que o jogador perca o jogo.

---

# Instruções de Compilação

O jogo foi desenvolvido utilizando o sistema operacional Linux (Ubuntu). Ele também é compatível com macOS, porém as instruções abaixo contemplam apenas a compilação para o Linux.

## Pré-requisitos

Certifique-se de que as ferramentas abaixo estejam instaladas no seu sistema:

### 1. GCC (GNU Compiler Collection)

O GCC é necessário para compilar o jogo. Para instalá-lo no Ubuntu, execute:

```bash
sudo apt update
sudo apt install build-essential
```

### 2. Git

O Git é necessário para clonar o repositório do jogo. Para instalá-lo no Ubuntu, execute:

```bash
sudo apt update
sudo apt install git
```

---

## Rodando a Aplicação

1. Clone o repositório:

```bash
git clone https://github.com/pedroguswander/jogo_pif.git
```

2. No terminal, acesse a pasta raiz do projeto (GAME_PIF):

```bash
cd GAME_PIF
```

3. Compile o jogo:

```bash
gcc ./src/*.c -I./include -o game
```

4. Execute o jogo:

```bash
./game
```

---

# Equipe

- **Felipe Rêgo**
- **Fernando Cavalcanti**
- **Pedro Gusmão**

---

Sinta-se à vontade para contribuir ou relatar problemas na seção de Issues! Divirta-se jogando Space Runner! 🚀
