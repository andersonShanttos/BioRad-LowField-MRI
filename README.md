# Projeto BioRad – Ressonância Magnética de Baixo Campo (~50 mT)

**BioRad – Tecnologia e Proteção à Vida** é um projeto educacional e de extensão
voltado ao desenvolvimento de um sistema de **Ressonância Magnética de baixo campo
(~50 mT)**, com foco em **baixo custo, portabilidade** e em um **pipeline totalmente
reprodutível**, integrando ensino, pesquisa e extensão.

**Instituição:** Universidade Federal do Paraná (UFPR) / Hospital Veterinário (HV)

---

## 🎯 Objetivos

- Construir um protótipo funcional de RM low-field (~50 mT) baseado em um arranjo Halbach
- Desenvolver um pipeline **vendor-neutral**, aberto e reprodutível
- Criar **datasets públicos** de phantoms para educação e pesquisa
- Publicar documentação completa (BOM, CAD, scripts, POPs e relatórios)
- Implantar **operação itinerante de extensão**, com material educativo

---

## 🔁 Pipeline Reprodutível

Pulseq (.seq) → definição do pulso  
MaRCoS / OCRA → controle do hardware (Red Pitaya)  
ISMRMRD → armazenamento universal de dados  
BART / SIRF → reconstrução de imagens  
QA → validação objetiva (SNR, CNR, uniformidade, repetibilidade)

Este pipeline permite que qualquer laboratório consiga reproduzir as etapas do
projeto de forma transparente, padronizada e de baixo custo.

---

## 📦 Estrutura do Repositório

- **/hardware** – Halbach, bobinas, TR-switch, PA RF, elétrica, montagem e fotos  
- **/cad** – Arquivos STL/STEP, desenhos técnicos e modelos 3D  
- **/pulseq** – Sequências FID, SE, GRE e testes experimentais  
- **/marcos_ocra** – Controle do sistema via Red Pitaya (MaRCoS / OCRA)  
- **/ismrmrd_data** – Dados brutos padronizados e exemplos  
- **/reconstruction** – Reconstrução com BART e SIRF  
- **/qa** – Quality Assurance (SNR, CNR, uniformidade, repetibilidade)  
- **/dataset** – Datasets públicos de phantoms  
- **/extension** – Ações de extensão e materiais educativos  
- **/bom** – Bill of Materials (Fase 1 e Fase 2)  
- **/scripts** – Ferramentas auxiliares  
- **/cronograma** – Planejamento e marcos do projeto  

A organização pode evoluir conforme o projeto avança.

---

## 📅 Cronograma (24 meses)

- **0–3 meses:** montagem mecânica e eletrônica mínima  
- **3–6 meses:** primeiros FID/SE e QA inicial  
- **6–12 meses:** ajustes de B0 e documentação  
- **12–18 meses:** datasets phantom e pipelines  
- **18–24 meses:** artigo e consolidação da Fase 1  

---

## 📜 Licença

Este projeto utiliza a **MIT License**.  
Consulte o arquivo `LICENSE` para mais detalhes.

---

## 👥 Colaboradores

- **Anderson dos Santos Schatzmann** — UFPR / Hospital Veterinário  
- Grupo de Física Médica — UTFPR
``
