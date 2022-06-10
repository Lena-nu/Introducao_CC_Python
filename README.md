# 🔥Introducao_CC_Python 🔥
❕Conversão de imagem RGB em imagem Grayscale❕

<sub>💻O que o algoritmo faz?</sub>
  O algoritmo pega uma imagem colorida selecionada pelo usuário e após isso transforma ela em tons de cinza, em que um único pixel irá representar a quantidade de luz ou irá conter as informações sobre a intensidade da luz, sendo por fim uma imagem unidimensional e com isso irá possuir diferentes tons de cinza apenas, fazendo parecer uma imagem preto e branco, ajustando  certas cores principais que o nosso o olho vê, azul, vermelho e verde, deixando cada um com uma certa intensidade e transformando ela em uma imagem de tons cinza nítida.   
  
<sub> 💻Pra que ele é usado?</sub>
 Vemos que as imagens de tons de cinza são muito mais fáceis de serem trabalhadas em uma grande variedade de tarefas. Como muitos problemas de segmentação de imagens, onde é extremamente mais fácil trabalhar com uma única camada de cor, sendo ela de tons cinza do que uma colorida. É possível também citar que utilizamos esse código sem sequer saber, afinal ele é bastante utilizado para imprimir imagens de tons cinza, já que a grande maioria das pessoas preferem ou utilizam somente a cor preta da impressora. 

<sub>💻Uma breve explicação de como ele está implementado no Python</sub>
  Usando o módulo cv2, irá disponibilizar as ferramentas necessárias. Para fazer o uso da imagem original é necessário usar a função imread do módulo cv2, tendo os canais de armazenamento da ordem RGB.
  Para a exibição da imagem, chama-se a função imshow também do módulo cv2.
	A com a função waitKey, irá aguardar um comando do teclado, recebendo como entrada um atraso, porém no código é definido o valor 0, aguardado indefinidamente até que o comando seja acionado. 
  No final chamando a função destroyAllWindows, no qual irá destruir as janelas criadas anteriormente. 

