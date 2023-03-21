# Levantamento de Nascidos Vivos no Brasil entre os anos de 2001 e 2020.

1. O trabalho teve como principal objetivo além de fazer um levantamento do número de nascimentos no Brasil no período 2001-2020.
- Fazer uma análise geral sobre o perfil das mães e suas tendências ao longo do tempo;
- Levantar informações sobre tipo de parto, peso médio das crianças, total de crianças entre outras informações; 
- Fazer um levantamento nos dados de nascidos com alguma anomalia identificada e obter dados com mais detalhamento sobre o incidência de Sindrome de Down e suas possiveis relações.

2. O conjunto de Dados de Nascidos Vivos do Ministério da Saúde do Governo Brasileiro foi obtivo em:
- https://opendatasus.saude.gov.br/dataset/sistema-de-informacao-sobre-nascidos-vivos-sinasc-1996-a-2020

3. Selecionamos os dados de 2001 a 2020, por estarems mais completos e analisamos algunas aspectos dos dados nesse intervalo de tempo.
Compilamos todas as tabelas num único arquivo e fizemos o tratamento nos dados, dentre os quais cabe destacar o seguinte:

- Considerando a questão fisiológica das mulheres estamos considerando apenas mães com idade no intervalo de [10,50];
- Identificamos Nascimentos com mais de uma anomalia registrada, como o foco do trabalho mais detalhado está apenas no caso da 
Sindrome de Down, optamos por selecionar apenas os caso de único registro de qualquer um dos subgrupos abaixo na categoria Q90, nessa
categoria existem os seguintes subgrupos:
         - Q 90.0 - Síndrome de Down, trissomia do 21, por não disjunção meiótica
         - Q 90.1 - Síndrome de Down, trissomia do 21, mosaicismo por não disjunção mitótica
         - Q 90.2 - Síndrome de Down, trissomia 21, translocação
         - Q 90.9 - Síndrome de Down, não específica

- Outras observações sobre o tratamento estão detalhadas nos notebooks.

- Dividimos em 4 partes os notebooks devido ao tamanho dos dados, os arquivos são muito grandes passam de 3gb, utilizamos
equipamento com 16gb de memória ram para fazer as análise e processar os ajustes nos dados.

- Como o arquivo final é muito Grande, adicionei um amostra de 10% do arquivo final, mas não se engane, a amostra contém 
mais de cinco milões de registros, mais precisamente: 5.604.636 registros

4. Utilizamos o Jupyter Notebook e a linguagem Python com algumas de suas bibliotecas.

