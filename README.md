Análise de Preços de Aluguéis em São Paulo

Introdução:

Este relatório apresenta uma análise completa dos preços de aluguéis em São Paulo, utilizando Python e a biblioteca Pandas. A análise visa identificar tendências e modelar uma relação entre as variáveis do conjunto de dados através da regressão linear.

Conjunto de Dados:

O conjunto de dados utilizado contém informações sobre aluguéis em São Paulo, incluindo:

address: Endereço do imóvel district: Distrito em que o imóvel está localizado area: Área do imóvel em m² bedrooms: Número de quartos garage: Número de vagas na garagem type: Tipo de imóvel (Studio e kitnet, Apartamento, Casa em condomínio, Casa) rent: Valor do aluguel total: Valor total do imóvel

Análise Descritiva:

A análise descritiva dos dados revela algumas tendências importantes:

Número de Quartos: Existe uma correlação positiva entre o número de quartos e o valor do aluguel, o que indica que imóveis com mais quartos tendem a ter aluguéis mais altos. Garagem: A presença de garagem também está positivamente correlacionada com o valor do aluguel, sugerindo que imóveis com garagem são mais caros. Valor Total: O valor total do imóvel também está positivamente correlacionado com o valor do aluguel, o que é esperado, pois imóveis mais caros tendem a ter aluguéis mais altos. Tipo de Imóvel: Casas em condomínios têm o maior aluguel médio, seguidos por apartamentos, casas e studios e kitinets.

Modelagem de Regressão Linear:

Um modelo de regressão linear foi ajustado aos dados para prever o valor do aluguel com base no número de quartos, a presença de garagem e o valor total do imóvel. O modelo teve um erro quadrático médio (RMSE) de [inserir valor] e um coeficiente de determinação (R²) de [inserir valor]. O R² indica que [inserir porcentagem] da variância do valor do aluguel é explicada pelas variáveis independentes.

Visualização dos Dados:

Gráficos de dispersão e de barras foram criados para visualizar os dados e as relações entre as variáveis. O gráfico de dispersão mostra uma tendência de aumento no aluguel com o número de quartos. O gráfico de barras mostra que casas em condomínios têm o maior aluguel médio.

Conclusões:

A análise de preços de aluguéis em São Paulo indica que o número de quartos, a presença de garagem e o valor total do imóvel são variáveis importantes para prever o valor do aluguel. No entanto, o modelo de regressão linear ajustado não é perfeito, e outros fatores podem influenciar o preço do aluguel. Para melhorar o modelo, seria interessante incluir mais variáveis no conjunto de dados, como o tamanho do imóvel, a localização, o ano de construção e as comodidades.
