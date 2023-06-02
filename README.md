# Desafio de 7 dias Pandas


> dados de empréstimos dos acervos do sistema de bibliotecas da UFRN

## Primeiro dia
- Importação de dados
- Unificar em um único Dataframe todos os dados pertinentes para a análise. 
- Mesclar com os dados do acervo, para que você possa entender, por exemplo, de qual biblioteca era o material emprestado ou a qual tema ele se referia. Elas se relacionam pela coluna de código de barras de cada material. 

## Segundo dia
- Iniciar a limpeza e atribuir mais contexto aos seus dados
- Coluna identificada como “localização”
  - - Os itens do acervo em uma biblioteca são organizados por um sistema de classificação de acordo com o respectivo tema. Existem diversos sistemas, mas este conjunto está de acordo com a CDU - Classificação Decimal Universal. Esta classificação é decimal, pois varia de acordo com a classe de cada assunto:
  - - 000 a 099: Generalidades. Ciência e conhecimento.
  - - 100 a 199: Filosofia e psicologia.
  - - 200 a 299: Religião.
  - - 300 a 399: Ciências sociais.
  - - 400 a 499: Classe vaga. Provisoriamente não ocupada.
  - - 500 a 599: Matemática e ciências naturais.
  - - 600 a 699: Ciências aplicadas.
  - - 700 a 799: Belas artes.
  - - 800 a 899: Linguagem. Língua. Linguística.
  - - 900 a 999: Geografia. Biografia. História.
- Excluir a coluna "registro_sistema".
- A coluna da matricula (“matricula_ou_siape”) não está com um formato muito legível. Transforme-a em formato String.