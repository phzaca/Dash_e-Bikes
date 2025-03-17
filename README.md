# Projeto E-commerce de Bikes 🚲
# E-Bikes
Descrição do Projeto
Neste projeto, o objetivo foi analisar e manipular uma base de dados de uma loja de e-commerce no ramo de bicicletas. A base foi obtida no Google Datasets, e após uma análise inicial, optei por seguir com ela devido à sua boa organização.

A seguir, descrevo as etapas que segui para manipulação dos dados e criação do relatório interativo no Power BI.

Etapas do Projeto 
# 1. Importação e Manipulação dos Dados
Obtenção da base de dados: Encontrei a base no Google Datasets e decidi trabalhar com ela.
Exploração inicial: Abri a base no VS Code e estudei os dados.
Manipulação inicial:
Importe a biblioteca pandas e li a base de dados, criando o DataFrame (DF) chamado dados.
Realizei a exclusão de algumas colunas desnecessárias.
Verifiquei o dtype dos dados e percebi que não seria necessário realizar muitas manipulações.
Renomeei algumas colunas para maior clareza.
Ajustei as colunas referentes ao custo dos pedidos e lucro.
Usei o método .unique() para explorar os dados, principalmente para as bandeiras de países.
Por fim, salvei os dados manipulados como um arquivo CSV.

# 2. Excel - Relacionamento de Países e Bandeiras
Criei um arquivo no Excel que relacionava os nomes dos países com as URLs das bandeiras. Esse arquivo ajudou na visualização geográfica no Power BI.

# 3. Power BI: Criação do Relatório Interativo
Ao entrar no Power BI, segui com as seguintes etapas de análise e visualização:

-- Página 1: Relatório de Vendas e Lucros
Gráficos:
Linha do tempo para analisar a quantidade de vendas ao longo do tempo.
Gráfico de área que compara o investimento e o lucro.
Cartões com informações chave:
Investimento 
Revenda 
Lucro 
Lucro médio (%) 
Quantidade de vendas 
Gráfico de Rosca para comparar o gênero dos clientes (masculino e feminino).
Gráfico de Pizza para mostrar as faixas etárias dos clientes.
Botões de navegação entre as páginas.

-- Página 2: Exportações
Mapa interativo mostrando os países que compraram na loja .
Grid com as bandeiras dos países, conforme o arquivo Excel criado anteriormente.
Cartões com:
Lucro 
Porcentagem de lucro 
Quantidade de vendas 

-- Página 3: Produto
Árvore hierárquica interativa: Exibição das categorias, subcategorias e produtos. Conforme o usuário clica em um item, os gráficos se atualizam dinamicamente.
Gráficos:
Participação do lucro por meio de uma barra.
Valor do lucro das categorias, subcategorias ou produtos selecionados.
Cartões com:
Investimento 
Lucro 
Lucro médio (%) 
Quantidade de vendas 
Botões de navegação entre as páginas.

# 4. Design e Responsividade
Todas as páginas são interativas e responsivas ao clique.
Criei o fundo de cada página de forma simples usando o Paint .
Considerações Finais
Esse projeto me proporcionou uma experiência prática com manipulação de dados, análise exploratória e criação de relatórios interativos no Power BI. O uso de gráficos e dashboards facilitou a análise dos dados de vendas, investimentos e lucros da loja de e-commerce de bicicletas.

## Tecnologias Utilizadas 🛠️
Python (pandas)
Excel
Power BI
Paint (para o fundo simples)
