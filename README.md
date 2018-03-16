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
- Tenha em mente o diretório em que estão localizados os frames;
- Na classe convert.py, preencha o argumento 'image_folder' com esse diretório;
- Atente para o formato dos frames indicados. Caso o formato seja diferente, revise o código e preencha 
corretamente os argumentos que correspondem ao formato de cada frame;
- Para o argumento 'video_name', escolha o nome que você queira dar ao vídeo que será formado.
- Rode no terminal a classe com o comando: python convert.py;
- Na opção do "compactador", marque a opção 'Microsoft Vídeo 1';
- Verifique o arquivo gerado em sua pasta. 

Tutorial: http://www.femb.com.mx/people-counter/people-counter-with-opencv-python/

Dataset: 
- https://www.d2.mpi-inf.mpg.de/node/428
- http://www.polymtl.ca/litiv/codes-et-bases-de-donnees
- http://www.vision.ee.ethz.ch/en/datasets/
- http://www.gti.ssr.upm.es/data/Lab_database.html
- https://cvlab.epfl.ch/data/pom
