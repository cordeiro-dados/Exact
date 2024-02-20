- Você recebeu um conjunto de dados de clientes da nossa empresa, mas
ele está repleto de valores ausentes e inconsistências. Como você abordaria
esse problema? Descreva pelo menos três técnicas de limpeza e
pré-processamento de dados que você poderia aplicar e explique quando
cada uma delas seria apropriada.

```
Existem algumas formas de lidar com problema:
1- Detecção de incostitências
    ** Realizar uma análise descritiva
        -Identificando valores discrepantes (outliers) por meio de medidas, como médias, mediana, desvio padrão, quartis.
        -Detectar valores inconsistentes, como datas impossíveis ou negativos em variávei que possuem valores absolutos.
    ** Visualização de Dados
        Usando de Histogramas, boxplot, scatterplot para identificar outliers, valores inconsistentes e correlações entre variáveis.
    ** Verificar Consistência Interna
        Buscar por valores incosisntentes em reação a outras variáveis do conjunto de dados, como idade que não bate com a data de nascimento.
    ** KNN
        Imputa valores ausentes com base em k vizinhos mais próximos no espaço de característica, adequando para variáveis categóicas e numéricas, especialmente quando a distribuição é muito complexa.
    ** Divisão do Conjunto de Dados
        Treino 70-80, utilizado para treinar o modelo
```