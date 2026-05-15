# 🎾 TênisFun

Projeto desenvolvido para a disciplina de Computação Gráfica utilizando Python e Pygame.

O jogo simula uma partida de tênis em primeira pessoa com câmera fixa e elementos em Pixel Art, aplicando conceitos de transformações geométricas estudados em sala de aula.

---

# 🎮 Gameplay

## Demonstração do jogo

<p align="center">
  <img
    width="800"
    alt="TênisFun"
    src="https://github.com/user-attachments/assets/dd2a47f7-1201-4587-9e5c-4b2cf3e454d2"
  />
</p>

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
```

---

## ✅ Rotação

A bola gira no próprio eixo utilizando:

```python
pygame.transform.rotate()
```

---

## ✅ Escala

A bola aumenta de tamanho conforme se aproxima do jogador, simulando profundidade.

```python
pygame.transform.scale()
```

---

## ✅ Reflexão (Flip)

A raquete muda de lado utilizando espelhamento horizontal:

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
└── scenes/
    ├── menu_scene.py
    └── game_scene.py
```

---

# 📂 Organização dos Arquivos

| Arquivo | Responsabilidade |
|---|---|
| `main.py` | Loop principal do jogo |
| `config.py` | Configurações e cores |
| `court.py` | Renderização da quadra |
| `player.py` | Jogadores e raquete |
| `ball.py` | Física, rotação e escala da bola |
| `menu_scene.py` | Tela inicial |
| `game_scene.py` | Controle da gameplay |

---

# 🚀 Como Executar

## 1. Instalar dependências

```bash
pip install pygame
```

---

## 2. Executar o jogo

Dentro da pasta do projeto:

```bash
python main.py
```

ou:

```bash
python tenis_fun/main.py
```

---

# 🖼️ Características Visuais

- Pixel Art
- Quadra em perspectiva
- Simulação de profundidade
- Bola com rotação
- Escalonamento da bola
- Interface simples e objetiva

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pygame
- PyCharm Community

