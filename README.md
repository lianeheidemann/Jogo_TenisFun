<div align="center">

# 🎾 TÊNISFUN

### Jogo 2D em Python com Pygame

Simulação de tênis em perspectiva com foco em **transformações geométricas**

<p>
  <img src="https://github.com/user-attachments/assets/dd2a47f7-1201-4587-9e5c-4b2cf3e454d2" width="750">
</p>

</div>

---

## 📌 Sobre o Projeto

O **TênisFun** é um jogo desenvolvido para a disciplina de Computação Gráfica.

O objetivo é aplicar, na prática, conceitos fundamentais de transformação geométrica em um ambiente interativo usando Python e Pygame.

O jogador controla um atleta de tênis visto de costas e deve rebater bolas lançadas pelo oponente em uma quadra com perspectiva simulada.

---

## 🎯 Objetivo Acadêmico

Este projeto foi desenvolvido com foco em:

- Aplicação prática de **transformações geométricas**
- Desenvolvimento de jogos com gráficos 2D
- Organização modular de código
- Uso de eventos e interação com teclado

---

## 🧠 Transformações Geométricas Implementadas

### 📍 Translação
Movimento dos objetos na tela (jogador e bola):

```python
self.x += self.speed
self.y += self.speed_y
```

---

### 🔄 Rotação
A bola gira em torno do próprio eixo:

```python
pygame.transform.rotate(surface, angle)
```

---

### 📏 Escala
Simulação de profundidade (bola cresce ao se aproximar):

```python
pygame.transform.scale(surface, (w, h))
```

---

### 🔁 Reflexão (Flip)
A raquete muda de lado conforme posição do jogador:

```python
pygame.transform.flip(surface, True, False)
```

---

## 🎮 Gameplay

- A bola é lançada pelo adversário
- O jogador deve se mover para esquerda ou direita
- O objetivo é rebater corretamente por 10 rodadas
- A dificuldade aumenta progressivamente

---

## 🕹️ Controles

| Tecla | Ação |
|------|------|
| ← | Move o jogador para esquerda |
| → | Move o jogador para direita |

---

## 🧱 Estrutura do Projeto

```text
tenis_fun/
│
├── main.py
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
├── scenes/
│   ├── menu_scene.py
│   └── game_scene.py
│
├── ui/
│   └── button.py
```

---

## ⚙️ Tecnologias Utilizadas

- Python 3.11
- Pygame 2.6
- PyCharm Community Edition

---

## 🚀 Como Executar

### 1. Instalar dependência
```bash
pip install pygame
```

### 2. Rodar o jogo
```bash
python main.py
```

---

## 🎥 Demonstração

<p align="center">
  <img src="https://github.com/user-attachments/assets/dd2a47f7-1201-4587-9e5c-4b2cf3e454d2" width="750">
</p>

---

## 👨‍💻 Autor(es)

Projeto acadêmico desenvolvido para a disciplina de Computação Gráfica.

- Nome:
- Matrícula:
- Turma:
- Professor(a):

---

## 📄 Licença

Uso acadêmico / educacional














#
🎾 TênisFun

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

