# Análise e caracterização de doenças crônicas pulmonares por meio de dados do IBGE e características como regiões e idade

Este artigo analisa a distribuição das doenças crônicas pulmonares na população brasileira utilizando dados da Pesquisa Nacional de Saúde (PNS) de 2019. As doenças crônicas pulmonares representam um desafio significativo para a saúde pública no Brasil, com alta mortalidade associada a essas condições não transmissíveis. A asma, em particular, destaca-se como uma das principais causas de mortalidade nesse contexto.

A pesquisa enfoca a caracterização dessas doenças por regiões geográficas e faixas etárias, utilizando técnicas de ciência de dados e aprendizado de máquina para analisar padrões e tendências. O estudo destaca a importância da PNS como fonte crucial de dados para a formulação de políticas de saúde direcionadas, adaptadas às diferentes realidades regionais e demográficas do Brasil.

O problema identificado revela uma variação significativa na distribuição das doenças crônicas pulmonares conforme as faixas etárias e regiões geográficas, o que justifica a necessidade de estudos detalhados para orientar políticas de saúde mais eficazes e direcionadas. A aplicação de técnicas avançadas de ciência de dados, como o aprendizado de máquina, visa melhorar a compreensão epidemiológica dessas condições e contribuir para modelos preditivos e estratégias preventivas mais precisas.

Os objetivos específicos incluem a análise detalhada dos dados da PNS, a criação de uma base de dados refinada, exploração e interpretação da distribuição das doenças crônicas pulmonares no contexto brasileiro. Ao final, o estudo busca contribuir para o desenvolvimento de políticas de saúde pública mais eficientes, reduzindo a morbimortalidade associada a essas doenças e otimizando o uso dos recursos públicos destinados à saúde.

## Organização do Repositório

O repositório está estruturado da seguinte forma:

### `Artigo_Cientifico_doencas_cronicas_pulmonares`
Contém o artigo científico principal e documentos relacionados.

- `Artigo/`
  - `ARTIGO_CIENTIFICO.docx`: Documento principal contendo a análise realizada.

- `Apresentacao/`
  - `APRESENTACAO_FINAL.pptx`: Arquivo da apresentação final do estudo.

### `BancoDeDados/`
Contém os arquivos de dados utilizados na análise.

- `input_PNS_2019.sas`: Código em SAS para tratamento dos dados.
- `input_PNS_2019.txt`: Versão em texto dos dados processados.
- `PNS_2019.csv`: Base de dados principal utilizada na análise.

### `Codigo/`
Contém os códigos e scripts utilizados na análise dos dados.

- `final.ipynb`: Notebook Jupyter com a análise dos dados e aplicação de aprendizado de máquina.
- `arquivo_final.csv`: Versão final dos dados tratados.
- `primeira_alteracao.csv`, `segunda_alteracao.csv`, `terceira_alteracao.csv`: Arquivos com etapas intermediárias da limpeza e manipulação dos dados.

### `Dicionario/`
Armazena informações sobre a estrutura e os atributos da base de dados.

- `Colunas.txt`: Descrição das colunas presentes na base de dados.
- `dicionario_PNS_microdados.txt`: Dicionário detalhado dos microdados utilizados.

### Arquivo Principal
- `README.md`: Este documento, contendo a descrição do estudo e a estrutura do repositório.

Essa organização facilita a navegação e o entendimento dos arquivos utilizados no estudo.
