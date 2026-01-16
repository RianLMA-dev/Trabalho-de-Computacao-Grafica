# Zelda 3D – Projeto de Computação Gráfica

Este projeto consiste no desenvolvimento de um jogo 3D inspirado na franquia Zelda, implementado integralmente em Python, como trabalho acadêmico da disciplina de Computação Gráfica.

O objetivo do projeto é aplicar, de forma prática, os conceitos fundamentais de computação gráfica, utilizando OpenGL em baixo nível, sem o uso de engines prontas, permitindo a compreensão completa do pipeline de renderização 3D.

---

## Descrição Geral

O sistema simula um ambiente tridimensional no estilo Zelda, permitindo ao jogador controlar um personagem em um cenário 3D composto por plataformas, rampas e inimigos.

O projeto foi desenvolvido de forma modular, separando claramente a lógica do jogo, a engine gráfica e o sistema de renderização, facilitando a compreensão, manutenção e evolução do código.

---

## Conceitos de Computação Gráfica Aplicados

Os principais conceitos abordados neste projeto incluem:

- Pipeline de renderização 3D  
- Sistemas de coordenadas (mundo, câmera e tela)  
- Transformações geométricas (translação, escala e rotação)  
- Projeção perspectiva  
- Câmera 3D (LookAt)  
- Shaders programáveis (GLSL)  
- Renderização de objetos 3D  
- Organização da cena  
- Detecção básica de colisão  
- Movimentação e animação em tempo real  

---

## Tecnologias Utilizadas

- Python 3  
- PyOpenGL  
- GLFW  
- NumPy  
- OpenGL (GLSL)  

---

## Estrutura de Pastas

```text
src/
├── assets/
│   └── shaders/
│       ├── basic.vert
│       └── basic.frag
│
├── core/
│   ├── renderizador.py
│   └── shaders.py
│
├── engine/
│   ├── transformacoes.py
│   ├── geometrias.py
│   └── colisao.py
│
├── game/
│   ├── jogador.py
│   ├── inimigo.py
│   ├── plataforma.py
│   └── rampa.py
│
└── main.py
