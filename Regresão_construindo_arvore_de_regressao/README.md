# 🌳 Regressão: Construindo Árvore de Regressão
---
## Índice  
- [Sobre o projeto](#sobre-o-projeto)  
- [Aprendizagens](#aprendizagens)  
- [Tópicos Explorados](#tópicos-explorados)  
- [Tecnologias utilizadas](#tecnologias-utilizadas)  
- [Licença](#licença)  

---

## Sobre o projeto  
Projeto focado na **construção e otimização de árvores de regressão** para modelagem preditiva, para precificação de entrega de esculturas, desenvolvido como parte da formação em Data Science da Alura. O objetivo é dominar algoritmos de aprendizado de máquina para previsão de valores contínuos, desde a preparação dos dados até a interpretação dos resultados do modelo.  

---

## Aprendizagens  
- **Fundamentos de árvores de regressão**: Compreensão do algoritmo e sua aplicação em problemas de previsão numérica.  
- **Divisão de nós**: Critérios como MSE (Mean Squared Error) e MAE (Mean Absolute Error) para splits otimizados.  
- **Prevenção de overfitting**: Técnicas de podagem (pruning) e validação cruzada.  
- **Interpretação de resultados**: Análise de importância de variáveis e visualização da árvore.  

---

## Abordagem Metodológica
O desenvolvimento segue uma estrutura progressiva:

Preparação dos dados: Tratamento de valores missing, encoding de variáveis categóricas e divisão treino-teste

Modelagem inicial: Criação de uma árvore baseline com parâmetros padrão

Otimização sistemática: Busca de hiperparâmetros via validação cruzada

Avaliação rigorosa: Análise de métricas de performance e interpretabilidade do modelo
---

## Tópicos Explorados  
### 🔍 **Análise de Sensibilidade**  
- Teste do modelo com diferentes conjuntos de dados e parâmetros para avaliar robustez.  

### 📉 **Métricas de Performance**  
- Cálculo de **R²**, **RMSE** (Root Mean Squared Error) e **MAE** para validação dos resultados.  

### 🌲 **Visualização da Árvore**  
- Exportação de gráficos da estrutura de decisão para compreensão do comportamento do modelo.  

### ⚙️ **Otimização de Hiperparâmetros**  
- Uso de **GridSearchCV** e **RandomizedSearchCV** para encontrar a melhor configuração.  

### 🔮 **Aplicações em Cenários Reais**  
- Previsão de preços de imóveis, demanda de produtos ou qualquer variável contínua.  

---

## Tecnologias utilizadas  
 - [Google Colaboratory](https://colab.research.google.com/): Ambiente de notebook interativo baseado na nuvem.
- [Python](https://www.python.org/): Linguagem de programação.  
- [Scikit-learn](https://scikit-learn.org/stable/) (*DecisionTreeRegressor*, *GridSearchCV*)  
- [Pandas](https://pandas.pydata.org/):  Biblioteca para manipulação e análise de dados.
- [Matplotlib](https://matplotlib.org/):  Biblioteca para criação de gráficos e visualizações estáticas.
- [Seaborn](https://seaborn.pydata.org/):  Biblioteca para visualização de dados estatísticos, baseada em Matplotlib.
- [Graphviz](https://graphviz.org/): Visualização de árvores  

---

## Licença  
Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).  

---

✨ Feito por [Marcia Gabrielle](https://github.com/Gabriellemga).  



