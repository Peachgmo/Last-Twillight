# 🌟 Last Twilight

Um jogo de aventura e plataforma atmosférico em 2D, desenvolvido na engine **Godot 4.3**. Acompanhe uma jornada melancólica, silenciosa e perigosa por um mundo consumido pela escuridão.

---

## 📖 Sinopse

Em um mundo onde o crepúsculo final ameaça apagar toda a existência, você controla uma **Alma de Luz**. Sua missão é cruzar cenários hostis, pesados e corrompidos pelas trevas para reencontrar seu irmão perdido: a **Alma da Lua**. Sem armas ou poderes de ataque, sua única defesa é o seu próprio brilho em meio ao vazio opressor.

---

## 👁️ Atmosfera e Estilo Visual

*   **Ambiente Pesado e Opressivo:** Cenários escuros com forte contraste de iluminação (claro-escuro), transmitindo solidão e perigo iminente.
*   **Narrativa Visual:** A história é contada de forma minimalista através do cenário, ruínas antigas e o contraste entre o brilho da alma e o breu do mundo.
*   **Iluminação Dinâmica:** A própria Alma de Luz serve como a única fonte de claridade do jogador, revelando caminhos ocultos, plataformas invisíveis e perigos escondidos na escuridão.

---

## 🌟 Mecânicas Principais

*   **Luz Essencial:** A energia da Alma de Luz diminui lentamente em áreas corrompidas. O jogador deve encontrar focos de energia ou cristais estelares para não se apagar por completo.
*   **Plataforma de Precisão e Fragilidade:** Pulos calculados e levitação temporária em um mundo cheio de ruínas desmoronando, espinhos sombrios e abismos sem fim.
*   **Pura Esquiva:** Criaturas feitas de sombra patrulham o caminho. O protagonista é totalmente vulnerável e não possui nenhuma mecânica de combate ou defesa direta; o foco total está em desviar, cronometrar movimentos e fugir das ameaças.
*   **Quebra-cabeças Ambientais:** Ative altares antigos posicionando-se sobre eles para guiar a luz e abrir portais para as próximas áreas.

---

## 🛠️ Tecnologias Utilizadas

*   **Engine:** [Godot 4.3](https://godotengine.org) (Versão Standard).
*   **Linguagem:** GDScript.
*   **Iluminação 2D:** Uso intensivo de `PointLight2D` atrelado ao jogador e `LightOccluder2D` nos cenários para criar sombras dinâmicas que afetam a visibilidade do caminho.
*   **Efeitos Visuais:** Sistema de partículas (`GPUParticles2D`) para o rastro de fagulhas que a alma deixa ao se movimentar.

---

## 📦 Como Executar o Projeto

### Pré-requisitos
Você precisará do **Godot Engine 4.3** instalado em sua máquina.

### Passo a Passo
1. Clone este repositório:
   ```bash
   git clone https://github.com
   ```
2. Abra o **Godot Engine 4.3**.
3. Clique em **Importar** (Import) e selecione o arquivo `project.godot` na pasta raiz do projeto.
4. Clique em **Editar** (Edit) para abrir o projeto no editor.
5. Pressione `F5` para iniciar o jogo.

---

## 🎮 Controles Padrão

*   `Setas / A-D`: Movimentar para a esquerda e direita.
*   `Espaço / W`: Pular / Segurar para flutuar e planar brevemente.

---

## 📝 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
