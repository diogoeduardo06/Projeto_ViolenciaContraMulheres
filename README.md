# **Análise Comparativa da Criminalidade Contra Mulheres nos Três Maiores Estados do Brasil (2022)**

## **Introdução**
Este trabalho apresenta uma comparação da criminalidade contra mulheres nos três estados mais populosos do Brasil em 2022: São Paulo (SP), Minas Gerais (MG) e Rio de Janeiro (RJ).

O objetivo principal foi analisar se a maior população feminina absoluta de um estado (SP) resultaria em uma taxa de criminalidade proporcionalmente maior. Para tal, foram utilizados dados públicos de ocorrências criminais (Sinesp) e projeções populacionais femininas (IBGE).

## **Hipótese**
O Estado de São Paulo, por apresentar maior parcela de mulheres em 2022, também apresentaria superioridade em taxa de criminalidade em comparação com Minas Gerais e Rio de Janeiro.

## **Metodologia e Ferramentas**
O projeto seguiu o fluxo padrão de Data Science, desde a coleta de dados brutos até a visualização e interpretação dos resultados.

### **Ferramentas**
- Python: Linguagem de programação central.

- pandas: Essencial para manipulação, limpeza e agregação dos bancos de dados.

- matplotlib e seaborn: Utilizadas para a geração dos gráficos de barras que ilustram a comparação absoluta e proporcional.

### **Metodologia**
- Filtragem Temporal e Geográfica: Seleção dos dados de ocorrências criminais para o ano de 2022 nos estados de SP, MG e RJ.
- Agregação por Vítimas: Soma das ocorrências onde as vítimas eram do sexo feminino (SP, MG, RJ).
- Coleta de População: Extração da população feminina em 2022 para cada UF (via IBGE).
- Cálculo da Taxa: Aplicação da fórmula para calcular a Taxa de Criminalidade por 100 mil mulheres.

Análise: Geração de gráficos e tabelas para averiguação e discussão dos resultados.

**Fórmula estatística**

Taxa por 100 Mil Mulheres = Ocorrências de Vítimas Femininas / População Feminina

## **Resultados e Discussão**

### **Análise de Vítimas Absolutas**

Ao analisar o número absoluto de vítimas femininas em 2022, a ordem de ocorrências foi a seguinte:
- São Paulo (SP): 428 ocorrências.
- Rio de Janeiro (RJ): 290 ocorrências.
- Minas Gerais (MG): 276 ocorrências.

  <img width="464" height="286" alt="image" src="https://github.com/user-attachments/assets/d58c5daf-b203-40fc-b1d9-c386d58c33b4" />

## **Taxa de Criminalidade Proporcional**
Ao realizar o cálculo da taxa por 100 mil mulheres, o cenário se inverteu, refutando a hipótese inicial:
- Rio de Janeiro (RJ): Taxa de 3.21 por 100 mil mulheres.
- Minas Gerais (MG): Taxa de 2.56 por 100 mil mulheres.
- São Paulo (SP): Taxa de 1.82 por 100 mil mulheres.

  <img width="424" height="239" alt="image" src="https://github.com/user-attachments/assets/aabe660f-9743-4ee6-b455-d7ee25052e5f" />

## **Conclusão**
**A hipótese inicial foi refutada.**

Apesar de São Paulo ter registrado a maior população feminina e o maior número absoluto de vítimas em 2022, foi o estado com a menor taxa de criminalidade relativa (1.82) entre os três comparados.

Isso nos leva à conclusão de que, ao considerar apenas os números absolutos, podemos chegar a análises equivocadas e distorcidas da realidade. É fundamental utilizar indicadores proporcionais para orientar a implementação de ações governamentais eficazes.

## **Agradecimentos**

Agradecemos à professora Aruane Mello Pineda pela orientação e incentivo, e à instituição SENAI Suíço-Brasileira Paulo Ernesto Torre pelo apoio e estrutura para a pesquisa.

# **II CONGRESSO INTERNACIONAL DE INOVAÇÃO E PESQUISA**

O artigo foi enviado para um congresso de tecnologia e pesquisa, no qual foi aceito. Mostrando assim a credibilidade e resultados de um ótimo trabalho feito.

<img width="937" height="657" alt="image" src="https://github.com/user-attachments/assets/e57807e6-cd26-41f9-839d-e52edf276b5b" />
