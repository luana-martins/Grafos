# Seleção de Features para a Classificação de Dados de Saúde

## Luana Almeida Martins, Jalisson Henrique, Tiago Fernandes

A alta dimensionalidade das bases de dados para o treinamento de modelos de Machine Learning (ML) pode ser prejudicial para a sua generalização e acurácia de predição. Dessa forma, o problema de seleção de um subconjunto ótimo de features, conhecido com um problema NP-Difícil, é considerado para a identificação das features relevantes para o modelo. Nesse trabalho, o problema da seleção de features é explorado no contexto da classificação de dados de saúde, em especial, para a predição de câncer de mama. Para isso, é proposta uma abordagem híbrida entre os métodos Filter e Wrapper, para a qual é desenvolvido o algoritmo JLT. O algoritmo consiste em quatro etapas: i) Filtro de subconjuntos iniciais de features por meio das correlações fortes e fracas entre features e label; ii) Wrapper entre duplas de features do tipo forte e fraca para seleção de uma dupla promissora, iii) Filtro do subconjunto de features complementares à dupla promissora, e iv) Wrapper entre features complementares e dupla de promissora. Além disso, foi realizado um experimento que consiste na comparação da precisão e recall para a execução de modelos de ML (*Decision-Tree*, *KNN*, *Random-Forest*, e *SVM-Linear*) utilizando os algoritmos JLT e *Sequential Forward Selection* (SFS) para a seleção de features e sem a execução desses algoritmos. Como resultado, os modelos de ML apresentaram resultados melhores quando utilizados os algoritmos de seleção de features.

**Arquivos disponíveis:**
* data.csv - contém o dataset *Breast Cancer Wisconsin (Diagnostic)*, também disponível em *UCI Machine Learning Repository* (importado aqui apenas para manter todos os dados em um só lugar)
* grafos.ipynb - contém todas as implementações necessárias para a reprodução do experimento. Esse arquivo contém o algoritmo JLT proposto, bem como ad implementações dos algoritmos SFS e dos quatro modelos de ML citados anteriormente. 
* DadosExperimento - contém todos os dados coletados a partir do experimento.
* Apresentação do trabalho disponível em: https://drive.google.com/file/d/17csBabPIMJatKPAsAoDeBG3dDftq3163/view

**Execute o código pelo Colab, não há necessidade de fazer uma cópia o ambiente está configurado para isso**
