# Análise de Sobrevivência no Titanic

## Descrição do Projeto

Este projeto foi desenvolvido como parte de uma atividade do curso de Análise de Dados ou Ciência de Dados, utilizando o famoso conjunto de dados do Titanic. O objetivo principal foi explorar os dados, realizar análises estatísticas e responder a perguntas relevantes, como:

- Qual foi a taxa de sobrevivência geral?
- Como fatores como classe de embarque, sexo e idade influenciaram a sobrevivência?
- Qual foi a taxa de sobrevivência por local de embarque?

O conjunto de dados do Titanic é amplamente utilizado para estudos de análise de dados e aprendizado de máquina, pois contém informações demográficas e de sobrevivência dos passageiros a bordo do navio.

## Conjunto de Dados

O conjunto de dados utilizado contém informações sobre os passageiros do Titanic, incluindo:

- `Survived`: Indica se o passageiro sobreviveu (1) ou não (0).
- `Pclass`: Classe de embarque (1ª, 2ª ou 3ª classe).
- `Name`: Nome do passageiro.
- `Sex`: Gênero do passageiro.
- `Age`: Idade do passageiro.
- `SibSp`: Número de irmãos/cônjuges a bordo.
- `Parch`: Número de pais/filhos a bordo.
- `Ticket`: Número da passagem.
- `Fare`: Tarifa paga pela passagem.
- `Cabin`: Número da cabine.
- `Embarked`: Local de embarque (`C` = Cherbourg, `Q` = Queenstown, `S` = Southampton).

O conjunto de dados foi obtido a partir do Kaggle ou de repositórios públicos como o GitHub.

## Metodologia

O projeto foi dividido nas seguintes etapas:

### 1. Carregamento dos Dados
Os dados foram carregados usando a biblioteca Pandas em Python.

### 2. Limpeza e Pré-processamento
- Dados faltantes foram tratados (por exemplo, valores ausentes na coluna `Age`).
- Colunas irrelevantes para a análise foram removidas.

### 3. Análise Exploratória de Dados (EDA)
- Foram criados gráficos e tabelas para entender a distribuição dos dados.
- Taxas de sobrevivência foram calculadas com base em diferentes variáveis, como sexo, classe de embarque e local de embarque.

### 4. Visualização de Dados
Gráficos como histogramas, gráficos de barras e heatmaps foram utilizados para visualizar os resultados.

### 5. Conclusões
Com base nas análises, foram tiradas conclusões sobre os fatores que mais influenciaram a sobrevivência dos passageiros.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Pandas**: Para manipulação e análise de dados.
- **Numpy**: Para operações numéricas e manipulação de arrays.
- **Matplotlib/Seaborn**: Para visualização de dados.
- **Jupyter Notebook**: Para desenvolvimento e documentação do código.

## Como Executar o Projeto

```bash
# Clone este repositório:
git fork https://github.com/seu-usuario/titanic-analysis.git

# Instale as dependências necessárias:
Anaconda, python e o Jupyter

# Abra o Jupyter Notebook:
jupyter notebook

# Execute o notebook Titanic_Analysis.ipynb para ver a análise completa.
```
Obs: Pode ser feito no Colab também

## Contribuições

Este projeto foi desenvolvido como parte de uma atividade de curso, mas contribuições são bem-vindas! Se você quiser sugerir melhorias ou adicionar novas análises, sinta-se à vontade.

