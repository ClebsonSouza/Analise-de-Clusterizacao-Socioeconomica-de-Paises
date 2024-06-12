# Projeto Cluster Paises

### * Exercício adaptado do MBA USP/Esalq em Data Science e Analytics

Este projeto realiza uma análise de clusterização de países com base em diversas características socioeconômicas. Utilizando técnicas de clusterização hierárquica e K-means, buscamos agrupar países com perfis semelhantes, o que pode ser útil para análises econômicas, políticas e sociais.

Problema de Negócio
Agrupar países com características semelhantes pode fornecer insights valiosos para formuladores de políticas, economistas e pesquisadores. A clusterização ajuda a identificar padrões e tendências que podem não ser evidentes em análises individuais.

Estrutura do Projeto
1. Carregamento dos Dados
Carregamos a base de dados a partir do arquivo CSV dados_paises.csv, contendo diversas variáveis socioeconômicas sobre os países.

2. Análise de Correlação
Calculamos a matriz de correlação das variáveis, removendo a coluna "country" que serve apenas como identificador. Esta análise ajuda a entender as relações entre as variáveis e a identificar redundâncias.

3. Clusterização Hierárquica
Aplicamos a técnica de clusterização hierárquica para agrupar os países. Utilizamos o dendrograma para visualizar e determinar o número ideal de clusters.

4. Clusterização K-means
Aplicamos a técnica de K-means para agrupar os países em clusters definidos. Avaliamos a qualidade dos clusters utilizando a métrica de Silhouette.

5. Visualização dos Clusters
Utilizamos gráficos 3D para visualizar os clusters formados, o que facilita a interpretação e análise dos resultados.

6. Caracterização dos Clusters
Analisamos as características de cada cluster, calculando estatísticas descritivas por grupo. Isso nos permite entender melhor as similaridades e diferenças entre os grupos de países.

Conclusão
Este projeto demonstra como técnicas de clusterização podem ser utilizadas para agrupar países com características socioeconômicas semelhantes. Os insights obtidos a partir dessa análise podem ser extremamente valiosos para diversas aplicações, incluindo a formulação de políticas públicas e a análise econômica.
