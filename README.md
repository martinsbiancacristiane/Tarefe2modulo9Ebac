# Tarefe2modulo9Ebac
Análise da Idade Média Materna por Região Imediata (RO, 2019)
📝 Descrição Geral
Este projeto realiza uma análise de agregação e visualização de dados utilizando o dataset do Sistema de Informações sobre Nascidos Vivos (SINASC) referente ao estado de Rondônia (RO) no ano de 2019. 
O objetivo  é investigar a variação da Idade Média das Mães ao longo do tempo e compará-la entre as diferentes Regiões Imediatas do estado.
O projeto demonstra o uso de:
Carregamento e limpeza de dados (pandas).
Correção de tipos de dados (Datas).
Mapeamento de dados categóricos para criar novas dimensões de análise (municípios para Regiões Imediatas).
Agrupamento de dados (groupby) e criação de tabelas dinâmicas (unstack) para análise temporal.
Visualização de dados (Gráfico de Linhas).

⚙️ Metodologia e Ferramentas
Categoria
DetalhesFonte de DadosSistema de Informações sobre Nascidos Vivos (SINASC) - Dados de Rondônia, 2019.
FerramentasPython, Pandas, Matplotlib/Seaborn.
AgregaçãoMédia da variável IDADEMAE.
DimensõesMês/Ano (MESANO) e Região Imediata (RegiaoImediata).
VisualizaçãoGráfico de linhas para plotar a série temporal da idade média.

📈 Resultado Principa 
Gráfico de Linhas que permite a comparação da tendência da idade média das mães ao longo do ano de 2019 em Rondônia.
Observou-se que a Região Imediata de Porto Velho consistentemente apresentou a maior idade média materna ao longo do ano, enquanto as regiões do interior mostraram médias ligeiramente menores e maior volatilidade. 
Isso sugere uma possível correlação entre o nível de desenvolvimento e urbanização da região e a idade em que as mulheres se tornam mães.
