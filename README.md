# Análise de Tendências de Vendas com Power BI 📊

Este repositório abriga um projeto que explora dados da Olist, uma plataforma que conecta vendedores a importantes marketplaces no Brasil. A finalidade deste trabalho é importar, tratar e analisar quatro bases de dados distintas utilizando o Power Query dentro do Power BI, com o objetivo de oferecer insights significativos sobre vendas e comportamento dos consumidores.

### Estruturas de Dados Importadas
As seguintes bases de dados foram incluídas no projeto:

1. **Pedidos (xlsx)**: Concentra informações sobre todos os pedidos realizados.
2. **Itens de Pedidos (csv)**: Detalha os itens específicos de cada pedido.
3. **Pagamentos (xml)**: Apresenta informações sobre os pagamentos efetuados.
4. **Produtos (json)**: Oferece detalhes sobre os produtos vendidos.

### Processo de Importação dos Dados

**Pedidos (xlsx)**  
- Acesse a guia "Página Inicial" no Power BI.
- Clique em "Obter Dados" e escolha "De Pasta de Trabalho".
- Encontre o arquivo de pedidos e selecione-o.
- Selecione a planilha com os dados e clique em "Carregar".

**Itens de Pedidos (csv)**  
- Clique em "Obter Dados" e escolha "Arquivo &gt; Texto/CSV".
- Localize o arquivo de itens de pedidos e importe os dados.

**Pagamentos (xml)**  
- Vá para "Obter Dados" e selecione "Arquivo &gt; XML".
- Carregue o arquivo de pagamentos, observando sua estrutura.

**Produtos (json)**  
- Clique em "Obter Dados" e selecione "Arquivo &gt; JSON".
- Carregue o arquivo de produtos e revise sua estrutura.

### Tratamento de Dados no Power Query
Durante o tratamento dos dados, utilizei diversas funcionalidades do Power Query, incluindo:

- **Coluna de Exemplo**: Empregada para limpar a coluna "Tipo de Pagamentos", removendo duplicatas e substituindo valores inadequados.
- **Remover Linhas**: Aprendi a excluir linhas indesejadas através da função "Remover linhas superiores".
- **Promover Cabeçalho**: Utilize a opção "Usar primeira linha como cabeçalho".
- **Extração de Texto**: Extraí informações usando delimitadores específicos nas colunas.
- **Mesclagem de Consultas**: Combinei consultas para relacionar dados entre diferentes tabelas.
- **Substituição de Valores**: A ferramenta "Substituir Valores" foi útil para realizar alterações na coluna "Payment Type".

### Manipulação Avançada
Aprofundei em técnicas como Coluna Personalizada e na criação de parâmetros via "Gerenciar Parâmetros" no Power Query. Aprendi também a resolver problemas relacionados à tipagem automática, definindo manualmente os tipos de dados. Renomeei colunas e otimizei as etapas aplicadas pelo Editor Avançado, melhorando a performance ao eliminar etapas desnecessárias e unificando processos.

### Modelagem de Dados
A modelagem de dados se revelou crucial para transformar essas informações brutas em insights valiosos. Consegui integrar várias fontes de dados e construir dashboards interativos que destacam o desempenho das vendas.

### Criação de Dashboard
O projeto inclui um dashboard com três visualizações:

- **Gráfico de Tabela**: Mostra o tipo de pagamento em relação à contagem de IDs de pedidos.
- **Gráfico de Barras Empilhadas**: Apresenta a soma de valores por nome de categoria.
- **Gráfico de Colunas Clusterizado**: Exibe a soma de valores por tipo de pagamento.

Esses gráficos proporcionam uma visualização clara e intuitiva dos dados, facilitando análises e decisões estratégicas.

### Conclusão
Este projeto exemplifica como ferramentas como Power BI e Power Query podem ser utilizadas para converter dados brutos em informações acionáveis. Espero que este repositório seja útil para aqueles que desejam aprofundar seus conhecimentos em análise de dados e modelagem no Power BI!

Sinta-se à vontade para explorar e adaptar as técnicas apresentadas aqui em seus próprios projetos!
