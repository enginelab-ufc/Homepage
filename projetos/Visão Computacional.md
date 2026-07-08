# 🤖 Projetos de Visão Computacional

Projetos de pesquisa e desenvolvimento na área de Visão Computacional desenvolvidos no EngineLab.

---

## 📊 Visão Geral

- **Projetos Ativos:** 2
- **Projetos Concluídos:** 1
- **Publicações Geradas:** 1
- **Colaboradores:** 10

---

## 🚀 Projetos em Andamento

# 2026
### Sistema de Auxílio ao Diagnóstico de Cáries em Radiografias Interproximais (Bitewing)

**Status:** 🟢 Em andamento   
**Início:** Março 2026 | Previsão de Conclusão: Dezembro 2026
**Responsável:** Prof. Dr. José Wellington Franco da Silva 
**Equipe:**
- Wagner Vasconcelos Dias (Graduando em Ciência da Computação/ Desenvolvedor)
- Antonio Everton Coelho Teixeira (Graduando em Ciência da Computação / Desenvolvedor)
- Gisele Gomes Costa (Graduanda em Sistemas de Informação / Desenvolvedor)
- Isabelly Lima dos Santos (Estudante de Mestrado em Odontologia)
**Bolsa**: PIBIC 

Equipe:
Wagner Vasconcelos Dias (Graduando em Ciência da Computação/ Desenvolvedor)
Antonio Everton Coelho Teixeira (Graduando em Ciência da Computação / Desenvolvedor)
Gisele Gomes Costa (Graduanda em Sistemas de Informação / Desenvolvedor)


**Descrição:**  
A cárie dentária é uma lesão bacteriana progressiva que destrói os tecidos do dente, exigindo detecção precoce para evitar tratamentos invasivos, nossa solução atua exatamente aí, como um Sistema de Auxílio ao Diagnóstico em Radiografias Interproximais (Bitewing). O pipeline tecnológico inicia-se com a aplicação do modelo YOLO na radiografia original para isolar e extrair exclusivamente os dentes. Em seguida, utilizamos Redes Neurais profundas para realizar a segmentação semântica das lesões, identificando a cárie minuciosamente, pixel a pixel. Por fim, o sistema exibe a máscara de segmentação visual gerada pela IA e valida a sua eficácia calculando métricas de precisão em comparação direta com o padrão-ouro clínico.

**Objetivos:**  
- Desenvolver um pipeline de Visão Computacional totalmente automatizado para análise de radiografias bitewing.
- Criar modelos de extração e segmentação otimizados e leves, com foco em futura aplicação embarcada em dispositivos móveis.
- Validar a eficácia clínica da IA garantindo alta precisão e sensibilidade na detecção.
- Consolidar a pesquisa como publicação científica na área de Computação Aplicada à Saúde.

**Metodologia:**
- Detecção de objetos e recorte da região de interesse (isolamento da estrutura dentária) utilizando YOLO.
- Aplicação de técnicas de pré-processamento e Data Augmentation nas imagens de radiografia.
- Fine-tuning de Redes Neurais Convolucionais para a segmentação semântica das lesões (pixel a pixel).
- Avaliação de desempenho do modelo através de métricas cruzadas com o padrão-ouro (máscaras reais de referência demarcadas por estudantes de mestrado em Odontologia).

**Tecnologias:**
`Python` `PyTorch` `YOLO (Ultralytics)` `Torchvision` `OpenCV` `Albumentations` `Scikit-Learn`

**Repositório:**
https://github.com/WagnerSPDB/SegmentacaoRadiografiasBitewing 

**Parcerias:**
Programa de Pós-Graduação em Odontologia (validação clínica e base de dados)

---


---


---


---

## ✅ Projetos Concluídos

### 2025
---

### Estimativa de Sexo com Inteligência Artificial Aplicada à Análise Tridimensional da Região Orbitária: Aplicação de Redes Neurais Convolucionais e Transferência de Conhecimento em um Estudo Multicêntrico

**Status:** ✅ Concluído  
**Período:** Agosto 2024 - Julho 2025
**Responsável:** Prof. Dr. Wellington Franco
**Equipe:**  Maria Fernanda Aquino Freitas Scarcela (Graduação), Diego Santiago de Mendonça (Doutorado) e Fábio Wildson Gurgel Costa (Doutorado)
**Bolsa**: PIBIC 

**Descrição:**  
Desenvolvimento de um sistema inteligente para classificação do sexo biológico a partir da análise automática de seios paranasais em imagens médicas de Tomografia Computadorizada utilizando técnicas de Inteligência Artificial e Visão Computacional. 

**Resultados Alcançados:**
- ✅ Acurácia de 92,60% com Resnet50 + RF
- ✅ Publicação de artigo

**Tecnologias:**  
`Python` `Pytorch` `MONAI` `Sckit-learn` 

**Parcerias:**
- Programa de Pós-graduação em Odontologia da Universidade Federal do Ceará

📂 **[Repositório](https://github.com/fernandascarcela/Sex-Estimation-from-3D-Analysis-of-Paranasal-Sinuses)**  


**Publicações:**
📄 **[Artigo Publicado]([link](https://sol.sbc.org.br/index.php/eniac/article/view/38877))** - ENIAC 2025 

---


---
<div align="center">

[← Voltar aos Projetos](../README.md#projetos)

</div>

