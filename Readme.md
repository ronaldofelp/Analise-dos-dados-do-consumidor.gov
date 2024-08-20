# Análise Exploratória de Reclamações no Consumidor.gov

<center>

<img  src='../analise_consumidor.gov/utilities/img/consumidor-gov.jpg' alt='Banner com o logo  do  Consumidor.Gov'>
  
</center>

## Introdução 

Este repositório apresenta uma análise das reclamações registradas no [Consumidor.gov](https://www.consumidor.gov.br)  no primeiro semestre de 2024. O objetivo principal é identificar padrões, tendências e fatores que influenciam a satisfação do consumidor e a eficiência das empresas na resolução de problemas.

## Objetivo da Análise

* **Perfil Geográfico:** Analisar a distribuição geográfica das reclamações, identificando as regiões, estados e cidades com maior incidência.

* **Satisfação do Consumidor:** Avaliar a satisfação do consumidor em relação ao atendimento das empresas, considerando fatores como tempo de resposta, segmento de mercado e nota atribuída.
* **Perfil do Consumidor:** Caracterizar o perfil dos consumidores que registram reclamações, considerando variáveis como faixa etária, sexo e forma de aquisição do produto ou serviço.

## Metodologia

**Coleta e Preparação dos Dados:**
* Os dados foram obtidos do [Consumidor.gov](https://www.consumidor.gov.br) e pré-processados para a análise, incluindo limpeza, transformação e integração de diferentes fontes.
* O processo de ETL (Extract, Transform, Load) pode ser encontrado em `etl_consumidor_gov.ipynb`.

**Análise Exploratória:**
* **Estatística Descritiva:** Cálculo de medidas de tendência central e dispersão para as variáveis numéricas.
* **Visualização de Dados:** Criação de gráficos e tabelas para explorar a distribuição das variáveis e identificar padrões visuais.
* **Análise Bivariada:** Análise da relação entre duas variáveis, como a correlação entre o tempo de resposta e a nota do consumidor.

**Ferramentas:**
* **Linguagem de Programação:** Python
* **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, Geopandas

## Resultados

* **Distribuição Geográfica:** A região Sudeste concentrou o maior número de reclamações, seguida pela região Nordeste. São Paulo foi a cidade com maior incidência.
* **Satisfação do Consumidor:** O segmento bancário liderou o ranking de reclamações, porém as empresas de telecomunicações apresentaram maior índice de satisfação. O tempo de resposta não apresentou correlação significativa com a nota do consumidor.
* **Perfil do Consumidor:** A faixa etária entre 31 e 40 anos foi a que mais registrou reclamações. A maioria dos consumidores procurou a empresa antes de registrar a reclamação no [Consumidor.gov](https://www.consumidor.gov.br).


## Limitações

* **Dados:** Os dados utilizados nesta análise são referentes ao primeiro semestre de 2024 e podem não ser representativos de outros períodos.
* **Causalidade:** A análise exploratória identifica correlações, mas não estabelece relações de causa e efeito. 


## Conclusões

A análise revelou que a satisfação do consumidor varia significativamente entre os diferentes segmentos de mercado e regiões. O tempo de resposta da empresa não parece ser um fator determinante para a satisfação do consumidor. A maioria dos consumidores busca resolver o problema diretamente com a empresa antes de recorrer ao Consumidor.gov.

