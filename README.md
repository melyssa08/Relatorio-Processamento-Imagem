# Relatório sobre Tarefas de Processamento de Imagem

O relatório a ser descrito tem como propósito demonstrar conhecimentos acerca de duas tarefas da visão computacional, suas aplicabilidades e nichos de mercado pelos quais essas aplicabilidades pertencem, e por fim, fazer uma demonstração de um produto via código com um modelo de visão computacional pré-treinado.

## Tarefas selecionadas para aprofundamento

Primeiramente, no que se refere as duas tarefas escolhidas, a primeira que será aprofundada será a da "classificação" e em seguida a tarefa de "detecção de objetos". Logo abaixo haverá informações acerca das duas escolhidas.

Diante da tarefa de "classificação", essa abordagem tange na rotulagem de somente um objeto numa imagem, um exemplo, seria dizer que houve necessidade de classificar se tal veículo era um carro ou um ônibus, visto isso, um único objeto será considerado nesta situação ou pertencente a classe ônibus ou pertencente a classe carro, e essa tarefa de rotular nesta situação, e outras semelhantes, se denominaria "classificação".

Ademais, outra tarefa importante é a "detecção de objetos" que é basicamente um compilado da localização de um objeto com sua categorização provinda de ser a instância de alguma classe; e a junção dessas duas etapas de encontrar e rotular que se encontra o processo de detecção. Partindo disso, um exemplo seria num jogo de futebol em que é possível identificar os jogadores em campo com suas localizações e rotulagens como jogadores, ao mesmo tempo que classifico a bola de futebol pela sua posição no jogo e sua categorização como bola de futebol.

Portanto, sendo descritas as tarefas, o próximo passo será redigir sobre suas aplicabilidades, ou seja, produtos provindos, e por fim, dizer algumas segmentações de mercado pelos quais esses produtos atuam.

## Aplicabilidades em produtos e segmentações de mercado atendidas

Primeiramente, no que tange da primeira tarefa escolhida, no caso a "classificação", um produto que chama a atenção é o modelo pré-treinado provindo da arquitetura "InceptionV3", com o conjunto de dados do ImageNet, do Keras, este modelo feito pelo Google Research, utiliza uma arquitetura de rede neural convolucional (CNN), e pode ser usado tanto para já fazer classficações, pois o modelo já contém 1000 categorias, como também pode ser usado para ser treinado para atender outras categorias. Vale lembrar que sua disponibildade para usar este modelo é gratuita. 

Seguidamente, os segmentos que o produto citado pode atuar são amplas, dois exemplos, seria na classificação, por exemplo de glóbulos brancos ou vermelhos na perspectiva da área da saúde, ou outro caso, no agronegócio no contexto de rotular qual cultura está sendo plantada em uma área de cultivo. Concluindo, essas aplicabildades citadas foram só uns exemplos da ampla gama de ações provindas da classificação na visão computacional.

Outrora, na perspectiva de "detecção de objetos", a arquitetura do "YOLOv5" que possui código aberto e uma API de python para multi frameworks, como TensorFlow, PyTorch, entre outros. Está arquitetura já possui modelos pré-treinados disponibilizados para variados contextos.

Ademais, com o produto dito acima de código aberto, as ações são variadas para vários nichos do mercado, em termos de exemplo, será citado dois, o primeiro condiz na monitoração de trânsito para entender a movimentação de variados transportes numa estrada e a frequência de cada tipo de transporte, e com isso, tirar insights do tráfego de tal estrada; outro exemplo, seria na detecção do movimento das expressões faciais e a partir disso tirar conclusões acerca das emoções de um paciente.

Concluindo, as aplicações dentre as duas tarefas são enormes e significativas e ter produtos como os citados acima, que são estas arquiteturas com modelos pré-treinados ajuda desenvolvedores a melhorarem seus próprios produtos de mercado economizando tempo, desempenho e proporcionando aprendizagens.

## Teste de produto

Nesta seção ocorrerá um teste usando um modelo pré-treinado da arquitetura do "InceptionV3" para a tarefa de classificação. O caso de teste, simplesmente, abordará qual categoria a imagem de cachorro "cachorro-teste.jpg" pertence. O código está no notebook "ponderada-classificacao-imagem.ipynb" com sua documentação incorporada no código.

Portanto, dentre o código é possível ver as operações feitas e o resultado trazido, em relação ao resultado, é interessante citar que existiu três provavéis categorias, isto é, "Labrador_retriever", "golden_retriever" e "kuvasz", e no fim, a maior porcentagem foi para o "Labrador_retriever" que seria exatamente a raça do cachorro.

## Links úteis

https://blog.roboflow.com/intro-to-computer-vision/

https://cloud.google.com/tpu/docs/inception-v3-advanced?hl=pt-br#:~:text=O%20Inception%20v3%20%C3%A9%20um,conjunto%20de%20dados%20do%20ImageNet.