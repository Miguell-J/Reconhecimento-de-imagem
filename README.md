# Reconhecimento-de-imagem

Este é um projeto simples que utiliza a biblioteca MediaPipe e OpenCV para reconhecimento de mãos em uma transmissão de vídeo da webcam. Ele detecta as landmarks (pontos-chave) da mão e desenha conexões entre esses pontos em tempo real.

<img src="">

Pré-requisitos
Antes de executar este código, certifique-se de ter as seguintes bibliotecas instaladas:

Python 3.x
OpenCV (pip install opencv-python)
MediaPipe (pip install mediapipe)
Como usar
Clone este repositório em sua máquina local ou faça o download do código-fonte.

Abra um terminal na pasta onde o código está localizado.

Execute o código com o seguinte comando:

Copy code
python nome_do_arquivo.py
A webcam será ativada, e você verá uma janela exibindo o feed de vídeo da sua webcam com as mãos detectadas e as landmarks desenhadas.

Pressione a tecla "ESC" para encerrar o programa.

Entendendo o Código
O código começa importando as bibliotecas necessárias, como cv2 (OpenCV) e mediapipe.

Ele inicializa a webcam, configurando uma conexão com o dispositivo de índice 0 (geralmente a webcam padrão).

Inicializa o MediaPipe para detecção de mãos.

Inicia um loop infinito que lê continuamente os quadros da webcam, converte-os para o formato RGB e detecta e desenha as landmarks da mão.

O loop é encerrado quando a tecla "ESC" é pressionada.

Finalmente, a webcam é liberada e todas as janelas abertas são fechadas.
