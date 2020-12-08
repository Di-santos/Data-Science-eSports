# Analisando o cenário competitivo de E-Sports com técnicas de data science e machine learning

Link: [Análise (Google Colab)](/FSI.ipynb)

<img src = "https://user-images.githubusercontent.com/68029637/97033725-2bad5b80-153a-11eb-9956-a980a11e835b.png" width = "800" height = "400">
<img src = "https://user-images.githubusercontent.com/68029637/97033779-3f58c200-153a-11eb-8120-fbf9f477269e.png" width = "800" height = "400">
<img src = "https://user-images.githubusercontent.com/68029637/97033786-4253b280-153a-11eb-8e7f-2727c2dc85ea.png" width = "600" height = "300">
<img src = "https://user-images.githubusercontent.com/68029637/97033795-4384df80-153a-11eb-89d8-409aa7ac03e7.png" width = "400" height = "300">

## Objetivo 

Este projeto foi desenvolvido por mim e pelo João (GitHub: JhonesBR) como avaliação na universidade. Seu objetivo principal era a introdução às técnicas de data science e machine learning, além de instigar o aluno a desenvolver a capacidade de gerar, polir e testar insights sobre temas diversos. Ademais, também aprendemos a trabalhar em grupo e coordenar projetos, uma vez que os trabalhos possuíam prazos sequenciais que requeriam organização e planejamento por parte da equipe.

## Início

Primeiramente, importamos o dataset do kaggle contendo o csv com os dados do cenário competitivo de E-Sports de LoL. Depois, importamos as bibliotecas do pandas, seaborn, numpy e matplotlib (essenciais para nossa análise). Por fim, formatamos e imprimimos as tabelas, que serão melhor explicadas nas seções seguintes.

## Análise Exploratória e Modelagem

Na análise exploratória, usamos histogramas e projeções simples para elaborar nossas primeiras hipóteses sobre comportamentos e estatísticas do campeonato, como taxas de vitórias e banimentos. Em determinada parte do trabalho, quando fomos solicitados para desenvolver o modelo de previsão, precisamos adicionar as informações individuais de cada campeão "na marra", já que o dataset não possuía tal formatação. Quanto ao cross-validation e matriz de confusão, tudo ocorreu bem e só tivemos alguns problemas (potencial overfitting).

## Insights Desenvolvidos

Dentre os insights desenvolvidos, diversos deles se mostraram verídicos após os teste e o debate com a turma. Notamos por exemplo, que o campeão "Zac" era o número um em banimentos por parte do lado vermelho, em contraste com uma taxa irrisória do lado azul. Concluímos, assim, que isso ocorre pelo fato do "Zac" se beneficiar da falta de visão do oponente, que se mostra muito mais vulnerável do lado vermelho do campo. Essa discussão e polimento de Insights foi muito vantajosa para nós, já que serviu para apurar nossa lógica e análise.





