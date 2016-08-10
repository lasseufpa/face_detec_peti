# face_detec_peti

Projeto de detecção de faces e também de outros objetos usando classificadores "haar cascade" (Viola Jones).

## As pricinpais issues do projeto ou subprojetos são:

1. Estudar o processo e códigos para treinamento de detector de face, e treinar um sistema que seja robusto a inclinações da cabeça, ou seja, permita detectar faces que estejam inclinadas (por exemplo, em 45 graus)
2. Gerar código no Octave ou Matlab que permita importar um detector treinado com OpenCV e disponibilizado em XML no "novo" formato (notar que já há código para lidar com o antigo formato). Depois comparar o resultado da execução em Octave/Matlab com o obtido com OpenCV para as mesmas imagens
3. Avaliar e reduzir o custo computacional da etapa de execução do detector de faces no Matlab/Octave. Para isso, fazer "profiling" do código, identificar funções críticas, avaliar seu custo, otimizar o código para reduzir esforço. Daí comparar a versão inicial com o código otimizado para reportar de preferência ganho significativo
4. Fazer uma avaliação sistemática de um detector de faces a partir de conjuntos de imagens relativamente grandes obtidos na Web. Usar conjunto de teste disjunto do de treino. Inserir ruído de forma controlada nas imagens (pode-se usar PSNR por exemplo) ou rotacionar levemente as imagens. Estudar principais fatores afetando o desempenho
5. Usando os mesmos algoritmos de detecção de face do Viola&Jones, treinar e avaliar um detector para um outro problema (por exemplo, detectar um carro em rodovia). Pode-se usar conjunto de imagens já disponível na Internet, mas não se pode simplesmente usar um detector já treinado. A equipe precisa aprender a treinar e gerar um detector.

## Materiais de auxílio

###### Artigo Viola Jones
[Viola Jones 1](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-cvpr-01.pdf)
[Viola Jones 2](http://www.vision.caltech.edu/html-files/EE148-2005-Spring/pprs/viola04ijcv.pdf)
[Nesse trabalho em portugês tem uma parte que fala sobre o Viola Jones](http://www.di.ubi.pt/~hugomcp/doc/SilvioFilipe.pdf)


###### Treinamento de classificadores

Materiais sobre o processo de treinamento de um classificador para reconhecimento de objetos, serão uteis pra os subprojetos 1 e 5.


[Face Detection using Haar Cascades](http://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html#gsc.tab=0)

[Cascade Classifier Training](http://docs.opencv.org/trunk/dc/d88/tutorial_traincascade.html#gsc.tab=0)

[Video OpenCV Windows](https://www.youtube.com/watch?v=yXm4heIHRr4)

[Video OpenCV Linux](https://www.youtube.com/watch?v=WEzm7L5zoZE)

[Exemplo Matlab 1](https://www.mathworks.com/matlabcentral/fileexchange/44545-train-cascade-object-detector)

[Exemplo Matlab 2](https://www.mathworks.com/matlabcentral/fileexchange/36855-face-parts-detection)

###### Detecção

[Exemplo Matlab 1](https://www.mathworks.com/matlabcentral/fileexchange/29437-viola-jones-object-detection)

###### Extras

Cada equipe da turma de projetos 2 e também o grupo do PETi deve eleger alguém que fique responsável pelo código da equipe. O responsável elegido deve dar fork neste repositório e criar uma pasta nele com um nome que identifique a equipe, nesta pasta ficaram os códigos de denvolvidos pelo grupo.

Os outros membros da equipe devem contribuir dando fork no repositório do repositório "forcado" pela pessoa que deu fork nesse repositório ou sendo adicionado como colaborador no repositório principal da equipe.

Além das pastas com os materiais de cada grupo, também existiram pastas com exemplos e materiais de apoio que poderão ser copiados para as pastas do grupos. caso algum grupo precise de um algo desenvolvido por outro grupo também poderão copiar os arquivos de uma pasta para outra.

Conforme o projeto for sendo desenvolvido as equipes devem dar pull request para este repositório para que todos possam acompanhar o que vem sendo desenvolvido.

Na parte das issues aqui no GitHub também existem alguns materiais interessantes.

