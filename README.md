# Resumo

Os estudos sobre séries temporais financeiras vem aumentando cada vez mais ao longo
dos anos principalmente com o uso de modelos de aprendizado de máquina para tentar
prever preços e movimentações para extrair ao máximo as oportunidades que surgem
nesse mercado. Há pouco tempo, uma nova classe de ativos foi criada e vem crescendo
exponencialmente nos últimos anos: criptomoedas. Esses ativos são moedas virtuais
que utilizam criptografia para manter a segurança das transações e tem como principal
representante o Bitcoin. Por serem relativamente jovens, comparadas ao mercado
tradicional como por exemplo commodities, ações, forex, existe uma volatilidade muito
grande no preço devido à adoção por pessoas e instituições de todo o mundo desses
ativos, mas que podem ser analisados da mesma forma. Neste trabalho, é proposto
um modelo de rede neural de classificação utilizando células LSTM para predição da
tendência no preço do Bitcoin utilizando como base de dados os valores do candlestick
semanal junto com o volume de transação. São testadas configurações diferentes para o
modelo, variando-se separadamente timesteps, epochs e a utilização de dados adicionais
da macroeconomia. Após encontrar a configuração que obtém os melhores resultados de
retorno de investimento e acurácia, o modelo é comparado a estratégias de negociação
simples.
