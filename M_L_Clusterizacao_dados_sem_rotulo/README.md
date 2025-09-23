# 🎯 Clusterização de Dados sem Rótulo: Projeto de Marketing

## Índice
- [Sobre o projeto](#sobre-o-projeto)
- [Objetivos principais](#objetivos-principais)
- [Metodologia aplicada](#metodologia-aplicada)
- [Algoritmos utilizados](#algoritmos-utilizados)
- [Métricas de avaliação](#métricas-de-avaliação)
- [Aplicações práticas](#aplicações-práticas)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Resultados esperados](#resultados-esperados)
- [Licença](#licença)

---

## Sobre o projeto
Projeto de **aprendizado não supervisionado** focado em técnicas de clusterização para segmentação de clientes em campanhas de marketing. Desenvolvido como parte da formação em Data Science da Alura, aborda desde o pré-processamento de dados até a interpretação dos clusters identificados.

---

## Objetivos principais
- **Segmentação de clientes**: Identificar grupos homogêneos com comportamentos similares
- **Análise de padrões**: Descobrir insights ocultos em dados não rotulados
- **Otimização de marketing**: Direcionar estratégias específicas para cada perfil de cliente
- **Redução de dimensionalidade**: Visualizar dados multivariados de forma inteligível

---

## Metodologia aplicada
### 🔍 **Pré-processamento**
- Tratamento de valores missing e outliers
- Normalização e padronização de features
- Redução de dimensionalidade (PCA)
- Análise de correlação entre variáveis

### 📊 **Análise exploratória**
- Estatísticas descritivas dos segmentos
- Visualização de distribuições
- Identificação de características dominantes por cluster

---

## Algoritmos utilizados
### 🎯 **K-Means**
- Algoritmo particional com inicialização k-means++
- Método do cotovelo para determinação do k ideal
- Análise de silhueta para validação de clusters

### 🌳 **Clustering Hierárquico**
- Dendrogramas para análise visual
- Métodos aglomerativos (ward, complete, average linkage)
- Identificação de subgrupos naturais

### 🔵 **DBSCAN**
- Detecção de clusters de densidade variável
- Identificação de outliers e ruídos
- Adaptabilidade a formatos não convexos

---

## Métricas de avaliação
- **Silhouette Score**: Coesão e separação dos clusters
- **Davies-Bouldin Index**: Qualidade da separação entre grupos
- **Calinski-Harabasz Index**: Densidade e variância dos clusters
- **Análise visual**: PCA 2D/3D para inspeção manual

---

## Aplicações práticas
### 🏪 **Varejo**
- Segmentação por comportamento de compra
- Identificação de clientes VIP
- Campanhas personalizadas por perfil

### 🏦 **Bancos**
- Grupos por uso de produtos financeiros
- Detecção de padrões de investimento
- Otimização de ofertas cruzadas

### 📱 **E-commerce**
- Clusterização por navegação e histórico
- Recomendações personalizadas
- Retenção de clientes

---

## Tecnologias utilizadas
- **Python 3.8+**
- **Scikit-learn** (KMeans, DBSCAN, Hierarchical Clustering)
- **Pandas** e **NumPy** para manipulação de dados
- **Matplotlib** e **Seaborn** para visualizações
- **Scipy** para clustering hierárquico
- **Plotly** para gráficos interativos

---

## Resultados esperados
- **Perfis de clientes** claramente definidos e interpretáveis
- **Estratégias de marketing** direcionadas e eficientes
- **Aumento de conversão** através de personalização
- **Redução de custos** com marketing massivo
- **Insights acionáveis** para tomada de decisão

---

## Licença
Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).

---

✨ Desenvolvido por [Marcia Gabrielle](https://github.com/Gabriellemga)

