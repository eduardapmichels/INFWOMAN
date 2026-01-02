# INF WOMAN

Jogo inspirado no **MegaMan**
Feito em **C** utilizando a biblioteca **raylib**.

O jogo possui modo **solo** e **multiplayer**, com diversos inimigos, boss, itens e efeitos sonoros.

---

## Desenvolvedoras

- [eduardapmichels](https://github.com/eduardapmichels)  
- [florisbalmanoella](https://github.com/florisbalmanoella)

---

## Como Jogar

- **Solo:** botão `Start`  
- **Multiplayer:** botão `Multiplayer`  

### Player 1
- `→` : andar para direita  
- `←` : andar para esquerda  
- `↑` : pular  
- `Espaço` : atirar  

### Player 2
- `D` : andar para direita  
- `A` : andar para esquerda  
- `W` : pular  
- `ALT esquerdo` : atirar  

### Função especial
- `Z` : modo "super" (invencível contra espinhos e inimigos)

---

## Regras do Arquivo TXT (mapa do jogo)

- O arquivo **precisa ter 200 linhas e 10 colunas**. Qualquer alteração pode quebrar o jogo.  
- Letras no TXT:

| Letra | Significado |
|-------|------------|
| `B`   | Bloco normal |
| `P`   | Ponto inicial do jogador |
| `M`   | Inimigo |
| `T`   | Boss (apenas no `MAINBOSS.C`) |
| `W`   | Bloco que deixa o personagem lento e sem pulo |
| `I`   | Item estrela (+50 pontos) |

---

## Sons e Música

- Música de fundo: *Lago dos Cisnes* (tocada ao iniciar o jogo)  
- Tiros e itens possuem sons correspondentes  
- **Player 1:** tiro rosa  
- **Player 2:** tiro verde


## Tecnologias Utilizadas

- Linguagem: **C**  
- Biblioteca: [**raylib**](https://www.raylib.com/)

---

## Observações

- Certifique-se de ter a **raylib instalada** antes de compilar.  
- O jogo depende do **formato exato do TXT**, então altere com cuidado.  
- Para ajustes ou melhorias no `MAINBOSS.C`, algumas correções no código podem ser necessárias.
