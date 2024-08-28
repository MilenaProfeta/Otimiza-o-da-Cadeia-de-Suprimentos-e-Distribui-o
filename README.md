# Otimização da Cadeia de Suprimentos e Distribuição
## Cenário
Você é o gerente de logística de uma grande empresa de varejo que opera em várias regiões de um país. A empresa possui três centros de distribuição (CDs) localizados em diferentes cidades e precisa abastecer 10 lojas espalhadas em diversas regiões. Sua tarefa é otimizar o processo de suprimento e distribuição, considerando as seguintes informações:

## Centros de distribuição (CDs):
| Centro de distribuição | Quantidade (unidades) | Localização |
|------------------------|-----------------------|-------------|
| CD1                    | 150                   | A           |
| CD2                    | 200                   | B           |
| CD3                    | 300                   | C           |

## Lojas e Demanda
|Loja   |Demanda (Unidades)|Localização|
|-------|------------------|-----------|
|Loja 1 |150               |X          |
|Loja 2 |200               |Y          |
|Loja 3 |300               |Z          |
|Loja 4 |180               |W          |
|Loja 5 |250               |V          |
|Loja 6 |350               |U          |
|Loja 7 |220               |T          |
|Loja 8 |270               |S          |
|Loja 9 |190               |R          |
|Loja 10|160               |Q          |

## Custos de Transporte por Unidade (R$) entre CDs e Lojas:
|CD -> Loja|Distância (Km)|Custo por Unidade (R$)|
|----------|--------------|----------------------|
|CD1 -> X  |100           |5,00                  |
|CD1 -> Y  |150           |7,00                  |
|CD1 -> Z  |120           |6,00                  |
|CD2 -> W  |90            |4,50                  |
|CD2 -> V  |130           |6,00                  |
|CD2 -> U  |110           |5,50                  |
|CD3 -> T  |80            |4,00                  |
|CD3 -> S  |140           |6,50                  |
|CD3 -> R  |100           |5,00                  |
|CD3 -> Q  |160           |7,50                  |

## Restrições:
1. **Abastecimento único:** Cada loja só pode ser abastecida por um único CD.
2. **Capacidade dos CDs:** As capacidades dos CDs não podem ser ultrapassadas.
3. **Objetivo:** Minimizar o custo total de transporte.
