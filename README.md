
# 🐍 Snake Game Extendido (Raylib + C++)

Este projeto é uma versão estendida do jogo **Snake**, desenvolvida em **C++** utilizando a biblioteca **Raylib**.  
O jogo conta com **duas cobras simultâneas**, **obstáculos dinâmicos**, **sistema de pontuação**, **aumento progressivo de velocidade** e **efeitos sonoros**.

---

##  Funcionalidades

-  Duas cobras controladas automaticamente em direções opostas  
-  Comida (maçã) com reposicionamento automático  
-  Obstáculos gerados dinamicamente durante o jogo  
-  Sistema de pontuação  
-  Aumento de velocidade conforme o score  
-  Efeitos sonoros (comer maçã e *game over*)  
-  Sistema de reinício após *Game Over*

---

## Controles

### Movimento
- ⬆️ **Cima**
- ⬇️ **Baixo**
- ⬅️ **Esquerda**
- ➡️ **Direita**

### Ações
- **ENTER** — Iniciar o jogo  
- **ENTER** — Reiniciar após *Game Over*

> A segunda cobra se movimenta automaticamente na direção oposta à primeira.

---

##  Estrutura de Pastas

```text
📦 Snake-Game
├── 📂 componentes_audio
│   ├── bonus.mp3
│   └── gameover.mp3
│   ├── campus_diminui.mp3
│   ├── come_maca.mp3
│
├── 📂 imagens
│   └── one_apple.png
│   └── maça.png
│   └── two_apple.png
│
├── jogo_completo.cpp
└── README.md


##  Tecnologias Utilizadas: C++, Raylib, Gráficos 2D, Áudio, Entrada de teclado, Sistema de colisões


Vídeo usado como inspiração: https://youtu.be/LGqsnM_WEK4?si=ZCg8DNxqhcSauNVw

























