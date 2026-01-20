# Python-Pandas-etl-s
Repositório para projetos de limpeza de dados com pandas


## 📌 Objetivo ##
Dominar scripts complexas em **Pandas** para projetos etl's.

## 📖 O que estudar? ##
* 🔹 Leitura e Escrita de Arquivos:
`read_csv()`, `read_excel()`, `read_json()`
`to_csv()`, `to_excel()`, `to_json()

Opções úteis: sep, encoding, index_col, usecols


* 🔹 Exploração de Dados:
`.head()`, `.tail()`, `.shape`, `.info()`, `.describe()`, `.dtypes`, `.columns`, `.index

* 🔹 Acessar dados com:
`.loc[]` (rótulos), 
`.iloc[]` (índices)

* 🔹 Manipulação de Dados
    1. Filtros e condições (df[df['coluna'] > 100])
    2. Seleção de colunas e linhas
    3. Renomear colunas: `df.rename()`
    4. Alterar tipos de dados: `astype()`
    5. Ordenar dados: `sort_values()`

* 🔹 Limpeza de Dados
    1. Valores nulos: `isnull()`, `dropna()`, `fillna()`
    2. Remover duplicados: `drop_duplicates()`
    3. Substituir valores: `replace()`, `map()`, `apply()`
    4. Trabalhar com datas: `pd.to_datetime()`

* 🔹 Agrupamentos e Agregações:
`groupby()` + `agg()`: soma, média, contagem, etc.
`pivot_table()`, 
`value_counts()`, `nunique()`

* 🔹 Combinação de DataFrames
`concat()`: empilhar dados,
`merge()`: juntar DataFrames (como JOIN no SQL),
`join()`: alternativa com índices