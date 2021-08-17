## Número de passageiros de ônibus da cidade de São Paulo ##

A Secretaria Municipal de Mobilidade e Trânsito disponibiliza os dados do número de passagereiros transportados diariamente pelos ônibus, por meio de planilhas de Excel.
As planilhas são disponibilizadas nessa página:
https://www.prefeitura.sp.gov.br/cidade/secretarias/mobilidade/institucional/sptrans/acesso_a_informacao/agenda/index.php?p=306932

Para acessar os dados foi feita uma raspagem, o notebook *raspagem_dados* disponibilizado pode ser utilizado para outros anos também, mas adaptações podem ser necessárias.

Considerar três questões:

**Um link para cada dia**. Os dados são disponibilizados em links específicos (um link para cada planilha para cada dia do ano). Portanto, somente para o ano de 2019, temos 365 links. 

**Resíduo de macro**. As planilhas parecem ter sido gerados por meio de uma macro, o que gera um tipo de _sugeira/resíduo_ dessa macro. Isso dificultou um acesso mais simples via urblib, por exemplo. A única solução encontrada voi baixar o arquivo, abrir e salvar sem a macro.

**Alteração nas colunas**. O formato das planilhas se altera ao longo do tempo. No caso desse código, feito para o ano de 2019 e 2020, algumas colunas foram suprimidas em um determinado momento de 2019. Por esse motivo, foram selecionadas apenas as seguintes colunas: data, tipo, area, empresa, linha, total de passageiros. Em 2019, por exemplo, as seguintes colunas deixaram se ser disponibilizadas _Passageiros Pagtes Em Dinheiro, Passageiros Pagtes Bu Vt, Passageiros Pgts Bu Vt Mensal, Passageiros Pagtes Int M/Cptm_.

### Comparando 2019 e 2020 ###

No gráfico abaixo temos a soma acumulada de 7 dias, para os anos de 2019, 2020, 2021 (16/ago).

![image](https://user-images.githubusercontent.com/64567327/129646030-d9428e91-3d69-4b33-b530-b3025b41eae9.png)





