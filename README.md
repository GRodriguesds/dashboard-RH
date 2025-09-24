# Gestão de Colaboradores com Power BI

Este projeto consiste em um **dashboard interativo** desenvolvido no **Power BI** para análise e acompanhamento de colaboradores da empresa.  
Com ele é possível monitorar indicadores como **média salarial, estado civil, tempo médio na empresa, avaliação média por área e distribuição de gênero**, facilitando a tomada de decisões estratégicas pelo RH.

---
## Tecnologias Utilizadas
- **Power BI Desktop** — construção do dashboard e criação de medidas em DAX  
- **DAX (Data Analysis Expressions)** — criação de métricas e cálculos dinâmicos  
- **Power Query** — limpeza, transformação e modelagem de dados  
- **Excel** — base de dados utilizada para alimentar o dashboard  

---
## Processo de Construção
1. **Coleta e Importação de Dados**  
   - Importação de um arquivo Excel com informações de funcionários (área, cargo, salário, tempo de empresa, avaliação, estado civil e sexo).  
2. **Tratamento no Power Query**  
   - Ajuste de tipos de dados (datas, números, texto).  
   - Padronização de colunas como *Área*, *Cargo* e *Estado Civil*.  
   - Criação de colunas auxiliares, como situação do funcionário (Ativo/Demitido).  
3. **Modelagem de Dados**  
   - Relacionamentos entre tabelas quando necessário.  
   - Criação de medidas em **DAX** para indicadores principais.  
4. **Criação de Visualizações**  
   - Uso de **cards** para métricas principais.  
   - Gráficos de barras, linhas e colunas para análises comparativas.  
   - Segmentações (slicers) para filtros dinâmicos de Área, Cargo e Estado Civil.  
5. **Design do Dashboard**  
   - Layout limpo e intuitivo, com destaque para KPIs estratégicos.  
   - Paleta de cores consistente para melhor experiência visual.

---
## Principais KPIs do Dashboard
- Média Salarial — valor médio pago aos colaboradores.
- Número de Funcionários — total geral, além da divisão por Homens e Mulheres.
- Veteranos — colaboradores com mais de 10 anos de empresa.
- Tempo Médio de Empresa — média de anos trabalhados por área.
- Avaliação Média por Área — nota média de desempenho por setor.
- Estado Civil — total de Casados e Solteiros.
- Distribuição por Área e Cargo — filtros dinâmicos para detalhar dados por setor.

---
## Como Usar
1. Baixe o arquivo `Dashboard RH.pbix` deste repositório.  
2. Abra o arquivo com o [Power BI Desktop](https://powerbi.microsoft.com/desktop/).  
3. Utilize os **filtros laterais** para segmentar informações por **Área e Cargo**.  
4. Interaja com os gráficos e cartões para obter insights específicos. 

---
## Resultados
-  Visualização clara do **número total de funcionários**, separados por **homens e mulheres**.  
-  Análise da **média salarial por área**.  
-  Compreensão do **tempo médio de permanência na empresa**.  
-  Indicador de **funcionários casados e solteiros**.  
-  Avaliação média por área, facilitando análises de clima organizacional.  
-  Filtros interativos para explorar os dados conforme a necessidade do RH.
  
---
##  Imagem do Dashboard

![Dashboard](./imagens/dashboard_funcionarios.png)
