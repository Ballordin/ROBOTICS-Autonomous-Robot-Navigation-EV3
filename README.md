# Navegacao-Autonoma-EV3

Projeto desenvolvido na unidade curricular de **Robótica (IPCA)**. Consiste num sistema autónomo de navegação para robô móvel, integrando cinemática direta/inversa, planeamento de trajetórias e visão computacional.

## Destaques Técnicos
- **Cinemática:** Controlo de movimento através de modelos de cinemática direta e inversa.
- **Mapeamento:** Conversão de coordenadas de imagem (câmara IP) para o mundo real (metros).
- **Inteligência:** Algoritmos de planeamento de trajetórias para desvio de zonas proibidas.
- **Visão:** Deteção de sinais de trânsito em espaço HSV e correção de erro odométrico.

## Demonstração
[![Assistir ao Vídeo](https://img.shields.io/badge/YouTube-Assistir%20Vídeo-red?style=for-the-badge&logo=youtube)](https://youtu.be/b_EHnqg5K34)

## Arquitetura do Sistema

<img width="868" height="594" alt="image" src="https://github.com/user-attachments/assets/47ebe408-f387-488d-bedd-749f6135ef18" />

## Documentação
O relatório técnico detalhado, contendo a fundamentação matemática (cinemática, matrizes de transformação e campos de custo), está disponível na pasta [`/documents`](./documents).

## Tecnologias
- **Hardware:** Lego Mindstorms EV3
- **Software:** MATLAB (App Designer, Image Acquisition/Processing Toolboxes)
