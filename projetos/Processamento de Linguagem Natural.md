# 🤖 Projetos de Processamento de Linguagem Natural

Projetos de pesquisa e desenvolvimento na área de PLN desenvolvidos no EngineLab.

---

## 📊 Visão Geral

- **Projetos Ativos:** 5
- **Projetos Concluídos:** 8
- **Publicações Geradas:** 12
- **Colaboradores:** 15

---

## 🚀 Projetos em Andamento

# 2026

### Desenvolvimento de um modelo de linguagem baseado em BERT especificamente otimizado para o português brasileiro moderno

**Status:** 🟢 Em andamento   
**Início:** Janeiro 2024 | **Previsão de Conclusão:** Dezembro 2024  
**Responsável:** Prof. Dr. Carlos Alberto Souza  
**Equipe:**
- Maria Clara Santos (Mestranda)
- João Pedro Lima (IC)
- Ana Paula Costa (IC)
**Bolsa**: PIBIC 

**Descrição:**  
Desenvolvimento de um modelo de linguagem baseado em BERT especificamente otimizado para o português brasileiro moderno. O projeto visa criar um modelo que supere os existentes em tarefas específicas do contexto brasileiro, incluindo gírias, neologismos e variações regionais. Atualmente em fase de coleta de corpus (50 milhões de sentenças) e pré-treinamento.

**Objetivos:**
- Coletar e curar corpus de 100 milhões de sentenças em PT-BR
- Treinar modelo BERT-base e BERT-large
- Alcançar SOTA em benchmarks brasileiros (ASSIN, HAREM)
- Disponibilizar modelo open-source na Hugging Face
- Publicar artigo em conferência internacional (NAACL/EMNLP)

**Metodologia:**
- Web scraping de fontes brasileiras (notícias, redes sociais, fóruns)
- Limpeza e filtragem usando heurísticas e modelos de qualidade
- Pré-treinamento com estratégia MLM + NSP
- Fine-tuning em múltiplas tarefas downstream
- Avaliação extrinseca e intrinseca

**Tecnologias:**  
`Python` `PyTorch` `Transformers` `Scrapy` `Spark` `MLflow` `Weights & Biases` `HuggingFace`

📂 **[Repositório](https://github.com/enginelabufc/brazilian-bert)**  

**Publicações:** 
- Paper em NAACL 2025 (Submetido)
- Dataset paper em LREC 2025 (Em preparação)
- Blog post técnico

**Parcerias:**
- Google Research Brasil (cloud credits)
- PUC-Rio (colaboração em corpus)
---
### IluminIA

**Status:** 🟢 Em andamento   
**Início:** Agosto 2025 | **Previsão de Conclusão:** Agosto 2026  
**Responsável:** Prof. Dra. Amanda Drielly Pires Venceslau
**Equipe:**
- Marciel Barros Pereira (Supervisor)
- Gabriel (Mestrando)
- Maria Clara Pereira de Sousa (Bolsista)
- Mikeyas (Bolsista)
- Emerson (Bolsista)
- Sthefany (Bolsista)

**Bolsa**: FASTEF

**Descrição:**  
O **IluminIA** é um projeto voltado para o desenvolvimento de uma arquitetura baseada em **Large Language Models (LLMs)** integrada à técnica de **Retrieval-Augmented Generation (RAG)** para auxiliar na geração automática de **Planos Educacionais Individualizados (PEIs)**.

A proposta busca apoiar a educação inclusiva por meio da automação e personalização de documentos pedagógicos, considerando diretrizes educacionais, necessidades específicas dos estudantes e práticas inclusivas.


**Objetivos:**
- Desenvolver uma arquitetura baseada em LLMs e RAG para geração automática de PEIs



**Metodologia:**
- **LLMs** integrada à técnica de **RAG** para auxiliar na geração automática de **PEIs**.


**Tecnologias:**  
`FastApi` `React` `Docker` `PostgreSQL` 


**Publicações:** 
- SBBD 2026 - Demos paper (Submetido)


**Parcerias:**
- FASTEF

---


---


---

## ✅ Projetos Concluídos

### 2025
### GRAFTEA

**Status:** ✅ Concluído  
**Período:** Setembro 2024 - Agosto 2025  
**Responsável:** Prof. Dr. Amanda Drielly Pires Venceslau
**Equipe:** Giovanna Maria Verissimo Xavier (Graduação) e Amanda Drielly Pires Venceslau(Doutora).

**Descrição:**  
Este trabalho propõe a construção de um gráfico de conhecimento acadêmico que reúne fontes, como artigos, conjuntos de dados e outros recursos, focados em ferramentas de suporte visual digital aplicadas ao ensino de crianças com autismo.

**Resultados Alcançados:**
- ✅ O GRAFTAE gerou aproximadamente 1069 triplas RDF, sendo: 709 triplas provenientes de três fontes heterogêneas e 360 triplas inferidas automaticamente pela ontologia.
- ✅ Reutilização de ontologias do OpenAIRE Graph
- ✅ Reutilização de estruturas propostas por Knowledge Graph acadêmicos


**Tecnologias:**  
`RDF` `Turtle` `Sparql` `GraphDB` `rdflib` `Zenodo API` `Protégé`

📂 **[Repositório](https://github.com/GiovannaXavier18/GRAFTAE.git)**  
---


---
<div align="center">

[← Voltar aos Projetos](../README.md#projetos)

</div>
