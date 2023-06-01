# Projetos de dados
Basicamente, aqui se reúne toda minha experiência com dados, processo que se iniciou durante a graduação em Matemática (Bacharelado), onde tive primeiro contato com programação e alguns projetos de aprendizado de máquina (seção 2, no índice a seguir).

## Índice
- 1 - [ENEM 2021](https://github.com/GHM-ML/Projetos-de-dados/tree/main/ENEM%202021)

- 2 - [Imersão dados Alura](https://github.com/GHM-ML/Projetos-de-dados/tree/main/Imersao-dados-Alura)

- 3 - [Processamento de Linguagem Natural](https://github.com/GHM-ML/Projetos-de-dados/tree/main/Processamento%20de%20Linguagem%20Natural) 

    - 3.1 - [Predição de gênero musical](https://github.com/GHM-ML/Projetos-de-dados/tree/main/Processamento%20de%20Linguagem%20Natural/Predi%C3%A7%C3%A3o%20de%20g%C3%AAnero%20musical)

    - 3.2 - [Tweets de desastre](https://github.com/GHM-ML/Projetos-de-dados/tree/main/Processamento%20de%20Linguagem%20Natural/Tweets%20de%20desastre)
   
- 4 - [Trabalhos graduação](https://github.com/GHM-ML/Projetos-de-dados/tree/main/Trabalhos-graduacao)

## Um resumo sobre dados:
Dados são valores atribuídos a algo chamado variável, cujos valores podem ser numéricos ou conceituais (categóricos). Os de tipo categórico podem obedecer a uma hierarquia (categórico ordinal) ou não (categórico nominal), já os de tipo numérico podem ser do tipo discreto (que assume valores inteiros: 1,2,3, assim por diante) ou contínuos (que permitem fracionamento). Podem ser medidos por algum instrumento ou de desígnio arbitrário.
Um conjunto de dados é uma coleção de dados.
Dados contém erros e vieses em sua concepção, o que influencia na coleta, tratamento e análise deles.
São explorados em busca de informações que gerem valor a alguém, contando uma história ou respondendo a alguma pergunta.
Dados podem ser pessoais ou empresariais, abertos ao público ou fechados. A LGPD cuida de delimitar dados pessoais sensíveis e protegê-los.
### Coleta e armazenamento:
Dados digitais são gerados, por exemplo, conforme os usuários usam aparelhos, redes sociais, navegam na web. Ou nas empresas, com os registros de compras, vendas, relatórios operacionais e seu armazenamento depende do volume com que são gerados, a velocidade e variedade.
Dados são geralmente são armazenados bancos de dados e gerenciados por SGBDs (Sistemas de Gerenciamento de Banco de Dados) de vários tipos, a depender da estrutura inerente aos dados em questão.
### Análise exploratória de dados:
#### Medidas:
Várias medidas estatísticas são empregadas para análise de dados:

1. As **medidas de tendência central** mostram valor central ou típico para uma distribuição de probabilidades, elas são **média(s), mediana e moda**.
   - **Moda:** O valor que mais se repete dentro do conjunto de dados.
   
   - **Mediana:** O valor central do conjunto de dados ordenado crescentemente.
   
   - **Média ($\mu$):** Soma dos valores do conjunto, dividido pelo seu tamanho. 
 
      - Ou seja, $\Large \mu = \frac{1}{N} \sum\limits_{i=i}^{N} x_{i}$, onde $x_{i}$ é uma observação e $N$ o tamanho do conjunto de dados.
     
2. Já as **medidas de dispersão** são concebidas para fornecerem uma ideia sobre o quão distribuídos os valores dos dados estão distribuídos em torno da média. São elas: **variância, desvio padrão e amplitude interquartil**.

   - **Variância ($\sigma^2$):** Soma dos quadrados das diferenças entre cada observação $x_{i}$ e a média $\mu$, divididos pelo total de observações $N$.
  
     - Matematicamente: $\Large \sigma^2 = \frac{1}{N} \displaystyle\sum_{i=1}^{N}(x_i - \mu)^2$
   
   - **Desvio Padrão ($\sigma$):** A raiz quadrada positiva da variância. Usada para melhor interpretabilidade, pois a unidade de medida da variância é o quadrado da dimensão dos dados (exemplo, se a dimensão do dado for cm, a variância será dada em cm², mas o desvio padrão volta para cm).
   
   - **Amplitude Interquartil:** Primeiramente, um quartil é qualquer um dos três valores que divide o conjunto ordenado de dados em quatro partes iguais, e assim cada parte representa 1/4 da amostra ou população. O primeiro quartil (também chamado quartil inferior) é o valor aos 25% do conjunto ordenado, o segundo quartil, também chamado **mediana** é o valor aos 50% do conjunto ordenado, o terceiro (quartil superior), 75%. Amplitude Interquartil é o nome que se dá à diferença entre os quartis superior e inferior.

#### Visualização:
- Variáveis Qualitativas:

Existem vários tipos, mas geralmente são variações estéticas do mesmo princípio, será apresentado o de barras:
  
<img src= "https://github.com/GHM-ML/Projetos-de-dados/assets/100609713/3794cc86-8b9f-4fa0-bb57-c1bd8abab29c" width=30% height=30%>
A ideia por trás dessa forma de apresentação é mostrar as categorias na horizontal e a frequência de cada uma na vertical.

E o de setores (ou de pizza):

<img src= "https://github.com/GHM-ML/Projetos-de-dados/assets/100609713/41ca0aa0-9c82-4365-9785-a5b0ff405e77" width=30% height=30%>

Cujo princípio é mostrar a frequência como área do setor que a categoria representa.

- Variáveis Quantitativas:

Os gráficos mostrados também funcionam bem para variáveis quantitativas discretas. Além deles, pode-se considerar:



<img src= "https://github.com/GHM-ML/Projetos-de-dados/assets/100609713/7fd27912-5606-4ddb-a967-06085e18e5e3" width=30% height=30%>

## Big data
Refere-se a um conjunto de tecnologias requeridas quando um conjunto de dados é volumoso, variado e coletado em escalas tão fora dos padrões tradicionais (como os dados gerados em redes sociais), que as técnicas de coleta, tratamento, operações de consulta e geração de relatórios se tornam impraticáveis, forçando o desenvolvimento de recursos e procedimentos otimizados para lidar especificamente com este tipo de conjunto de dados.
## Machine Learning
Muitas vezes, busca-se obter inferências ou entender as relações existentes entre as variáveis constituintes de um conjunto de dados. O Aprendizado de Máquina (Machine Learning) é a ciência de desenvolvimento de algoritmos e modelos estatísticos que voltado para atender a essas necessidades. Apesar de possuir vários algoritmos voltados à resolução de vários tipos de problemas, as classificações mais comuns são:
1. Aprendizado supervisionado;
2. Aprendizado não supervisionado;
3. Aprendizado semissupervisionado;
4. Aprendizado por reforço.

Os algoritmos de tipo 1. (únicos tratados aqui, até o momento) podem, ainda, serem subcategorizados em: Regressão e Classificação.

# Referências:
- https://escoladedados.org/tutoriais/o-que-sao-dados/#:~:text=Em%20resumo%2C%20dados%20s%C3%A3o%20valores,ser%20atribu%C3%ADdos%20de%20forma%20arbitr%C3%A1ria.
- https://pt.wikipedia.org/wiki/Sistema_de_gerenciamento_de_banco_de_dados
- https://www.oracle.com/br/big-data/what-is-big-data/
- https://aws.amazon.com/pt/what-is/machine-learning/
- [Estatística Básica (Livro por Pedro Alberto Morettin e Wilton O. Bussab)](https://g.co/kgs/tNHyFY)
- [An Introduction to Statistical Learning: with applications in R (Livro por Daniela Witten, Robert Tibshirani e Trevor Hastie)](https://g.co/kgs/5DGxto)
