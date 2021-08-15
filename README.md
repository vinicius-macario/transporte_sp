## Número de passageiros de ônibus da cidade de São Paulo ##

A Secretaria Municipal de Mobilidade e Trânsito disponibiliza os dados do número de passagereiros transportados diariamente pelos ônibus, por meio de planilha de Excel
https://www.prefeitura.sp.gov.br/cidade/secretarias/mobilidade/institucional/sptrans/acesso_a_informacao/agenda/index.php?p=306932

Para consolidar os dados disponibilizados, temos três questões

**Um link para cada dia**

Os dados são disponibilizados em links específicos (um link para cada planilha para cada dia do ano). Portanto, somente para o ano de 2019, temos 365 links - um cada dia do ano. 

**Resído de macro**

As planilhas parecem ter sido gerados por meio de uma macro, o que gera um tipo de _sugeira/resíduo_ dessa macro. Isso dificultou um acesso mais simples via urblib, por exemplo. A única solução encontrada voi baixar o arquivo, abrir e salvar sem a macro.

**Alteração nas colunas**

Por fim, uma terceira dificuldade é que o formato das planilhas se alteram ao longo do tempo. No caso desse código, feito para o ano de 2019 e 2020, algumas colunas foram suprimidas em um determinado momento de 2019. Por esse motivo, foram selecionadas apenas as seguintes colunas: data, tipo, area, empresa, linha, total de passageiros. Em 2019, por exemplo, as seguintes colunas deixaram se ser disponibilizadas _Passageiros Pagtes Em Dinheiro, Passageiros Pagtes Bu Vt, Passageiros Pgts Bu Vt Mensal, Passageiros Pagtes Int M/Cptm_.


