# Aula 2 - # Editando a Base de Dados com Power Query

De onde paramos na última aula, continuaremos a transformar nossos dados. Então seguimos com a extração de informações de uma única coluna (*Endereço*), usando a ferramenta ***Colunas de Exemplo***, em duas outras colunas (*Cidade* e *Estado*). Com isto, basta selecionar a coluna que queremos usar como base (*Endereço*) e ao usar esta ferramenta, preenchemos a coluna com exemplos do que queremos extrair. Após alguns exemplos dados a ferramenta, ela tentará identificar o padrão da informação dada e extrair o mesmo de todas as outras linhas.
Usando a ferramenta de adição, a partir de outras três colunas (*Custo Combustível*, *Custo Manutenção* e *Custo Fixos*), criamos uma única coluna (*Custos*) representando os custos totais; o mesmo foi feito usando outras duas colunas (*Data de Pedido* e *Data de Entrega*) em uma única coluna (*Tempo de Entrega*), porém desta vez usando a ferramenta de subtração para sabermos em qual foi o tempo total de entrega; usando esta informação, podemos comparar se o tempo total de entrega foi bom em relação ao prazo de entrega. Desta forma, podemos criar uma nova coluna (*Status Entrega*) usando a ferramenta de coluna condicional que terá como condição:
**Se** ***Tempo de Entrega*** **<=** ***Prazo de Entrega***
 A saída será de ***No Prazo***
 Senão, será de ***Atrasada***
 
Foi dado também um exemplo de adição de uma linha nova para comprovar a eficiência da automação do PowerBi que, como explicado na última aula, irá se utilizar das ***Etapas Aplicadas*** para transformar quaisquer novas linhas de informações em dados prontos para análise.
