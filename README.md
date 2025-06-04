# 📊 Solução Inteligente para Otimização de Estoques e Processos de Manutenção
### Projeto de Extensão – TecMaqli LTDA
Este projeto foi desenvolvido como parte de uma atividade de extensão universitária em parceria com a empresa TecMaqli LTDA, especializada na manutenção de máquinas industriais voltadas para os segmentos de lavanderia e cozinha industrial.

### 🎯 Objetivo desenvolver uma solução analítica inteligente para:

Otimizar o estoque de peças de reposição.

Fornecer recomendações estratégicas baseadas em dados reais da operação da empresa.

### 🛠️ Tecnologias Utilizadas

Python (Pandas, Seaborn, Matplotlib, Scikit-learn)

Jupyter Notebook

PDF com gráficos e recomendações automatizadas

### 🗂️ Estrutura da Análise
1. analise_exploratoria()
Estatísticas descritivas das ordens de serviço e estoque.

Visualização dos tipos de defeito e tempo de reparo.

2. analise_fornecedores()
Mapeamento da quantidade de peças por fornecedor.

Estoque médio por fornecedor.

Gráficos de distribuição horizontal por fornecedor.

3. analise_pecas()
Peças mais utilizadas em reparos.

Custo médio por categoria de peça.

Identificação de risco de falta de estoque com base na demanda.

4. analise_correlacao_regressao()
Correlação entre variáveis como custo total, tempo de reparo e custo unitário.

Regressão linear para prever custos com base em variáveis operacionais.

5. gerar_recomendacoes_graficos_pdf()
Geração automática de um relatório visual em PDF contendo:

Peças sem estoque com alta demanda.

Fornecedores mais impactantes financeiramente.

Máquinas com maior custo e tempo de manutenção.

Peças mais utilizadas.

Tipos de defeito mais caros.

Relação estoque vs demanda com identificação de riscos.

### 📁 Saídas do Projeto
Recomendacoes_Gestores.pdf: Relatório gráfico automatizado com insights e recomendações.

Gráficos e tabelas analíticas para suporte à decisão.

### 👥 Equipe Envolvida
Colaboradores da TecMaqli LTDA

Aluno extensionista Marcos Vinicius responsável pelas análises e desenvolvimento

### 🧠 Conclusão
A solução implementada auxilia os gestores da TecMaqli a tomar decisões baseadas em dados reais sobre:

Compras de peças.

Seleção de fornecedores.

Prevenção de falhas recorrentes.

Controle financeiro e operacional.

Esse projeto é um passo importante para a transformação digital na manutenção industrial, com foco em eficiência, previsibilidade e redução de custos.


### Como Executar

1. Clone o repositório.
2. Instale as dependências com `pip install -r requirements.txt`.
3. Execute os notebooks ou scripts conforme necessário.
