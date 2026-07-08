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

**Publicações:** (Se houver)
- Paper em NAACL 2025 (Submetido)
- Dataset paper em LREC 2025 (Em preparação)
- Blog post técnico

**Parcerias:**
- Google Research Brasil (cloud credits)
- PUC-Rio (colaboração em corpus)
Área: Visão Computacional 

Título do projeto:
Sistema de Auxílio ao Diagnóstico de Cáries em Radiografias Interproximais (Bitewing)

Status:  Em andamento

Início: Março 2026 | Previsão de Conclusão: Dezembro 2026

Responsável: Prof. Dr. José Wellington Franco da Silva

Equipe:
Wagner Vasconcelos Dias (Graduando em Ciência da Computação/ Desenvolvedor)
Antonio Everton Coelho Teixeira (Graduando em Ciência da Computação / Desenvolvedor)
Gisele Gomes Costa (Graduanda em Sistemas de Informação / Desenvolvedor)

Isabelly Lima dos Santos:
Estudante de Mestrado em Odontologia (Curadoria e Anotação Clínica)

Descrição: A cárie dentária é uma lesão bacteriana progressiva que destrói os tecidos do dente, exigindo detecção precoce para evitar tratamentos invasivos, nossa solução atua exatamente aí, como um Sistema de Auxílio ao Diagnóstico em Radiografias Interproximais (Bitewing). O pipeline tecnológico inicia-se com a aplicação do modelo YOLO na radiografia original para isolar e extrair exclusivamente os dentes. Em seguida, utilizamos Redes Neurais profundas para realizar a segmentação semântica das lesões, identificando a cárie minuciosamente, pixel a pixel. Por fim, o sistema exibe a máscara de segmentação visual gerada pela IA e valida a sua eficácia calculando métricas de precisão em comparação direta com o padrão-ouro clínico.

Objetivos:

Desenvolver um pipeline de Visão Computacional totalmente automatizado para análise de radiografias bitewing.

Criar modelos de extração e segmentação otimizados e leves, com foco em futura aplicação embarcada em dispositivos móveis.

Validar a eficácia clínica da IA garantindo alta precisão e sensibilidade na detecção.

Consolidar a pesquisa como publicação científica na área de Computação Aplicada à Saúde.

Metodologia:

Detecção de objetos e recorte da região de interesse (isolamento da estrutura dentária) utilizando YOLO.

Aplicação de técnicas de pré-processamento e Data Augmentation nas imagens de radiografia.

Fine-tuning de Redes Neurais Convolucionais para a segmentação semântica das lesões (pixel a pixel).

Avaliação de desempenho do modelo através de métricas cruzadas com o padrão-ouro (máscaras reais de referência demarcadas por estudantes de mestrado em Odontologia).

Tecnologias: Python, PyTorch, YOLO (Ultralytics), Torchvision, OpenCV, Albumentations, Scikit-Learn

Repositório: https://github.com/WagnerSPDB/SegmentacaoRadiografiasBitewing 

Parcerias:
Programa de Pós-Graduação em Odontologia (validação clínica e base de dados)

---


---


---


---

## ✅ Projetos Concluídos

### 2025




---


---
<div align="center">

[← Voltar aos Projetos](../README.md#projetos)

</div>
