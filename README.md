# desafio-triggo
Desafio de dados com análise, SQL, machine learning e dashboards
# 📦 Análise de Vendas e Logística do Marketplace

Este projeto tem como objetivo analisar dados de um marketplace para entender padrões de vendas, logística e satisfação do cliente. Realizei uma série de análises exploratórias e criei dashboards interativos para facilitar a visualização dos principais insights.

---

📈 Principais Análises Realizadas

A) Volume de Pedidos por Mês
Tendência clara de crescimento nas vendas ao longo do tempo.

Picos entre novembro e dezembro, indicando sazonalidade (Black Friday e festas de fim de ano).

Meses de janeiro e fevereiro com volume menor de vendas, típico do varejo.

💡 Insight: ajuda no planejamento de estoque e campanhas promocionais em períodos de alta demanda.

B) Tempo de Entrega dos Pedidos
Maioria dos pedidos entregue entre 8 a 10 dias.

Distribuição com assimetria positiva, revelando casos com atrasos logísticos.

Pico de densidade bem definido, mas com presença de outliers (pedidos acima de 20 dias).

🔎 Insight: investigar outliers para aprimorar a eficiência logística.

C) Análise Geográfica e de Valor Médio dos Pedidos
Junção de dados de pedidos, itens e clientes para calcular o ticket médio por estado.

Identificação de estados com maior valor médio para estratégias de marketing direcionadas.

Visualização com boxplots e curvas KDE para entender distribuição de distâncias e valores.

🌎 Insight: otimização de rotas e campanhas personalizadas por região.

D) Modelo de Regressão Linear - Avaliação do Cliente
Avaliação da influência de variáveis como tempo de entrega e categoria nos reviews.

Resultados:

MSE = 2.1989

R² = 0.0518 (modelo explica apenas 5,2% da variação das notas)

📉 Conclusão: modelo pode ser aprimorado com variáveis mais significativas, mas já oferece direções úteis (ex: cds_dvds_musicais com notas altas, dvds_blu_ray com notas baixas).

📊 Dashboards Criados
Dashboard Geral de Vendas

Evolução das vendas ao longo do tempo.

Filtros por estado e categoria.

Mapa de Calor

Concentração de vendas por estado/região do Brasil.

Relação entre Avaliação e Tempo de Entrega

Gráficos para correlacionar atrasos com avaliações.

Dashboard de Vendedores

Performance por vendedor: volume de vendas, satisfação e tempo médio de entrega.

✅ Conclusão
Esse projeto me permitiu aplicar técnicas de análise exploratória de dados, visualização e modelagem estatística para extrair insights acionáveis para o negócio. Os dashboards são ferramentas valiosas para a equipe de operações, logística e marketing, ajudando na tomada de decisão baseada em dados.

💻 Tecnologias Utilizadas
Python (Pandas, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

Plotly / Dash

Google Colab

Power BI (opcional)
