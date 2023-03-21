## Levantamento de Nascidos Vivos no Brasil entre os anos de 2001 e 2020.

1. O trabalho teve como principal objetivo além de fazer um levantamento do número de nascimentos no Brasil no período 2001-2020.
- Fazer uma análise geral sobre o perfil das mães e suas tendências ao longo do tempo.
- Levantar informações sobre tipo de parto, peso médio das crianças, total de crianças entre outras informações. 
- Optou-se por aprofundar um levantamento nos dados de nascidos com alguma anomalia identificada e obter dados com mais detalhamento sobre a incidência de Sindrome de Down e suas possiveis relações.

2. O conjunto de Dados foi obtivo no site do Governo Brasileiro, vinvulado ao Ministério da Saúde em Fevereiro de 2023, link abaixo:
- https://opendatasus.saude.gov.br/dataset/sistema-de-informacao-sobre-nascidos-vivos-sinasc-1996-a-2020

3. O período definido de análise foram os dados de 2001 até 2020, por estarems mais completos.
As tabelas foram agrupadas num único arquivo e feito o tratamento nos dados, dentre os quais cabe destacar o seguinte:

- Considerando a questão fisiológica das mulheres foi considerado apenas mães com idade no intervalo de [10,50];
- Foi Identificado também registros de nascimentos com mais de uma anomalia registrada e nesse caso, foi definido que a primeira anomalia registrada,
seria considerada a predominante. Foi definido também um foco mais detalhado apenas no caso da Sindrome de Down e assim foram selecionados 
apenas os caso de registro único de qualquer um dos subgrupos abaixo, na categoria Q90 e nessa categoria existem os seguintes subgrupos: 

- Q 90.0 Síndrome de Down, trissomia do 21, por não disjunção meiótica;
- Q 90.1 Síndrome de Down, trissomia do 21, mosaicismo por não disjunção mitótica;
- Q 90.2 Síndrome de Down, trissomia 21, translocação;
- Q 90.9 Síndrome de Down, não específica.

- Outras observações sobre o tratamento estão detalhadas nos notebooks.

4. O trabalho foi dividido em 4 partes devido ao tamanho dos dados, os arquivos são muito grandes, ultrapassa 3gb, foi utiliizado
equipamento com 16gb de memória ram para fazer as análise e processar os ajustes nos dados.

5. Como o arquivo final é muito grande, adicionei um amostra de 10% do arquivo final, mas não se engane, a amostra contém 
mais de cinco milões de registros, mais precisamente: 5.604.636 registros

6. Foi utilizado o Jupyter Notebook e a linguagem Python com algumas de suas bibliotecas.

