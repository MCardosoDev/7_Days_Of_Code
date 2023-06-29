# Desafio de 7 dias com Pandas

> dados de empréstimos dos acervos do sistema de bibliotecas da UFRN

## Primeiro dia
- Importação de dados
- Unificar em um único Dataframe todos os dados pertinentes para a análise. 
- Mesclar com os dados do acervo, para que você possa entender, por exemplo, de qual biblioteca era o material emprestado ou a qual tema ele se referia. Elas se relacionam pela coluna de código de barras de cada material. 

## Segundo dia
- Iniciar a limpeza e atribuir mais contexto aos seus dados
- Coluna identificada como “localização”
  - Os itens do acervo em uma biblioteca são organizados por um sistema de classificação de acordo com o respectivo tema. Existem diversos sistemas, mas este conjunto está de acordo com a CDU - Classificação Decimal Universal. Esta classificação é decimal, pois varia de acordo com a classe de cada assunto:
  - 000 a 099: Generalidades. Ciência e conhecimento.
  - 100 a 199: Filosofia e psicologia.
  - 200 a 299: Religião.
  - 300 a 399: Ciências sociais.
  - 400 a 499: Classe vaga. Provisoriamente não ocupada.
  - 500 a 599: Matemática e ciências naturais.
  - 600 a 699: Ciências aplicadas.
  - 700 a 799: Belas artes.
  - 800 a 899: Linguagem. Língua. Linguística.
  - 900 a 999: Geografia. Biografia. História.
- Excluir a coluna "registro_sistema".
- A coluna da matricula (“matricula_ou_siape”) não está com um formato muito legível. Transforme-a em formato String.

## Terceiro dia
- Entender se a quantidade de empréstimos está diminuindo, aumentando ou permanecendo igual ao decorrer dos últimos anos.
- Verificar qual é a quantidade total de exemplares emprestados por cada ano e plote um gráfico de linhas.
- Fazer uma análise em relação à visualização gerada.
- Exemplares emprestados e não de empréstimos realizados.
- Entender para gerenciar a programação de férias dos colaboradores de acordo com os meses de menor demanda
- Entender para programar atividades que não sejam de atendimento ao usuário para períodos específicos de menor demanda.
- Gerar uma tabela com a quantidade total de exemplares emprestados por mês e descobrir quais meses são os que possuem a maior quantidade de empréstimos realizados. Plote um gráfico de linhas.

## Quarto dia
“Como se distribuem os empréstimos de exemplares pelos tipos de vínculo dos usuários?”
Desta forma, a diretoria poderá entender qual é o público que está utilizando a biblioteca e assim tomar decisões em continuar com a estratégia de negócio atual ou modificá-la.

Quais coleções são mais emprestadas?
Da mesma forma, as coleções. Ranquear as coleções mais emprestadas pelo público, será bastante importante para a estratégia atual.

Quais são as bibliotecas com mais ou menos quantidade de empréstimos?
Assim, a diretoria conseguirá entender onde ela deverá melhorar e focar suas iniciativas.

Gerar uma tabela de frequência e com o percentual para cada variável.

Criar uma função que gere a tabela com os valores.

## Quinto dia
Verifique qual é a coleção com maior frequência para cada tipo de usuário.
Filtre os dados com condições solicitadas
Selecione apenas os empréstimos
Faça a contagem de empréstimos mensais por cada ano
Crie uma função para gerar a visualização do gráfico de box plot por cada ano.
Crie o gráfico de boxplot

## Sexto dia
Calcular a quantidade de empréstimos realizados entre 2015 e 2020 por cada curso de graduação que passará pela avaliação.

Os cursos serão:
  - Biblioteconomia
  - Ciências sociais
  - Comunicação social
  - Direito
  - Filosofia
  - Pedagogia

Gerar uma tabela com as seguintes características:
  - Índice: Cursos
  - Colunas: Ano
  - Valores: Quantidade de empréstimos
  - Total: Acrescente uma linha e uma coluna de total a tabela

## Sétimo dia
Criar uma tabela com as diferenças percentuais de empréstimos entre 2017-2018, 2018-2019, 2019-2022.

Criar o HTML da tabela.

Não contenha numeração de índice;
Os nomes dos cursos tenham apenas a primeira letra maiúscula;
Os números percentuais estejam indicados pelo símbolo “%”;
Cor dos números: Positivos = Verde; Negativos = Vermelho

Criar a tabela já com algumas estilizações do CSS prontas para adiantar o trabalho.

O padrão inicial para as tabelas deste projeto será:

- Cabeçalho:
  - font-size = 1.4rem
  - text-align = center
  - font-weight = bold
  - color = whitesmoke
  - background-color = #001692
  - border-radius = 0.25rem
  - box-shadow = 0 0 1rem gray

- Corpo:
  - font-size = 1rem
  - padding = 0.5rem
  - text-align = left
  - font-weight = bold
  - border-bottom = 0.1rem solid lightgray