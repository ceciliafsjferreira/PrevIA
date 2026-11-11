# 🚌 PrévIA — Preditivo de Atrasos no Transporte Público via Eventos Meteorológicos

> **PrévIA** é uma solução de inteligência artificial desenvolvida para prever a probabilidade de atrasos na frota de transporte público urbano a partir da integração e cruzamento de dados operacionais de trânsito e condições meteorológicas em tempo real.

---

## 🎯 Objetivo do Projeto

Eventos climáticos adversos (como chuvas intensas, alagamentos e tempestades) causam gargalos críticos na mobilidade urbana. O **PrévIA** une duas fontes distintas de dados para modelar padrões históricos e gerar previsões assertivas, permitindo que gestores e passageiros se antecipem aos impactos no tráfego.

---

## 🏗️ Arquitetura & Tecnologias

A pipeline de dados foi desenhada para suportar ingestão, tratamento e modelagem preditiva com alta performance:

* **Linguagem principal:** Python 3.x
* **Consultas & Transformações:** SQL
* **Data Lakehouse / Lake:** Databricks
* **Manipulação de Dados:** Pandas / PySpark
* **Machine Learning:** Scikit-Learn
* **Modelagem de Dados:** Arquitetura relacional e relatórios de fluxo

---

## 🗄️ Integração dos Bancos de Dados

O modelo preditivo cruza constantemente duas bases de dados:

1. **Dados Operacionais de Transporte:** Horários, rotas, localização da frota e tempo de percurso (ex: SPTrans).
2. **Dados Meteorológicos:** Precipitação, temperatura, umidade e alertas de tempestades (ex: OpenWeatherMap).

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
* Conta configurada no **Databricks** (ou ambiente Python local com Spark/SQL)
* Python 3.10+ instalado
* Chaves de acesso às APIs de dados meteorológicos e de transporte

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/previa.git](https://github.com/seu-usuario/previa.git)
   cd previa


Equipe da PrevIA

Cecília F. S. de Jesus Ferreira - Scrum Master

Josafá Rodrigues Mafra Junior - Product Owner

Irapuan Braga - Dev

Thiago Celso S. de Sousa - Dev

Yasmin Guedes dos Santos - Dev




