# Modelo-Score-Futebol
Neste repositório, disponibilizo estudos sobre aplicação de machine learning no futebol.

### Estudo00 - Modelo de machine learning para previsão de rebaixamento do time na Série A
OBS: Os notebooks estão comentados em língua espanhola.

Atualmente, esse estudo contém três modelos - e três notebooks:

i) modelo geral, ii) modelo com escalonamento Standard Scaling e iii) modelo com escalonamento MinMax Scaling.

A ideia de desenvolvimento segue de um modelo bastante genérico, sem tratamento, para um cada vez mais tratado. Sendo assim, as três primeiras versões têm baixíssimo tratamento. Ainda assim os modelos apresentaram boa performance devido à natureza bastante uniforme dos times que são/não são rebaixados entre as edições de 2006 e 2023 do Brasileirão Séria A.

A versão 1 (geral) e 2 (Standard Scaling) se destacaram tanto em ganho de KS quanto em ganho de AUC.

Além dos estudos de desenvolvimento do modelo, há uma análise complementar acerca da ordenação da taxa de rebaixamento por faixa de probabilidade de rebaixamento.
