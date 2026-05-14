# 🎾 TênisFun

Projeto desenvolvido para a disciplina de Computação Grafica utilizando Python e pygame.

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

# 🎮 Gameplay

## Demonstração do jogo

![Gameplay do jogo](assets/gameplay.gif)

Vídeo completo:
https://www.youtube.com/watch?v=SEU_VIDEO

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
```

---

## ✅ Rotação

Rotação da bola utilizando:

```python
pygame.transform.rotate()
```

---

## ✅ Escala

Aumento de tamanho da bola simulando profundidade:

```python
pygame.transform.scale()
```

---

## ✅ Reflexão (Flip)

Espelhamento horizontal da raquete:

```python
pygame.transform.flip()
```

---

# 🏗️ Estrutura do Projeto

```text
tenis_fun/
│
├── main.py
│
├── core/
│   └── config.py
│
├── graphics/
│   └── court.py
│
├── sprites/
│   ├── player.py
│   └── ball.py
│
├── ui/
│   └── button.py
│
└── scenes/
    ├── menu_scene.py
    └── game_scene.py
```

---

# 🚀 Como Executar

Instale o pygame:

```bash
pip install pygame
```

Execute o jogo:

```bash
python main.py
```

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pygame
- PyCharm Community

---

# 👨‍💻 Autor(es)

Projeto desenvolvido para a disciplina de Computação Gráfica.

Adicionar:
- Nome dos integrantes
- Matrícula
- Turma
- Nome da professora

<img width="800" height="462" alt="TênisFun" src="https://github.com/user-attachments/assets/dd2a47f7-1201-4587-9e5c-4b2cf3e454d2" />?]
