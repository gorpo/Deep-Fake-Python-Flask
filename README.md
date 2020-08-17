
[![Build](https://img.shields.io/badge/dev-gorpo-brightgreen.svg)]()
[![Stage](https://img.shields.io/badge/Release-Stable-brightgreen.svg)]()
[![Build](https://img.shields.io/badge/python-v3.7-blue.svg)]()
[![Build](https://img.shields.io/badge/windows-7%208%2010-blue.svg)]()
[![Build](https://img.shields.io/badge/Linux-Ubuntu%20Debian-orange.svg)]()
[![Build](https://img.shields.io/badge/arquiterura-64bits-blue.svg)]()<br>
  <h6 align="center">
   <img src="https://raw.githubusercontent.com/gorpo/Manicomio-Boot-Theme/master/manicomio/boot.png" width="55%"></img>
       <h2 align="center">Manicomio | Python Deep Fake Flask| Deep Learning</h2>
  </h6>
<h3 align="center"> Programa de manipulação de imagens com OpenCV, Torch, Torchvision, Numpy e Pillow.</h3><br>
<img src="https://raw.githubusercontent.com/gorpo/Deep-Fake-Python-Flask/master/images/example2.jpg" width="100%"></img>

<p>Sistema de manipulação de imagem que cria imagens *** seguindo um padrão especifico, pois faz a leitura e treinamento com arquivos .lib, os quais devem ser feitos o download e inseridos posteriormente na pasta /checkpoints.</p>

# Requisitos:
- Python3.7 (não testado em outros)
- OpenCV
- Torch
- Torchvision
- Numpy
- Pyllow
- Flask
- outras lib's ver arquivos ou logs de erro


self.gpu_ids = [0] #FIX CPU
self.gpu_ids = [] #FIX CPU

# Instalações previas das libs que cumprem os requisitos para windows10:
--> Torch:<br>
<code>pip install https://download.pytorch.org/whl/cu90/torch-1.1.0-cp37-cp37m-win_amd64.whl</code>
-->Torchvision<br>
<code>pip install https://download.pytorch.org/whl/cu90/torchvision-0.3.0-cp37-cp37m-win_amd64.whl </code>
--> Pillow<br>
<code>pip install Pillow==6.1</code>
--> OpenCV<br>
<code>pip install opencv-python</code>
--> Numpy<br>
<code>pip install numpy</code>

# Lib's adicionais e obrigatórias:
<p> Precisamos adicionar os arquivos cm.lib, mm.lib e mn.lib dentro da pasta "/checkpoints", para isto basta fazer o download abaixo de cada uma delas, ou caso contrario o script não irá rodar e irá apresentar o seguinte erro:</p>
---> Iremos ter o erro:<br>
<code>FileNotFoundError: [Errno 2] No such file or directory: 'checkpoints/cm.lib'
libpng warning: iCCP: known incorrect sRGB profile</code>
--correção:<br>
	--> criar a pasta e por os arquivos nela:<br>
<code> CM lib>> https://drive.google.com/file/d/1wNo3Rjd_F4I8kh25HZ0rfnfRcBy5wept/view
MM lib>> https://drive.google.com/file/d/15fylXbJYqXbmfKoo-KX2SpvYGtlMcITE/view
Mn lib>> https://drive.google.com/file/d/1VWwc8TQcPgUlE_MVZm0je1xn3MeCiuJ_/view</code>

# Executando:
<p> Basta executar o servidor flask e seguir os processos no endereço fornecido.</p>

  
# Tempo de execução:
  <p> O tempo de execução de todo processo e qualidade varia de maquina para maquina, este script usa duas formas para fazer seue processo, ou uso da Memoria Ram ou uso da GPU. Para acelerar o processo aconselho uso de GPU porém ira se comportar tranquilamente com uso da memoria ram, para mudar o uso de GPU e Memoria ram basta mudar a linha 


