# TCC

Nas últimas décadas, diversos avanços tecnológicos e incentivos voltados à pesquisa cientí-
fica vêm fazendo com que o Brasil obtenha destaque internacional no âmbito da produção
agrícola frente ao aumento da demanda global por alimentos. Apesar disso, verifica-se
ainda significativa negligência em relação à importância das comunidades microbianas,
seja por falta de informação ou pela subestimação de seu papel crucial no processo, o
que resulta em práticas de manejo que não conseguem explorar plenamente a capacidade
produtiva do solo. Para mudar esse cenário, uma abordagem promissora se dá através
do uso de técnicas avançadas de biotecnologia, tal como o sequenciamento metagenômico
de amostras de solo. Análises desses dados oriundos do sequenciamento podem revelar
informações valiosas sobre os microrganismos presentes na amostra, permitindo assim
uma gestão mais eficiente e sustentável dos solos agrícolas. Nesse contexto, busca-se aqui
conduzir análises de dados de metagenômica obtidos de amostras de solo, utilizando-se de
dados (brutos) sequenciados disponibilizados publicamente por Ordine et al. (2023). Es-
pecificamente, tem-se por objetivo i) caracterizar o perfil (taxonômico) das comunidades
microbianas, evidenciando a diversidade e a abundância de microrganismos; ii) identificar
o perfil do resistoma e do viruloma, focando na abundância e diversidade dos genes de
resistência a antibióticos (ARGs) e de fatores de virulência (VFs); bem como iii) clarifi-
car as diferenças observadas nas amostras de solo analisadas, levando em consideração as
características de cada amostra. Para tal, diferentes ferramentas de bioinformática são
aplicadas em sequência a fim de produzir pipelines capazes de realizar a análise de dados
de forma não assistida. Em particular, duas pipelines são implementadas aqui utilizando
linguagem GNU Bash, sendo uma delas destinada à classificação taxonômica e a outra para
a caracterização de genes de resistência a antibióticos (ARGs) e de fatores de virulência
(VFs). Como resultado da execução dessas pipelines, gêneros importantes para a saúde
do solo e das plantas foram identificados, tais como Bradyrhizobium, Nocardioides e Pseu-
domonas. Por sua vez, com respeito dos ARGs, genes relevantes como vanRO, rsmA e
RbpA foram identificados. Ainda, no contexto de VFs, a presença de genes como acpXL,
hsiB1 e pilG foram observados nas amostras analisadas. Portanto, os resultados obti-
dos ratificam a validade das pipelines implementadas tanto no que tange à classificação
taxonômica quanto à caracterização do resistoma e do viruloma.
