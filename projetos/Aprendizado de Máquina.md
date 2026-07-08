# 🤖 Projetos de Aprendizado de Máquina

Projetos de pesquisa e desenvolvimento na área de Aprendizado de Máquina desenvolvidos no EngineLab.

---

## 📊 Visão Geral

- **Projetos Ativos:** 3
- **Projetos Concluídos:** 4
- **Publicações Geradas:** 5
- **Colaboradores:** 6

---

## 🚀 Projetos em Andamento

# 2026

### O USO DE TÉCNICAS DE APRENDIZADO DE MÁQUINA À MORFOMETRIA DOS
SEIOS PARANASAIS PARA ESTIMATIVA DO SEXO BIOLÓGICO EM POPULAÇÕES
BRASILEIRAS

**Status:** 🟢 Concluído
**Início:** Agosto de 2025 | **Conclusão:** Fevereiro de 2026
**Responsável:** Prof. Dr. José Wellington Franco da Silva   
**Equipe:**
- João Victor de Oliveira Rodrigues 

**Descrição:**  
Este projeto propõe o desenvolvimento de modelos de aprendizado de máquina para predição do sexo biológico a partir de medidas morfométricas dos seios paranasais obtidas por tomografia computadorizada. Para isso, serão utilizadas características lineares, tridimensionais e volumétricas associadas a técnicas de pré-processamento, engenharia de atributos e classificação supervisionada, buscando identificar padrões anatômicos relacionados ao dimorfismo sexual

**Objetivos:**
- Desenvolver modelos de aprendizado de máquina para predição do sexo biológico utilizando medidas morfométricas dos seios paranasais.
- Aplicar técnicas de pré-processamento e engenharia de atributos nos dados extraídos das tomografias computadorizadas.
- Treinar diferentes algoritmos de classificação supervisionada.
- Otimizar hiperparâmetros dos modelos utilizando validação cruzada.
- Comparar o desempenho dos classificadores por meio de métricas estatísticas.
- Identificar as características anatômicas mais relevantes para a distinção entre os sexos.
- Avaliar a robustez e capacidade de generalização dos modelos desenvolvidos.

**Metodologia:**
- Pré-processamento e padronização dos dados.
- Engenharia de atributos morfométricos.
- Tratamento de outliers utilizando IQR Clipping.
- Treinamento de modelos de classificação supervisionada.
- Otimização de hiperparâmetros com GridSearchCV.
- Aplicação de validação cruzada estratificada.
- Ajuste de threshold para classificação.
 -Avaliação e comparação dos modelos utilizando métricas estatísticas.

**Tecnologias:**  
Python ipynb

📂 **[Repositório](https://github.com/VictorORodrigues/Classifica-o-do-sexo-biol-gico-a-partir-das-medidas-dos-seios-paranasais/tree/main)**

**Parcerias:**
- Programa de Mestrado Odontologia Fortaleza-CE

---

### Análise e Predição de Insuficiência Cardíaca

**Status:** 🟢 Em andamento

**Início:** Janeiro 2026 | **Previsão de Conclusão:** Junho 2026

**Responsável:** Prof. Bruno Riccelli

**Equipe:** 
- Pedro Kauan Silveira Silva
- Mikeyas Brito dos Santos
- Gisele Gomes
**Bolsa**: IC

**Descrição:** Desenvolvimento de um modelo preditivo baseado em Inteligência Artificial para avaliar o risco e detectar padrões associados à insuficiência cardíaca. O projeto processa bases de dados de saúde para extrair características clínicas (biomarcadores, fatores demográficos e comorbidades), auxiliando na detecção precoce e servindo como uma ferramenta de suporte à decisão clínica.

**Objetivos:**

* Realizar o pré-processamento e análise exploratória de datasets de saúde cardiovascular.
* Treinar e otimizar modelos de aprendizado de máquina para classificação de risco cardíaco.
* Identificar as principais features clínicas que influenciam a progressão da insuficiência cardíaca.
* Avaliar os modelos utilizando métricas como Acurácia, Precisão, Recall e AUC-ROC.

**Metodologia:**

* Limpeza de dados e tratamento de anomalias/valores ausentes em registros clínicos.
* Engenharia de atributos (feature engineering) para melhorar o poder de separação das classes.
* Validação cruzada e ajuste de hiperparâmetros de algoritmos de classificação.
* Documentação e versionamento do modelo preditivo para reprodutibilidade científica.

**Tecnologias:** `Python` `Pandas` `Scikit-Learn` `PyTorch Lightning` `Matplotlib` `Jupyter Notebook`

📂 **[Repositório](https://github.com/pkziinn10/Heart-Failure)**

---
### Modelo Preditivo para Estimativa de Faturamento

**Status:** 🟢 Em andamento

**Início:** Janeiro 2026 | **Previsão de Conclusão:** Junho 2026

**Responsável:** Prof. Bruno Riccelli

**Equipe:** - Pedro Kauan Silveira Silva (Desenvolvedor Principal)
**Bolsa**: IC

**Descrição:** Construção de um sistema analítico focado na predição e estimativa de faturamento utilizando histórico de registros operacionais e financeiros. A solução busca identificar sazonalidades, tendências e anomalias na receita para projetar resultados futuros, otimizando o planejamento estratégico e a alocação de recursos institucionais baseada em dados.

**Objetivos:**

* Prever o faturamento mensal e projetar tendências financeiras.
* Estruturar uma base de dados consolidada a partir de fontes históricas de cobrança e serviços.
* Otimizar a tomada de decisão gerencial através de insights preditivos.
* Implementar pipelines analíticos contínuos para atualização de projeções.

**Metodologia:**

* Integração e consolidação de dados transacionais.
* Aplicação de modelos preditivos e regressão para estimativa de valores contínuos.
* Avaliação estatística da precisão das previsões usando métricas padronizadas.
* Estruturação de um fluxo analítico reprodutível e versionado.

**Tecnologias:** `Python` `Pandas` `Scikit-Learn` `SQL` `Docker` `Git`

📂 **[Repositório](PRIVADO)**

---

### AUSMI - Analyze the Use of Medical Services by the Elderly

**Status:** 🟢 Em andamento

**Início:** Janeiro 2026 | **Previsão de Conclusão:** Junho 2026

**Responsável:** Prof. Bruno Riccelli

**Equipe:** 
- Pedro Kauan Silveira Silva
- Mikeyas Brito dos Santos

**Descrição:** Desenvolvimento de um projeto analítico focado em explorar os padrões de uso de serviços médicos por indivíduos com 50 anos ou mais. O projeto utiliza dados da *National Poll on Healthy Aging* para avaliar e comparar diferentes classificadores de aprendizado de máquina na previsão da frequência anual de consultas médicas dessa população, auxiliando no entendimento e planejamento das demandas de saúde na terceira idade.

**Objetivos:**

* Explorar e analisar dados de saúde pública focados na população 50+.
* Prever a frequência anual de visitas a médicos utilizando dados demográficos e clínicos.
* Treinar e comparar o desempenho de múltiplos algoritmos de classificação (como XGBoost, Random Forest e SVM).
* Documentar a metodologia e realizar validação estatística rigorosa dos resultados.

**Metodologia:**

* Pré-processamento e limpeza da base de dados da *National Poll on Healthy Aging*.
* Aplicação de validação cruzada estratificada (*stratified cross-validation*) para garantir a robustez dos modelos.
* Ajuste e otimização de hiperparâmetros (*hyperparameter tuning*).
* Avaliação de desempenho e validação estatística comparativa utilizando o teste de Wilcoxon.

**Tecnologias:** `Python` `Pandas` `Scikit-Learn` `XGBoost` `Estatística` `Machine Learning`

📂 **[Repositório](https://github.com/pkziinn10/Analyze-the-use-of-medical-services-by-the-elderly)**

--

### Green AI in Credit Risk: Carbon-Aware Machine Learning

**Status:** 🟢 Em andamento   
**Início:** Outubro 2025 | **Previsão de Conclusão:** Julho 2026  
**Responsável:** Prof. Dr. Marcos Roberto Machado  
**Equipe:**
- Antonio Everton Coelho Teixeira (Graduando)
- José Wellington Franco da Silva (Doutorado)


**Descrição:**  
Projeto de pesquisa voltado para análise do impacto ambiental de modelos de aprendizado de máquina aplicados à previsão de risco de crédito. O estudo investigou como estratégias de engenharia e seleção de atributos afetam simultaneamente o desempenho preditivo e o consumo energético dos modelos. Foram realizados experimentos considerando diferentes níveis de dimensionalidade das variáveis para analisar o equilíbrio entre eficiência computacional e emissões de carbono.

**Objetivos:**
- Investigar a relação entre desempenho preditivo e impacto ambiental
- Avaliar o efeito da dimensionalidade das características (-10% até +50%)
- Comparar emissões e consumo energético sob diferentes cenários experimentais
- Comparar frameworks de monitoramento de carbono
- Propor métricas que integrem desempenho e sustentabilidade computacional

**Metodologia:**
- Seleção de atributos utilizando Mutual Information
- Construção de 11 cenários experimentais com redução e aumento progressivo de atributos
- Avaliação dos modelos Random Forest, LightGBM e Redes Neurais Artificiais
- Monitoramento energético e cálculo de emissões utilizando CodeCarbon e CarbonTracker

**Tecnologias:**  
`Python` `CodeCarbon` `CarbonTracker` `Pandas` `Numpy` `Scikit-Learn`

📂 **[Repositório](https://github.com/EvertonTeix/Green-AI-in-Credit-Risk-Balancing-Performance-and-Carbon-Efficiency)**  

**Parcerias:**
- University of Twente (Universidade de Twente)

## ✅ Projetos Concluídos

### 2025
### Balancing Accuracy, Fairness, Explainability and Sustainability in Peer-to-Peer Credit Risk Assessment

**Status:** ✅ Concluído  
**Período:** Fevereiro 2025 - Agosto 2025  
**Responsável:** Prof. Dr. Marcos Roberto Machado  
**Equipe:** Antonio Everton Coelho Teixeira (Graduação), José Wellington Franco da Silva (Doutorado)

**Descrição:**  
Projeto de pesquisa voltado para análise dos trade-offs entre desempenho preditivo, justiça algorítmica, explicabilidade e sustentabilidade em modelos de aprendizado de máquina aplicados à previsão de inadimplência em plataformas de empréstimos Peer-to-Peer (P2P). O estudo avaliou diferentes classificadores amplamente utilizados em crédito financeiro utilizando um protocolo reproduzível orientado à governança responsável de sistemas de IA.

**Resultados Alcançados:**
- ✅ Benchmark de classificadores para previsão de risco de crédito P2P
- ✅ Avaliação de desempenho utilizando Accuracy, Precision, Recall, F1-score e AUC
- ✅ Análise de justiça algorítmica por meio de Disparate Impact
- ✅ Aplicação de métodos de explicabilidade utilizando SHAP e LIME
- ✅ Quantificação de consumo energético e emissões de CO₂ utilizando CodeCarbon
- ✅ Avaliação do custo ambiental por ganho de desempenho preditivo
- ✅ Identificação e análise dos trade-offs entre precisão, justiça, explicabilidade e sustentabilidade

**Tecnologias:**  
`Python` `SHAP` `LIME` `CodeCarbon` `Pandas` `Numpy`

📂 **[Repositório](https://github.com/EvertonTeix/p2p-credit-risk-tradeoffs)**  



---


---
<div align="center">

[← Voltar aos Projetos](../README.md#projetos)

</div>
