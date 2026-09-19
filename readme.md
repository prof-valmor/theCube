# 🧩 Rubik's Cube 3D (Bevy Engine)

Um emulador interativo de Cubo Mágico 3D construído em Rust utilizando a [Bevy Engine](https://bevyengine.org/). O projeto conta com controles para rotações de camadas, suporte a atalhos de teclado, barra de ferramentas interativa (UI) e um **placar com heurística em tempo real** para calcular o percentual de peças resolvidas.

Compatível com **macOS / Windows / Linux** (Desktop) e **Android**.

---

## ✨ Funcionalidades

- 🎲 **Renderização 3D em Tempo Real:** Iluminação direcional, sombras e controle orbital de câmera via mouse/touch.
- 🧮 **Sistema de Placar (Heurística):** Calcula em tempo real quantas das 27 peças (*cubies*) estão na sua posição correta original, indicando a precisão do cubo (`0%` a `100%`).
- 🔄 **Controles Flexíveis de Rotação:**
  - Botões dedicados na interface gráfica (UI) para girar todas as camadas (`R`, `L`, `U`, `D`, `F`, `B`, `M`, `E`, `S`).
  - Alternador do sentido de rotação (**Horário / Anti-horário**).
  - Suporte a teclas de atalho no teclado.
  - Botão de **Embaralhar** (gera uma sequência aleatória de movimentos).
  - Botão de **Resetar Vista** para retornar a câmera à posição inicial.
- 📱 **Multiplataforma:** Roda nativamente no Desktop e em dispositivos móveis Android.

---

## 🎮 Controles

### Câmera
- **Clique / Toque + Arrastar:** Orbita a câmera ao redor do cubo.

### Teclado
| Tecla | Ação (Camada) | Com `Shift` pressionado |
| :--- | :--- | :--- |
| **R** | Rotacionar *Right* (Direita) | Inverte o sentido |
| **L** | Rotacionar *Left* (Esquerda) | Inverte o sentido |
| **U** | Rotacionar *Up* (Superior) | Inverte o sentido |
| **D** | Rotacionar *Down* (Inferior) | Inverte o sentido |
| **F** | Rotacionar *Front* (Frente) | Inverte o sentido |
| **B** | Rotacionar *Back* (Trás) | Inverte o sentido |
| **M** | Rotacionar *Middle* (Central - Eixo X) | Inverte o sentido |
| **E** | Rotacionar *Equator* (Central - Eixo Y) | Inverte o sentido |
| **S** | Rotacionar *Standing* (Central - Eixo Z) | Inverte o sentido |

---

## 🚀 Como Executar Localmente

### Pré-requisitos
- [Rust](https://www.rust-lang.org/) (versão 1.80+ recomendada).

### 🖥️ No Desktop (macOS / Windows / Linux)

1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/custom_rubiks_cube.git](https://github.com/seu-usuario/custom_rubiks_cube.git)
   cd custom_rubiks_cube
