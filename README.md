# Personas_Kmeans 

Este projeto foi desenvolvido durante o último semestre do Curso de Ciência de Dados, como parte da disciplina de Aprendizagem de Máquina, ministrada pelo Professor Rogério. A parceria para o desenvolvimento do projeto foi estabelecida com meu colega de sala, Fernando.
Foi utilizado o algoritmo K-means, agrupamento K-Means é um algoritmo de aprendizagem não supervisionado usado para resolver problemas de agrupamento. Segue um procedimento simples de classificação de um determinado conjunto de dados em um número de clusters, definidos pelo parâmetro k. A Biblioteca GDS Neo4j conduz clustering com base nas propriedades do nó, com uma propriedade do nó da matriz flutuante sendo passada como entrada por meio do nodePropertyparâmetro. Os nós no gráfico são então posicionados como pontos em um despaço dimensional (onde dé o comprimento da propriedade da matriz).

## Base de dados 
(Dados Fictícios)

- A base de dados possui 10.127 linhas;
- Colunas: 
- 'CLIENTNUM': 'Número_cliente';
- 'Attrition_Flag': 'Indicador_atrito';
- 'Customer_Age': 'Idade';
- 'Gender': 'Gênero';
- 'Dependent_count': 'Quantidade_dependente';
- 'Education_Level': 'Nível_escolaridade';
- 'Marital_Status': 'Estado_civil';
- 'Income_Category': 'Categoria_renda';
- 'Card_Category': 'Categoria_cartão';
- 'Months_on_book': 'Tempo_Relacionamento';
- 'Total_Relationship_Count': 'Quantidade_total_relacionamento';
- 'Months_Inactive_12_mon': 'Meses_inativos_últimos_12_meses';
- 'Contacts_Count_12_mon': 'Quantidade_contatos_em_12_meses';
- 'Credit_Limit': 'Limite_crédito';
- 'Total_Revolving_Bal': 'Saldo_rotativo_total';
- 'Avg_Open_To_Buy': 'Média_abertura_para_compra';
- 'Total_Amt_Chng_Q4_Q1': 'Variação_Total_Montante_4º_para_1º_trimestre';
- 'Total_Trans_Amt': 'Valor_total_transações';
- 'Total_Trans_Ct': 'Quantidade_total_transações';
- 'Total_Ct_Chng_Q4_Q1': 'Variação_total_transações_4º_trimestre_para_1º_trimestre';
- 'Avg_Utilization_Ratio': 'Taxa_utilização_média'.

## Gráficos para Análise de dados 
### Matriz de Correlação:
![image](https://github.com/iancaabreu/Personas_Kmeans/assets/102169504/2edbdf67-51b7-409a-a065-685a2a735592)

### Escolha do K clusters Utilizando o Método Elbow:

  ![image](https://github.com/iancaabreu/Personas_Kmeans/assets/102169504/106943b7-c356-4755-9714-d1ee6e0b164c)

### Normalização das Variáveis:

![image](https://github.com/iancaabreu/Personas_Kmeans/assets/102169504/20227ab8-38ba-42b5-82cb-b0bc7c4d49fc)

### Make_spider dos clusters 

![image](https://github.com/iancaabreu/Personas_Kmeans/assets/102169504/cc234047-731e-4855-9802-5227c655d7fb)


 ## Resultado: Descrição das Personas
### Persona A: Ousado
Perfil de cliente com taxa de utilização e valor total de transações altas, porém com baixo limite de crédito. Estratégias para melhor atendê-lo podem incluir personalização de serviços dentro do escopo atual, oferecendo benefícios adicionais para incentivá-lo a explorar novas opções ou produtos e aumentar seu limite crédito e engajamento.
### Persona B: Moderado
Perfil de cliente com baixa taxa de utilização, valor total de transações alta e limite de crédito médio. Preferia operar dentro dos limites dos serviços essenciais, evitando taxas adicionais e mostrando moderação na exploração de novas oportunidades de compra. Para aumentar seu engajamento e taxa de utilização direcionar ofertas de produtos e serviços para diversificar sua carteira.
### Persona C: Engajado
Perfil de cliente engajado, com alto limite de crédito e valor total de transações. Isso sugere uma relação equilibrada e utilização restrita a poucos serviços ou produtos. Para otimizar as oportunidades de expansão de acordo com suas necessidades e objetivos financeiros deve-se ofertar serviços / produtos para diversificar sua utilização.
### Persona D: Arrojado
Perfil de cliente com taxa de utilização praticamente proporcional ao limite crédito e valor total de transações muito alto. Propenso a explorar novas oportunidades financeiras e alta a abertura para compra sugere uma disposição significativa para envolver-se mais profundamente com os serviços oferecidos pelo banco. Estratégias direcionadas para atender às suas necessidades emergentes é personalizar ofertas podem ser eficazes para promover uma relação duradoura.
