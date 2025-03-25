# 🚁 Controle de Drone com Rastreamento Ocular

Este projeto traz uma abordagem inovadora para o controle de drones, utilizando **rastreio ocular**! Com a ajuda do **OpenCV** e do **MediaPipe**, o usuário pode pilotar um drone **apenas com o olhar**, sem necessidade de controles físicos. 👀✨

---

## 🎯 Como Funciona?

1️⃣ **📷 Captura de Vídeo**
   - A webcam captura imagens em tempo real para análise do movimento dos olhos.

2️⃣ **🤖 Detecção Facial e Rastreamento Ocular**
   - Através do **MediaPipe Face Mesh**, o código identifica pontos-chave do rosto, focando nos olhos para determinar a direção do olhar.

3️⃣ **🎯 Calibração Inteligente**
   - Antes de iniciar, o usuário pressiona a tecla **'G'** enquanto olha para o centro da tela para calibrar o sistema e compensar variações individuais.

4️⃣ **🚀 Controle do Drone**
   - **Olhar para cima** ⬆️ → Drone sobe
   - **Olhar para baixo** ⬇️ → Drone desce
   - **Olhar para a esquerda** ⬅️ → Drone vira para a esquerda
   - **Olhar para a direita** ➡️ → Drone vira para a direita
   - **Olhar para o centro** 🔵 → Drone permanece parado

5️⃣ **🖥️ Simulação Gráfica Interativa**
   - O sistema exibe uma interface visual 3D com um drone animado, incluindo fundo gradiente e um grid que cria um efeito de profundidade. 🌐

6️⃣ **📊 Indicadores HUD**
   - A interface exibe dados como velocidade, inclinação e status da calibração, permitindo um monitoramento em tempo real. 🎛️

7️⃣ **🔚 Encerramento**
   - Para sair do programa, basta pressionar a tecla **ESC**. 🏁

---

## 🚀 Expansões Futuras

🔹 **Integração com drones reais** 🚁, possibilitando controle físico através do rastreamento ocular.

🔹 **Aprimoramento do algoritmo de rastreamento** 👁️, utilizando redes neurais para maior precisão.

🔹 **Aplicações em acessibilidade** ♿, permitindo que pessoas com mobilidade reduzida controlem dispositivos com os olhos.

---

## 📜 Licença
Este projeto é de código aberto e está licenciado sob a **MIT License**. Sinta-se à vontade para explorar, modificar e aprimorar! 🎉

