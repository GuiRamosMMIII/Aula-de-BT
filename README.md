Olá, bom dia a todos. Nós somos o grupo responsável pelo desenvolvimento de um projeto de previsão de vendas com uso de machine learning. Hoje, vamos apresentar a empresa fictícia BellaBox, os desafios enfrentados e a solução tecnológica que construímos para apoiar sua tomada de decisão.

A BellaBox é uma startup brasileira fundada em 2020 que atua no setor de cosméticos e autocuidado. Seu principal modelo de negócios é a assinatura mensal de kits de beleza personalizados, que são entregues diretamente na casa das clientes. A empresa opera totalmente online, com foco em jovens mulheres urbanas, especialmente entre 18 e 35 anos, que buscam praticidade, novidade e bem-estar.

Desde o início, a BellaBox se destacou por oferecer um serviço flexível, com planos que permitem personalizar os produtos recebidos com base no perfil da cliente. Em poucos anos, a empresa já conta com mais de 50 mil assinantes em todo o Brasil, sendo reconhecida por sua forte presença nas redes sociais e campanhas de marketing de influência.

Apesar do crescimento acelerado, a BellaBox começou a enfrentar um problema crítico: a imprevisibilidade nas vendas. Por depender muito de campanhas sazonais, marketing digital e variações de comportamento do consumidor, a empresa tinha dificuldade para antecipar a demanda mensal. Isso impactava diretamente o planejamento de estoque, logística de distribuição e até a experiência do cliente, gerando atrasos e desperdícios.

Foi a partir desse desafio que surgiu o objetivo do nosso projeto: criar um modelo de machine learning para prever as vendas da BellaBox com maior precisão, auxiliando o time de operações e marketing a se planejar com mais inteligência.

Para isso, utilizamos um conjunto de dados contendo as vendas diárias da empresa ao longo de três meses, com informações como data, dia da semana, mês, e se havia promoção ativa. Também calculamos variáveis derivadas, como o comportamento médio por dia da semana, que ajudaram a enriquecer a análise.

Durante a fase de exploração dos dados, identificamos padrões interessantes. Por exemplo, as vendas costumavam subir significativamente às sextas-feiras e aos domingos. Além disso, dias com promoção mostraram um aumento médio de 15% nas vendas. Utilizamos gráficos interativos para visualizar essas tendências, incluindo um gráfico 3D que mostra como dia da semana, presença de promoção e volume de vendas se relacionam.

Com os dados prontos, aplicamos um modelo de Random Forest Regressor, conhecido por sua robustez e capacidade de lidar com variáveis categóricas e contínuas. Após treinar o modelo e avaliar seu desempenho, obtivemos um erro médio (RMSE) bastante satisfatório, o que demonstra que o modelo é confiável para prever vendas com base em padrões históricos.

A partir disso, geramos previsões que mostram, por exemplo, quais dias da semana tendem a ter maior volume de vendas, e como uma promoção específica pode impactar esse número. Essas informações podem ser usadas pela BellaBox para planejar com antecedência a quantidade de kits que devem ser preparados, otimizar a logística e até agendar as campanhas publicitárias nos momentos de maior impacto.

Com o uso contínuo desse modelo e a inclusão de mais dados no futuro, como clima, feriados ou até engajamento em redes sociais, a BellaBox poderá transformar sua tomada de decisão em algo muito mais analítico, automatizado e eficiente.

Encerramos aqui nossa apresentação. Esperamos que tenham gostado da solução e que ela mostre como a tecnologia pode ser aplicada de forma prática e estratégica para resolver problemas reais de negócio. Muito obrigado!

