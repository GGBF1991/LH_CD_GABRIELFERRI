# Desafio Indicium Lighthouse

### Gabriel Ferri


#  <strong>Descrição do Projeto</strong>
Este projeto é parte do Desafio proposto pela Indicium. O objetivo é realizar uma análise detalhada de um banco de dados cinematográfico e aplicar técnicas de análise exploratória de dados (EDA) e criação de um modelo de machine learning para prever a nota do IMDb de filmes com base em suas características.
</font>

## Arquivos no Repositório

- **LH_CD_GABRIELFERRI.ipynb:** Notebook contendo o EDA e os modelos desenvolvidos.
- **requirements.txt:** Arquivo contendo as dependências do projeto.
- **model.pkl:** Modelo treinado salvo no formato pickle.
- **pipeline.pkl:** Pipeline de pré-processamento salvo no formato pickle.
- **genre_multilabel_binarizer.pkl:** Codificador de rótulos binários para gêneros de filmes, salvo no formato pickle.
- **desafio_indicium_imdb.csv:** Arquivo CSV contendo os dados para o desafio.
- **[Lighthouse] Desafio Ciência de Dados 2024-9.docx:** Documento Word com o desafio detalhado.

## Instalação e Execução

Para executar este projeto localmente, siga estas instruções:

<font size="4">
 
1. **Clone o repositório:**

   ```bash
   git clone https://github.com/GGBF1991/LH_CD_GABRIELFERRI.git
   cd LH_CD_GABRIELFERRI

2. **Crie e ative o ambiente:**

   Recomenda-se utilizar um ambiente virtual Python (conda).

   ```bash
   conda create --name lh_cd_gabrielferri python=3.8
   conda activate lh_cd_gabrielferri
   ```

3. **Instale as dependências:**

   ```bash
   pip install -r requirements.txt
   ```
<font size="4">

## Dados e Dicionário

A base de dados de treinamento contém 15 colunas com informações sobre filmes:

| Coluna          | Descrição                                     |
|-----------------|-----------------------------------------------|
| Series_Title    | Nome do filme                                  |
| Released_Year   | Ano de lançamento                              |
| Certificate     | Classificação etária                           |
| Runtime         | Tempo de duração                               |
| Genre           | Gênero                                         |
| IMDB_Rating     | Nota do IMDB                                   |
| Overview        | Overview do filme                              |
| Meta_score      | Média ponderada de todas as críticas           |
| Director        | Diretor                                        |
| Star1           | Ator/atriz #1                                  |
| Star2           | Ator/atriz #2                                  |
| Star3           | Ator/atriz #3                                  |
| Star4           | Ator/atriz #4                                  |
| No_of_Votes     | Número de votos                                |
| Gross           | Faturamento                                    |

<font size="4">

### Contato


E-mail: engenhariaferri@gmail.com

LinkedIn: https://www.linkedin.com/in/gabrielferrimachinelearning/
```
