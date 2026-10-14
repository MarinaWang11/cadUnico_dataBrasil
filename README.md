# Análise Socioeconômica do Cadastro Único (CadÚnico 2018)

Repositório desenvolvido para a atividade prática de processamento de microdados do Cadastro Único, simulando um teste técnico de Trainee em Análise de Dados para a consultoria **DataBrasil Analytics** (Disciplina: Tecnologias para Data Science).

## 📋 Sobre o Projeto
O objetivo deste projeto é realizar a Análise Exploratória de Dados (AED) utilizando os microdados da base "Pessoa" do CadÚnico de 2018. O trabalho aborda o mapeamento demográfico, condições do mercado de trabalho, vulnerabilidade de Pessoas com Deficiência (PCD), desigualdade de renda e uma proposta de enriquecimento de dados com bases públicas municipais (IDEB e PIB Municipal).

## 🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em **Python** utilizando as seguintes bibliotecas[cite: 2, 8]:
* **Pandas** e **PySpark**: Manipulação e processamento de grandes massas de dados.
* **Matplotlib** e **Seaborn**: Geração de visualizações gráficas e gráficos estatísticos.
* **Jupyter Notebook**: Ambiente interativo de desenvolvimento.

## 🚀 Como Executar o Projeto
1. Clone este repositório para a sua máquina:
   ```bash
   git clone [https://github.com/MarinaWang11/cadUnico_dataBrasil.git](https://github.com/MarinaWang11/cadUnico_dataBrasil.git)

```

2. Certifique-se de ter o Python e o Java (JDK) instalados, e crie um ambiente virtual com o Conda:


```bash
conda create -n propagacao python=3.12 -y
conda activate propagacao

```


3. Instale as dependências necessárias:
```bash
conda install -c conda-forge pyspark pandas seaborn matplotlib jupyter notebook openjdk=11 -y

```


4. Baixe o arquivo de microdados (`PESSOA_2018.TXT`) disponibilizado pelo Ministério do Desenvolvimento Social e coloque-o na raiz da pasta do projeto.


5. Abra o VS Code, selecione o kernel correspondente ao seu ambiente e execute o arquivo `.ipynb` célula por célula.



## 📊 Principais Etapas Desenvolvidas

* **Etapa 1:** Análise demográfica (distribuição de idade por sexo e cor/raça), taxa de ocupação em idade ativa (18 a 65 anos) e renda média por nível de escolaridade.


* **Etapa 2:** Avaliação da proporção de trabalho remunerado por faixas etárias e mapeamento da vulnerabilidade de Pessoas com Deficiência (PCD) frente à extrema pobreza.


* **Etapa 3:** Proposta arquitetural de enriquecimento de dados unindo o CadÚnico a indicadores municipais (IDEB e PIB Municipal) via chave geográfica do IBGE.


* **Análises Específicas:** Interseccionalidade de renda (gênero x cor/raça), relação entre escolaridade e trabalho, e o impacto da presença de crianças de 0 a 6 anos na ocupação de mães responsáveis.



## **Autora:** [Marina Rihs Matos Wang](https://github.com/MarinaWang11)
