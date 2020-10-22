# Dissertação - previsão de coeficiente de atrito


Os arquivos presentes nessa página foram utilizados para o desenvolvimento da Dissertação **"PREVISÃO DO COEFICIENTE DE ATRITO EM PISTA DE POUSO E DECOLAGEM UTILIZANDO REDES NEURAIS ARTIFICIAIS"**. Os modelos desenvolvidos tratam-se de pesquisas acadêmicas e podem conter erros. O autor não se responsabiliza pela seu uso.


Os códigos estão salvos em formato Jupyter Notebook, os quais podem ser utilizados baixando o Anaconda por meio do endereço eletrônico: https://www.anaconda.com/products/individual

As estimativas realizadas pela Rede Neural Artificial dizem respeito a coeficiente de atrito mensurado por equipamento GripTester a 65 km/h a 3 m do eixo da pista de pouso e decolagem do Aeroporto Internacional de Fortaleza.


Explicação sobre os arquivos:<br>
**BD 1.csv**: arquivo com dados de 12 relatórios utilizados para treinar e testar o Modelo M0;

**Multi Layer Perceptron Regressor - Testando arquiteturas de redes (Modelo M0).ipynb**: arquivo em formato Jupyter Notebook para treinar e testar o Modelo M0;

**BD 2.csv**: arquivo com dados de 18 relatórios utilizados para treinar e testar o Modelo M1;

**Multi Layer Perceptron Regressor - Testando arquiteturas de redes (Modelo M1).ipynb**: arquivo em formato Jupyter Notebook para treinar e testar o Modelo M1;

**Modelo M1.ipynb**: arquivo em formato Jupyter Notebook com a arquitetura do Modelo M1 já determinada;

**Validacao.csv**: arquivo com dados do relatório de 14/08/2019 empregado como Validação do Modelo M1;

**Multi Layer Perceptron Regressor - Testando arquiteturas de redes (Modelo M2).ipynb**: arquivo em formato Jupyter Notebook para treinar e testar o Modelo M2;

**BD 3.csv**: arquivo com dados de 19 relatórios utilizados para treinar e testar o Modelo M2 (Dados.csv + Validacao.csv);

**Modelo M2.ipynb**: arquivo em formato Jupyter Notebook com a arquitetura do Modelo M2 já determinada;

**MODELO_M2.xlsx**: arquivo em formato Excel com o Modelo M2;

**coeficientes_entrada_1_cam_oculta.txt**: matriz com os pesos sinápticos da camada de entrada para primeira camada oculta;

**coeficientes_1_cam_oculta_2_cam_oculta.txt**: matriz com os pesos sinápticos da primeira camada oculta para a segunda camada oculta;

**coeficientes_2_cam_oculta_saida.txt**: matriz com os pesos sinápticos da segunda camada oculta para a camada de saída;

**interceptor_entrada_1_cam_oculta.txt**: vetor com os pesos sinápticos dos interceptores da camada de entrada para a primeira camada oculta;

**interceptor_1_cam_oculta_2_cam_oculta.txt**: vetor com os pesos sinápticos dos interceptores da primeira camada oculta para a segunda camada oculta;

**interceptor_2_cam_oculta_saida.txt**: vetor com os pesos sinápticos dos interceptores da segunda camada oculta para a camada de saída;




Contato: brenoquariguasi@det.ufc.br
