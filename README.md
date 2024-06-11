# Detecção de Mãos e Desenho em Vídeo com OpenCV e cvzone

Este projeto demonstra como usar a biblioteca OpenCV em conjunto com cvzone para detectar mãos em tempo real a partir da câmera e desenhar com base nos movimentos dos dedos. Quando apenas um dedo está levantado, o script desenha na tela. Quando três dedos estão levantados, o desenho é apagado.

## Requisitos

Antes de executar o script, certifique-se de ter instalado as seguintes bibliotecas Python:

- `opencv-python`
- `cvzone`
- `mediapipe`

Você pode instalar essas bibliotecas usando os seguintes comandos:

```sh
pip install opencv-python cvzone mediapipe --user
```

## Uso

Clone este repositório ou baixe o arquivo `main.py`.

Execute o script `main.py`:

## Funcionamento
Detecção de Mãos: O script usa cvzone para detectar mãos na imagem capturada da câmera.
Desenho: Se apenas um dedo está levantado, o script desenha um ponto na tela. Esses pontos são conectados para formar linhas.
Apagar Desenho: Se três dedos estão levantados, o desenho é apagado.

## Saída
A saída é uma janela de vídeo onde você pode ver as mãos detectadas e o desenho baseado no movimento do dedo.

## Problemas Comuns
Erro ao abrir a câmera: Verifique se a câmera está conectada corretamente e não está sendo usada por outro aplicativo.
Erro ao capturar a imagem: Certifique-se de que os drivers da câmera estão atualizados e que você tem as permissões necessárias para acessar a câmera.
