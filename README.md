# Projeto BioRad – RM de Baixo Campo (~50 mT)

Protótipo educacional e de extensão focado em baixo campo magnético, baixo custo, portabilidade e pipeline totalmente reprodutível.  
Universidade Federal do Paraná (UFPR) / HV.

---

## 🎯 Objetivos

1. Construir um protótipo funcional de RM low-field (~50 mT) baseado em um arranjo Halbach.
2. Desenvolver um **pipeline vendor-neutral**:
   - **Pulseq (.seq)** → sequências de excitação
   - **MaRCoS / OCRA** → controle do hardware
   - **ISMRMRD** → dados brutos padronizados
   - **BART / SIRF** → reconstrução de imagem
3. Criar **datasets públicos** de phantoms para educação e pesquisa.
4. Publicar documentação completa: **BOM, CAD, scripts, POPs, relatórios**.
5. Implantar operação itinerante (extensão) com material educativo.

---

## 📦 Estrutura do Repositório

### **Hardware**

/hardware
Componentes físicos: Halbach, bobina, TR-switch, PA RF, elétrica, montagem, fotos.

### **CAD**

/cad
Arquivos STL/STEP, desenhos técnicos, peças 3D do suporte e bobina.

### **Pulseq**

/pulseq
Sequências: FID, SE, GRE, testes de sincronização, parâmetros.

### **Console (MaRCoS/OCRA)**

/marcos_ocra
Scripts, configurações e logs para controle via Red Pitaya.

### **Dados brutos (ISMRMRD)**

/ismrmrd_data
Aquisições brutas, conversões e exemplos.

### **Reconstrução**

/reconstruction
BART, SIRF, notebooks, scripts e resultados.

### **Quality Assurance (QA)**

/qa
SNR, CNR, uniformidade B0, distorção, repetibilidade e gráficos.

### **Dataset público**

/dataset
Phantoms, calibrações, aquisições e materiais para treinamento.

### **Extensão**

/extension
Ações itinerantes, banners, conteúdo educativo, POPs de campo.

### **BOM (Bill of Materials)**

/bom
Listas de materiais Fase 1 e Fase 2, fornecedores.

### **Scripts**

/scripts
Ferramentas auxiliares, automações.

### **Cronograma**

/cronograma
Gantt, marcos da Fase 1 e Fase 2.

---

## 🔁 Pipeline Reprodutível

1. **Pulseq (.seq)** → definição do pulso  
2. **MaRCoS/OCRA** → uso do Red Pitaya como console  
3. **ISMRMRD** → armazenamento universal dos dados  
4. **BART / SIRF** → reconstrução  
5. **QA** → validação objetiva (SNR, CNR, uniformidade, repetibilidade)

Esse pipeline permite que qualquer laboratório consiga **reproduzir** as etapas do projeto.

---

## 📅 Cronograma (24 meses)

**0–3 meses:** montagem mecânica + eletrônica mínima  
**3–6 meses:** primeiros FID/SE + QA inicial  
**6–12 meses:** ajustes B0 + documentação  
**12–18 meses:** dataset phantom + pipelines  
**18–24 meses:** artigo + consolidação da Fase 1

---

## 📜 Licença

Este projeto utiliza **MIT License**.

---

## 👥 Colaboradores

- Anderson dos Santos — UFPR / HV  
- Grupo de Física Médica — UTFPR
