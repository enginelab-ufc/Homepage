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
- Programa de Pós-Graduação em Odontologia (validação clínica e base de dados)

---
### SADE - Sistema de Auxílio ao Pré-diagnóstico Domiciliar de Escoliose

**Status:** 🟢 Em andamento

**Início:** Setembro 2025 | **Previsão de Conclusão:** Dezembro 2026

**Responsável:** Prof. Bruno Riccelli

**Equipe:** 
- Pedro Kauan Silveira Silva
- Mikeyas Brito dos Santos
- Alison Dantas de Moura
- Luis Felipe de Andrade Marques
- Josué Lemos Mesquita

**Descrição:** Desenvolvimento de uma plataforma digital voltada para a triagem inicial e rastreamento da escoliose por meio de smartphones. O sistema utiliza Inteligência Artificial (deep learning) e visão computacional para guiar o usuário e analisar imagens do Teste de Adams, fornecendo laudos automáticos sugestivos e orientações para encaminhamento médico especializado.

**Objetivos:**

* Auxiliar o pré-diagnóstico domiciliar da escoliose com detecção de assimetrias.
* Desenvolver um validador de imagem em tempo real (luminosidade e enquadramento).
* Integrar dados clínicos (anamnese) e visuais na geração de laudos em PDF.
* Permitir interoperabilidade com Prontuários Médicos via HL7 FHIR.

**Metodologia:**

* Arquitetura de software baseada em Domain-Driven Design (DDD) e Clean Architecture.
* Criação de tutorial interativo para o posicionamento correto do paciente.
* Treinamento e inferência de modelo de Deep Learning utilizando CNNs.
* Implementação de fluxos e regras de negócio no backend.

**Tecnologias:** `Python` `FastAPI` `PyTorch` `Visão Computacional` `Docker` `HL7 FHIR` `SQL`

📂 **[Repositório](PRIVADO)**

---
### HygeIA - Sistema de Otimização de Saúde Bucal no SUS

**Status:** 🟢 Em andamento   
**Início:** Agosto 2025 | **Previsão de Conclusão:** Agosto 2027  
**Responsável:** Prof. Dr. José Wellington Franco da Silva

**Equipe:**
- Antonio Everton Coelho Teixeira (Graduando)
- Cainã Farias da Silva (Graduando)
- Gisele Gomes Costa (Graduanda)
- Wagner Vaconcelos Dias (Graduando)
  
**Bolsa**: -

**Descrição:**  
Aplicação de Inteligência Artificial e Aprendizado de Máquina para a otimização da saúde bucal no SUS, com foco na identificação de cáries e lesões bucais associada ao câncer de boca. As atividades envolvem o desenvolvimento e avaliação de modelos preditivos e sistemas inteligentes voltados à análise de imagens odontológicas, à prevenção de doenças bucais e à gestão de informações em saúde, contribuindo para a melhoria da qualidade do cuidado e para o fortalecimento da atenção básica.


**Objetivos:**

- Apoio ao diagnóstico precoce de doenças bucais;
- Contribuir para a otimização da gestão de informações em saúde no contexto do SUS;
- Apoiar profissionais da atenção básica com ferramentas tecnológicas voltadas à tomada de decisão;
- Incentivar a integração entre tecnologia e pesquisa na saúde pública.


**Metodologia:**
- Coleta e organização de imagens de dentes e lesões bucais para a formação da base de dados do projeto;
- Aplicação do modelo YOLO para detecção e identificação de lesões nas imagens odontológicas;
- Desenvolvimento e treinamento de modelos de Aprendizado de Máquina voltados à classificação e identificação de possíveis casos de cáries e câncer de boca;
- Avaliação dos modelos por meio de métricas de desempenho;
- Análise dos resultados obtidos para apoio ao diagnóstico;
- Documentação e validação das soluções desenvolvidas visando aplicação no contexto do SUS. 
  

**Tecnologias:**  
`Python` `YOLO` `JavaScript` `React` `FastAPI` `SQLite`

📂 **[Repositório](https://github.com/CainDeVV/Pet-Saude.git)**  


**Publicações:** 
- Revista CRO-CE
   - Entre Algoritmos e Autonomia: Dilemas Éticos da Inteligência Artificial na Odontologia Digital
   - Likes, Filtros e Ética Profissional: a Imagem do Cirurgião-Dentista na Era Digital
   - Sorrisos Digitais, Dados Sensíveis: Desafios Éticos na Era da Odontologia Conectada
   - Tecnologia Com Sensibilidade: O Desafio Ético da Humanização na Odontologia Digital
       
  
**Parcerias:**
- Curso de Odontologia - UFC (Fortaleza)
- EngineLab
- Ministério da Saúde
- Secretaria Municipal de Saúde de Fortaleza

---
### Grupo de Pesquisa em Segmentação e Classificação de Cárie Dentária via Imagens Móveis e Radiográficas

**Status:** 🟢 Em andamento
**Início:** início de 2025 | Previsão de Conclusão: não sei
**Responsáveis:** Prof. Dr. Wellington Franco e Profa. Dra. Lidiany Karla Azevedo Rodrigues

**Equipe:**
- Ana Larissa Teixeira Dantas (Graduanda)
- Jadiel Silva da Cunha (Graduando, IC)
- Julyana Raab Pereira (Mestranda)
- Isabelly Lima dos Santos (Mestranda)
- Beatriz Gonçalves Neves (Doutora)
- Bruno Riccelli dos Santos Silva (Doutor)
- Adriana Pigozzo Manso (Doutora)
- Wellington Franco (Doutor)
- Lidiany Karla Azevedo Rodrigues (Doutora)

**Bolsa:** PIBIC / Voluntário

**Descrição:** Desenvolvimento de sistemas de telediagnóstico baseados em inteligência artificial para detecção e análise da cárie dentária, priorizando o uso de imagens intraorais capturadas por smartphones para democratizar o acesso ao diagnóstico. O projeto evoluiu da classificação binária e ordinal (3 classes) para frentes mais avançadas, focando na segmentação semântica de imagens RGB e radiográficas. O objetivo central é refinar os limites de detecção e expandir a capacidade de categorização para abranger os estágios completos do sistema ICDAS.

**Objetivos:**
- Desenvolver e otimizar modelos de visão computacional para a segmentação precisa da cárie dentária em imagens intraorais (RGB).
- Expandir as classes preditivas para mapear detalhadamente os múltiplos níveis de severidade do critério ICDAS.
- Implementar algoritmos de segmentação aplicados a exames de raio-X odontológicos.
- Aumentar a robustez das predições frente a variações do mundo real, como iluminação não padronizada e artefatos de imagem.
- Consolidar um pipeline computacional de baixo custo computacional e alta eficácia para telediagnóstico remoto.

**Metodologia:**
- Aquisição e expansão do banco de imagens (smartphones e radiografias) com anotações de especialistas (ground truth).
- Treinamento de redes neurais profundas (CNNs) para tarefas de segmentação semântica e regressão ordinal.
- Validação cruzada e testes de estabilidade preditiva.
- Ajuste fino e otimização de modelos com frameworks modernos para garantir inferência em tempo viável.

**Tecnologias:** 
`Python` `TensorFlow` `PyTorch` `Scikit-learn` `OpenVINO` `Keras`

📂 **[Repositório](https://github.com/larissatx11/Pesquisa-Odonto)**  

**Publicações:** 
- Artigo aceito no Simpósio Brasileiro de Computação Aplicada à Saúde (SBCAS): "Classificação Ordinal de Lesões de Cárie Cavitadas e Não Cavitadas em Fotografias da Superfície Oclusal Baseada no ICDAS com Transfer Learning".

**Parcerias:**
- Faculdade de Farmácia
- Odontologia e Enfermagem (FFOE) - UFC Fortaleza

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

