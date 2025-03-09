Controle de Drone com Rastreamento Ocular

Este projeto implementa um simulador de controle de drone baseado no rastreamento ocular utilizando OpenCV e MediaPipe. O usuário controla o movimento do drone apenas com o olhar, sem a necessidade de controles físicos.

Como Funciona

1. Captura de Vídeo
O código utiliza a webcam para capturar imagens em tempo real e processá-las.


2. Detecção Facial e Rastreamento Ocular
Com a biblioteca MediaPipe Face Mesh, ele identifica pontos-chave no rosto, focando nos olhos para determinar a direção do olhar.


3. Calibração
Antes de iniciar, o usuário deve calibrar o sistema pressionando a tecla 'g' enquanto olha para o centro da tela. Isso compensa diferenças individuais no rastreamento.


4. Movimento do Drone

Para cima: Olhar para cima

Para baixo: Olhar para baixo

Para a esquerda: Olhar para a esquerda

Para a direita: Olhar para a direita

Parado: Olhar para o centro



5. Simulação Gráfica
O drone é desenhado em uma interface gráfica que simula um ambiente 3D com fundo gradiente e grid para um efeito de profundidade. Ele possui corpo central, braços, hélices animadas e LEDs.


6. Indicadores HUD
Uma interface exibe informações como velocidade, inclinação e estado da calibração.


7. Encerramento
Para sair, basta pressionar a tecla ESC.



Este projeto pode ser expandido para integração com drones reais ou outras aplicações de acessibilidade baseadas em rastreamento ocular.

