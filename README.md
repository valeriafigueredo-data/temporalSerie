Este repositório armazena os projetos da disciplina de Séries Temporais, do Cesar School.

Na primeira atividade, análises foram tecidas a partir do conjunto de dados chamado "GDP Growth of European Countries". Ele contém informações sobre o crescimento do GDP ("PIB") de mais de 15 países europeus, abrangendo o período de 1960 a 2023.Nesse momento, foram realizados treinamentos em alguns modelos tradicionais (AR, MA, ARMA, ARIMA).
 
 Na segunda atividade, utilizou o dataset 'Covid3Month', presente no tsai. Ocorreu tratamento e análise dos dados, com a estruturação de algumas visualizações e conclusões. Também foi utilizado um modelo de aprendizagem profunda (arquitetura LSTM) para realizar o treinamento, validação, teste e predições. O modelo apresentou um bom desempenho durante as épocas, pois ocorreu um bom ajuste aos dados de treinamento e boa generalização na validação.

No projeto final, o dataset escolhido também foi o 'Covid3Month', presente no tsai. Foram realizados treinamentos e testes em alguns modelos tradicionais (AR, MA, ARMA, ARIMA) e em redes neurais profundas: biblioteca TSAI e arquiteturas LSTM, GRU, Resnet, InceptionTime e TST, assim como em MLP.
 
Nos modelos tradicionais, houve a aplicação dos modelos às colunas dos Estados Unidos e Rússia (inferência externa), devido aos seus comportamentos singulares: maior número de casos e melhor distribuição dos dados na base de dados, respectivamente. O mesmo ocorreu com o MLP.

Na sessão de redes neurais profundas: biblioteca TSAI e arquiteturas LSTM, GRU, Resnet, InceptionTime e TST, os modelos foram aplicados sobre todo o dataset, sem aplicação de filtros dos países, como no anterior.

Durante todo o trabalho, conclusões e análises foram tecidas. É importante ressaltar que nenhum modelo foi considerado muito bom, ideal, todos precisam de melhorias. Por exemplo, no LSTM ( melhor modelo do quadro comparativo do TSAI - redes neurais profundas) é importante em futuros treinamentos aplicar regularização (como Dropout) para buscar reduzir o overfitting.
