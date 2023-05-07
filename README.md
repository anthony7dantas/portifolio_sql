# Consultas SQL para Comércio de Vendas

![sql](https://user-images.githubusercontent.com/132700172/236702980-aaab0ee1-aef1-4ebf-9515-f780b8f73d22.png)




# Objetivo
O objetivo deste projeto é demonstrar a importância da otimização de consultas SQL para um banco de dados de comércio de vendas. Serão utilizados dados reais de uma empresa fictícia para exemplificar a aplicação de técnicas de otimização de consultas SQL com o uso de Procedures e CTE (Common Table Expressions)

Após a conclusão da exploração dos dados, as consultas foram usadas para criar um dashboard no PowerBI para melhor visualização dos dados.

# Dados Analisados

Os dados analisados são provenientes de uma empresa fictícia de comércio de vendas de eletrônicos. A empresa possui diversas filiais distribuídas por todo o país e faz uso de um banco de dados MySQL para armazenar informações sobre seus clientes, vendas e estoque.




# Softwares utilizados
- MySQL
- Microsoft Excel
- PowerBI
- Metodologias Ageis

# Consultas


Consulta 1: Vendas por Produto e Mês
A primeira consulta busca retornar as vendas de cada produto por mês, com o objetivo de identificar o comportamento de vendas ao longo do ano.

# Consulta original

![consulta 1](https://user-images.githubusercontent.com/132700172/236701420-372d7902-a20f-42c0-a0d6-be186dddb6b2.png)

# Consulta otimizada

![consulta op 1](https://user-images.githubusercontent.com/132700172/236701436-b610dd18-d9b9-4535-872e-21ee8dc41484.png)

Consulta 2: Estados que Mais Venderam
A segunda consulta busca retornar os estados que mais venderam, com o objetivo de identificar quais regiões estão gerando mais receita para a empresa.

# Consulta original

![consulta 2](https://user-images.githubusercontent.com/132700172/236701453-23e39a65-d0cd-4aae-b7d7-a2087ecf1f0f.png)

# Consulta otimizada

![consulta op 2](https://user-images.githubusercontent.com/132700172/236701460-e277afe5-8a5f-45cd-9747-b4f05e6177af.png)

# Dashboard

![1677203034833](https://user-images.githubusercontent.com/132700172/236701479-148ebaaf-9f9e-471f-968c-eb80454bd6d8.jpeg)


# Conclusões
Após realizar as otimizações nas consultas SQL, foi possível observar uma significante melhora no tempo de resposta e na performance do banco de dados. A utilização de técnicas como a criação de índices, o uso de procedures e a utilização de CTEs permitiram que as consultas fossem executadas de maneira mais eficiente, reduzindo a quantidade de tempo necessária para retornar os resultados esperados.

Com a otimização das consultas, foi possível identificar os principais estados que mais vendem, bem como os produtos mais populares, permitindo uma melhor tomada de decisão por parte da empresa. Além disso, o cálculo do ticket médio também foi aprimorado, fornecendo uma informação importante para a análise de desempenho do negócio.

# Recomendações ao tomador de decisão
Com base nos resultados obtidos após a otimização das consultas, é importante destacar a importância de investir em técnicas de otimização de consultas SQL. Ao utilizar essas técnicas, é possível melhorar a performance do banco de dados e reduzir o tempo necessário para a execução das consultas, permitindo uma melhor análise dos dados e uma tomada de decisão mais eficiente.

Além disso, é importante destacar a importância da utilização de ferramentas de análise de dados, como o PowerBI. Essas ferramentas permitem a criação de dashboards interativos, que facilitam a visualização dos dados e permitem uma análise mais profunda do desempenho da empresa.

Por fim, é importante ressaltar a importância da adoção de metodologias ágeis no desenvolvimento de projetos de análise de dados. A utilização de metodologias ágeis permite uma melhor gestão do projeto e uma maior flexibilidade na adaptação às mudanças do mercado, permitindo uma tomada de decisão mais rápida e eficiente.
