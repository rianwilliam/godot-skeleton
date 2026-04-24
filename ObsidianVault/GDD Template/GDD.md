# GDD - [Nome do Jogo]

**Versão:** 1.0 
**Data:** 23/04/2026  
**Motor:** Godot Engine 4.x  
**Gênero:** [Ex: Plataforma / Top-down Shooter / Metroidvania]

---

## 1. Visão Geral do Jogo
### 1.1. O Conceito (Elevator Pitch)
*Uma frase que descreve o jogo de forma impactante.*
> Ex: Um plataforma de precisão onde você controla a gravidade para resolver puzzles em um mundo de neon.

### 1.2. Pilares de Design
* **Pilar 1:** [Ex: Movimentação fluida]
* **Pilar 2:** [Ex: Dificuldade progressiva]
* **Pilar 3:** [Ex: Atmosfera melancólica]

### 1.3. Público-Alvo e Plataformas
* **Plataformas:** PC (Windows/Linux), Web.
* **Público:** [Ex: Jogadores casuais que gostam de puzzles].

---

## 2. Mecânicas (Gameplay)
### 2.1. Movimentação do Personagem
* **Caminhar:** Velocidade X, aceleração Y.
* **Pulo:** Altura fixa ou variável? Coyote time? Jump buffer?
* **Habilidade Especial:** [Ex: Dash, Tiro, Gancho].

### 2.2. Core Loop
1. [Ação Primária: Ex: Explorar a sala]
2. [Desafio: Ex: Desviar de espinhos e coletar chaves]
3. [Recompensa: Ex: Abrir o portão para a próxima fase]

### 2.3. Sistema de Combate / Interação
* Como o jogador interage com o mundo?
* Sistema de vida (Corações? Barra de HP? One-hit-kill?).

---

## 3. Direção de Arte (2D)
### 3.1. Estilo Visual
* **Tipo:** [Ex: Pixel Art / Desenho à mão / Vetorial].
* **Resolução de Tela:** [Ex: 640x360 (base para 16:9 pixel-perfect)].
* **Paleta de Cores:** [Link para imagem ou descrição das cores principais].

### 3.2. Assets Necessários
- [ ] Sprites do Jogador (Idle, Run, Jump, Death).
- [ ] Tilesets (Chão, Paredes, Fundo).
- [ ] Efeitos de Partícula (Poeira ao pular, faíscas).

---

## 4. Áudio e Música
### 4.1. Atmosfera Sonora
* Descrição do sentimento que a música deve passar.

### 4.2. Estrutura de Bus (Godot)
*Configuração do `audio/bus/default_bus_layout.tres`:*
* **Master:** Controle geral.
* **Music:** Música ambiente com compressor.
* **SFX:** Efeitos sonoros.
* **UI:** Cliques e navegação.

---

## 5. Mundo e Narrativa
### 5.1. História
*Breve resumo do enredo.*

### 5.2. Progressão de Fases
1. **Tutorial:** Apresenta o movimento básico.
2. **Floresta:** Introduz inimigos simples.
3. **Caverna:** Introduz a mecânica de luz.

---

## 6. Interface (UI/UX)
* **Menu Principal:** Jogar, Opções, Sair.
* **HUD:** Contador de moedas e barra de vida no canto superior esquerdo.
* **Telas de Transição:** Fade black entre fases.

---
