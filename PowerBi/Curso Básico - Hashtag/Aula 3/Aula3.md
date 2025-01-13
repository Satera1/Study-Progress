# Aula 3 - Introdução às Fórmulas do Power BI

Nesta aula começamos a realizar a análise dos nossos dados, definindo as métricas e indicadores.
Começamos com a dica de realizar nossas análises (pensando em um ambiente empresarial) com a dinâmica 'top down' que, nesta ocasião, consiste em relatar informações no âmbito geral (uma análise mais global); então começamos criando uma ***Nova Medida*** (clicando com o *botão direito na tela* -> *Nova medida* ou *Página Incial* -> *Nova medida*), onde podemos passar instruções *DAX (Data Analysis Expressions)* para começarmos a realizar as análises de nossos dados. Começamos calculando a **Receita Líquida** (soma de todos valores da coluna *Valor do Frete Líquido*), o **Custo Total** (soma de todos valores da coluna *Custos*) e o **Lucro** (subtraindo ***Custo Total*** da ***Receita Líquida***).

De assim por diante fizemos diversas outras receitas, utilizando os métodos *SUM*, *AVERAGE*, *COUNT*, *DISTINCTCOUNT* e *CALCULATE* concatenado com *COUNTROWS*.
Para visualizarmos estas receitas devemos ir até o tab de ***Exibição de Relatório*** e criar um modo de visualização, como um gráfico de barras, colunas, linhas, pizza, etc. No caso desta aula começamos apenas com o *cartão*, que apenas mostra o valor da receita inserida no campo.
Como em alguma delas estamos mexendo com valores monetários, então nos foi mostrado como utilizar os métodos de formatação de texto que aparecem nas caixas, como adicionar/alterar o símbolo da moeda, ajuste de casas decimais e aplicar a porcentagem.
