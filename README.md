<div align=center>
<img width="18%" height="auto" src="https://static.wixstatic.com/media/efe4c3_d4c9a129e6264a75bbcc9f54ec63bd45~mv2.png/v1/fill/w_181,h_88,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/Dataside%20-%20Monocromatico.png"/>
  </div> 
 <br><br>

<div align=center>
    <h1> Desafio Dataside
  </div>  



<h4 align="left">
 Neste desafio, desenvolvi um notebook que será responsável por extrair dados de previsão do tempo das cidades do Vale do Paraíba, região onde se localiza a Dataside.
 Com esses dados usando Pyspark, gerei um data frame com os dados de previsão adquiridos pela API <a href="https://hgbrasil.com/status/weather"><strong>Hg Weather »</strong></a>
 e a partir dele uma temp view. Por fim exportei a tabela em csv usando Pandas.</h4>

```
Este projeto consiste em:
1 - Consultar municípios do Vale do Paraíba, gerar um data frame e criar uma temp view com esses dados.
2 - Consultar dados do tempo para cada município, gerar um data frame e criar uma outra temp view.
3 - Utilizar Spark SQL para gerar os data frames da Tabelas 1.
4 - Exportar o data frame para CSV.
```
## Tenologias usadas

- Python
- PySpark
- Pandas
- API IBGE
- API Hg Weathers
- Biblioteca Requests, Datetime, Time , pyspark.sql, Json, Itertools e  pyspark.sql.window.


## Exemplo de saida do csv:
<div style="display: inline_block">
     <img align="center" alt="Alexandre-Exemplo" src="https://user-images.githubusercontent.com/89695635/211845813-104f49d9-48ce-4aaa-900f-21aaf9bb4368.png">
</div>

##

<div align="center" style"display: inline_block"><br>
  <img align"center" alt="Alexandre-Python" height=60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" /> 
  <img align"center" alt="Alexandre-Pandas" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original-wordmark.svg" />
  <img align"center" alt="Alexandre-Spark" height="50" width="100" src="https://spark.apache.org/docs/latest/api/python/_static/spark-logo-reverse.png" />
  <img align"center" alt="Alexandre-HgWeathers" height="40" width="15%" src="https://hgbrasil.com/assets/hg-br-logo-29abe59800e509879c6b79ff8861370119567f923c815595f7d19dff4986d786.png"/>
  <img align"center" alt="Alexandre-IBGE" height="40" width="100" src="https://user-images.githubusercontent.com/89695635/211843449-3becff14-11c0-407d-84dc-a676cfce0804.png" />
</div>
<br>
