# transporte_sp
Dados do números de passageiros de ônibus da cidade de São Paulo

A Secretaria Municipal de Mobilidade e Trânsito disponibiliza os dados do número de passagereiros transportados diariamente, por meio de planilha de Excel
https://www.prefeitura.sp.gov.br/cidade/secretarias/mobilidade/institucional/sptrans/acesso_a_informacao/agenda/index.php?p=306932

Os dados são disponibilizados em links específicos (um link para cada planilha para cada dia do ano).

Além da disponibilização de 365 links, as planilhas parecem ter sido gerados por meio de uma macro, o que gera um tipo de _sugeira_/_resíduo_ dessa macro.

Por fim, uma terceira dificuldade é que o formato das planilhas se alteram ao longo do tempo. No caso desse código, feito para o ano de 2019 e 2020, algumas colunas foram suprimidas em um determinado momento de 2019. Por esse motivo, foram selecionadas apenas as seguintes colunas: data, tipo, area, empresa, linha, total de passageiros.


