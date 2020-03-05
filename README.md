# A3_RoboticaComputacional

<h2>Informações Gerais</h2>

<h3>Engenharia de Computação Insper - Robótica Computacional 2020.1</h3>

<h3>Alunos:</h3>
<ul>
  <li><a href=https://www.linkedin.com/in/enrico-damiani-125527196/>Enrico Francesco Damiani</a></li>
  <li><a href=https://www.linkedin.com/in/marcosvinis28/>Marcos Vinícius da Silva</a></li>
</ul>

<h3>Professor:</h3> 
<ul>
  <li><a href=https://www.linkedin.com/in/fabiodemiranda/>Me. Fabio Roberto de Miranda</a></li>
</ul>
<h2>Informações da Atividade</h2>

<h3>Parte 1 - Ponto de Fuga</h3>
<p>
Robôs que trabalham dentro de prédios precisam saber seguir corredores. Uma das maneiras de fazer isso é o robô alinhar o centro de sua câmera ao ponto de fuga do corredor, para que sua trajetória seja aproximadamente paralela às paredes do mesmo. O ponto de fuga é aquele para o qual as retas paralelas parecem convergir.
</p>

<h3>Parte 2 - Executar dois exemplos</h3>
<p>
Há três exemplos: mobilenet_detection, yolov3_detection e tracking. Os dois primeiros são reconhecedores de objetos, e o último é de rastreamento. Um dos arquivos abaixo precisa ser baixado e salvo nas pasta yolov3_detection/yolov3-coco.
https://www.dropbox.com/s/013ogt2bhwfzxwb/yolov3.weights?dl=0 ou https://pjreddie.com/media/files/yolov3.weights

Atenção: Vamos rodar a Yolo só por importância "histórica". Depois de rodar o demos, estude o notebook Demo_Imagenet.ipynb
</p>

<h3>Parte 3 - Identificar Objeto</h3>
<p>
Use o projeto mobilenet_detection para basear seu código. Neste projeto, escolha uma categoria de objetos que o reconhecedor reconhece. Diga aqui qual foi sua escolha. Implemente a seguinte funcionalidade: sempre que o objeto identificado em (2) estiver presente por mais que 5 frames seguidos, desenhe um retângulo fixo ao redor dele.
</p>

<h3>Parte 4</h3>
<p>
Trace uma linha entre os centros do círculo magenta e do círculo ciano. Imprima na tela o ângulo entre esta linha e a horizontal.
</p>

<h3>Parte 5</h3>
<p>
Baseado nos círculos encontrados pela transformada de Hough, desenhe um círculo sobre o círculo ciano e outro sobre o círculo magenta. Desafio bônus: ser capaz de eliminar circulos espúrios (aqueles que não são os da folha).
</p>

<h3>Parte 6</h3>
<p>
Usando um detector de features BRISK, identifique o escrito Insper na folha. Veja os exemplos no notebook e em em código.
</p>
