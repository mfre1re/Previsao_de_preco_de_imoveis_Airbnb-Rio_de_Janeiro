# Previsao_de_preco_de_imoveis_Airbnb-Rio_de_Janeiro

Modelo de previsão de preços baseado em parâmetros pré-determinados, que realizarão a análise dos dados (através de modelos de Inteligência Artificial) para desenvolver um método para estabelecer os preços de dado imóvel para os consumidores. 
O objetivo, com isso, é que o usuário comum que irá alugar seu espaço (ou mesmo os que pretendem alugar um imóvel pela plataforma) possam ter uma base de preços coerente e assim tomar decisões com maior confiança sobre os valores que devam utilizar seja para serem competitivos, seja para escolher o local com o melhor custo x benefício.

## Tecnologias e Bibliotecas Utilizadas

- Linguagem: Python 3.9.13
- Bibliotecas: NumPy, Pandas, Matplotlib, Scikit-Learn
- Frameworks: Streamlit
- Ferramentas: Jupyter Notebook, Anaconda

## Instalações
- A instalação do Python pode ser feita através do próprio site, basta buscar no Google:
    Python 3.9.13 (ou a versão mais atual)
- Utilize o Jupyer notebook pelo seu navegador ou instale através do terminal:
    pip install jupyterlab
  
Documentação: https://docs.jupyter.org/en/latest/

Obs_1: Importante dizer que o Google Colab também pode ser utilizado como ferramenta
Obs_2: Caso possua o Anaconda no computador, pode utilizar o Jupyter Notebook presente no Anaconda.

As bibliotecas e frameworks utilizados podem ser instaladas através do pip no terminal:
- Pandas, usada para manipulação e análise de dados:
  *pip install pandas*
  
- NumPY, usada para cálculos numéricos e arrays multidimensionais:
  *pip install numpy*
  
- Matplotlib, usada para criação de gráficos de alta qualidade:
  *pip install matplotlib*
  
- Scikit-Learn, usada para aprendizado de máquina em Python: 
  *pip install -U scikit-learn*
  
- Plotly, usada para visualização interativa e dashboards da web: 
  *pip install plotly*
  
- Streamlit, usada para criação de aplicativos da web interativos e personalizados para suas análises de dados, com facilidade e rapidez:
  *pip install streamlit*

## Como utilizar?
1. Baixe os arquivos necessários, já separados, no local de sua escolha;
2. Em seguida, execute o terminal dentro da pasta baixada ou abra o terminal ou prompt Anaconda, navegue até a pasta que contém os arquivos do modelo;
3. Digite a seguinte linha:
   streamlit run Deploy_Projeto_Airbnb.py

![image](https://github.com/mfre1re/Previsao_de_preco_de_imoveis_Airbnb-Rio_de_Janeiro/assets/88170132/4c358bc0-1574-4cdc-b1f3-ffc2dac7e390)


Desta forma será aberta uma tela em seu navegador padrão (como mostrado na figura abaixo) para que possa ser utilizado a ferramenta para previsão de preços. Nesta tela o usuário deverá preencher as métricas dadas, em inglês, baseado nas especificações utilizadas pelo Airbnb e após o preenchimento clicar em "Prever valor do Imóvel", para que seja obtido a previsão do preço imóvel, em REAIS, do local desejado. Vale ressaltar que a região trabalhada foi o Rio de Janeiro.

![image](https://github.com/mfre1re/Previsao_de_preco_de_imoveis_Airbnb-Rio_de_Janeiro/assets/88170132/7aa77da6-1631-4d06-8929-55ee82854ff8)

Para preenchimento de dados como latitude e longitude (posições cartográficas), podem ser pegos através do Google maps:

![image](https://github.com/mfre1re/Previsao_de_preco_de_imoveis_Airbnb-Rio_de_Janeiro/assets/88170132/117e3087-8657-4c5e-983e-7c3c13d1b5be)

- No Google Maps, na localização desejada, basta dar um clique simples e será mostrado o indicador da posição, tal como na imagem, indicado pela seta azul;
- Em seguida, basta pegar as posições de latitude e longitude, copiar e colar, respectivamente, mostrados na imagem exemplo, sublinhados pela linha vermelha

A Inteligência Artificial nesta ferramenta trabalha utilizando o modelo de ExtraTrees. Nos testes foram trabalhados, além deste modelo, Regressão Linear e Random Forest, sendo o ExtraTrees obtendo a melhor relação com o Coeficiente de Determinação mais elevado e o Erro Quadrático Médio mais baixo.

Caso deseje ENCERRAR a utilização da ferramenta, basta retornar ao terminal e digitar "CTRL" e "C" simultaneamente.

Obs.: Pode levar algum tempo para que a informação do valor seja carregado baseado na capacidade de processamento do computador em uso.




  
  
