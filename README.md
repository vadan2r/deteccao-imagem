# deteccao-imagem
Projeto de criação de uma base de dados e treinamento.

Para imagens rotuladas:

![image](https://github.com/user-attachments/assets/898db2d5-e0bd-4c81-8373-70b32e4a7a3a)

Seguindo os exemplos de aula, vamos rotular uma base de dados e aplicar o treinamento com a rede YOLO. 
 
Para essa tarefa será necessário utilizar o software LabelMe: http://labelme.csail.mit.edu/Release3.0/ para rotular as imagens. 
 
Também será necessário utilizar a rede YOLO, disponível em: https://pjreddie.com/darknet/yolo/. 
 
Para quem preferir e não quiser rotular uma base de dados, pode usar as imagens já rotuladas do COCO: https://cocodataset.org/#home. 
 
E para quem estiver utilizando um computador que não consiga rodar a rede YOLO, pode utilizar o transfer learning no COLAB:

https://colab.research.google.com/drive/1lTGZsfMaGUpBG4inDIQwIJVW476ibXk_#scrollTo=j0t221djS1Gk. 
 
O trabalho deve conter pelo menos duas classes retreinadas para detecção, além das classes já treinadas previamente antes de realizar o transfer learning.  
 
Por meio da imagem é possível visualizar um exemplo de resultado esperado: 

![image](https://github.com/user-attachments/assets/44340db4-01ad-4c1f-b79f-f1b79f4f0e1f)

Figura 1: Detecção em imagens com a rede YOLO. 
