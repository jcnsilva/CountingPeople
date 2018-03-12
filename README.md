# Contador de pessoas em vídeo

**Projeto desenvolvido para as disciplinas Inteligência Artificial e Visão Computacional - UFCG**

Equipe: 
* Bruno Rocha
* Diana Marcela
* Júlio César
* Matheus Oliveira
* Veruska Santos

Para executar: 
- Com arquivo de vídeo: python countingPeople.py --video videos/video.mp4
- Da webcam: python countingPeople.py

Para converter frames em um vídeo .avi:
1- Tenha em mente o diretório em que estão localizados os frames;
2- Na classe convert.py, preencha o argumento 'image_folder' com esse diretório;
3- Atente para o formato dos frames indicados. Caso o formato seja diferente, revise o código e preencha 
	corretamente os argumentos que correspondem ao formato de cada frame;
4- Para o argumento 'video_name', escolha o nome que você queira dar ao vídeo que será formado.
5- Rode no terminal a classe com o comando: python convert.py;
6- Na opção do "compactador", marque a opção 'Microsoft Vídeo 1';
7- Verifique o arquivo gerado em sua pasta. 

Tutorial: http://www.femb.com.mx/people-counter/people-counter-with-opencv-python/

Dataset: 
* https://data.kitware.com/#collection/56f56db28d777f753209ba9f
* https://www.cs.utexas.edu/~chaoyeh/web_action_data/dataset_list.html
* http://www.vision.ee.ethz.ch/en/datasets/
