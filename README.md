# 🎾 TênisFun

Projeto desenvolvido para a disciplina de :contentReference[oaicite:0]{index=0} utilizando Python e :contentReference[oaicite:1]{index=1}.

O jogo simula uma partida de tênis em primeira pessoa com câmera fixa e elementos em Pixel Art, aplicando conceitos de transformações geométricas estudados em sala de aula.

---

# 📚 Objetivo da Atividade

Desenvolver um jogo digital interativo aplicando, na prática, os seguintes conceitos de computação gráfica:

- Translação
- Rotação
- Escala
- Reflexão (flip/espelhamento)

O projeto foi desenvolvido utilizando:

- Python 3.11.9
- Pygame 2.6.1
- PyCharm Community 2025.2

---

# 🕹️ Sobre o Jogo

No jogo **TênisFun**, o jogador controla um atleta de tênis visto de costas para a câmera.

A bola é lançada pelo adversário e o jogador deve mover-se rapidamente para o lado correto da quadra utilizando o teclado para rebater a bola.

A cada acerto:
- a velocidade aumenta;
- o tempo de reação diminui;
- a dificuldade cresce progressivamente.

O objetivo é sobreviver às 10 rodadas sem errar.

---

# 🎮 Controles

| Tecla | Função |
|---|---|
| ← | Move o jogador para esquerda |
| → | Move o jogador para direita |

---

# 🧠 Conceitos de Computação Gráfica Aplicados

## ✅ Translação

Movimentação do jogador e da bola na tela.

Exemplo:

```python
self.x += self.speed
self.y += self.speed_y
