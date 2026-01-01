# 🌕 Análise das Luas do Sistema Solar com Ciência de Dados

## 📌 Visão Geral

As luas do Sistema Solar constituem um verdadeiro laboratório natural para o estudo de processos físicos, composicionais e evolutivos. Elas apresentam grande diversidade de tamanhos, densidades e massas, refletindo diferentes histórias de formação e ambientes planetários.

Este projeto aplica **ciência de dados** a esse contexto astronômico, explorando parâmetros físicos consolidados das luas para investigar **padrões emergentes**, **semelhanças estruturais** e a **organização natural desses corpos em grupos físicos distintos**.

O foco é **exploratório e interpretativo**, combinando rigor estatístico com leitura física dos resultados.

---

## 🎯 Pergunta Central

**Quais padrões físicos emergem quando analisamos as luas do Sistema Solar em conjunto, e elas se organizam naturalmente em grupos com propriedades semelhantes?**

---

## 🧪 Dados Utilizados e Fontes

Os dados utilizados neste projeto foram obtidos a partir de fontes oficiais e amplamente reconhecidas pela comunidade científica:

* **Planetary Satellite Physical Parameters (JPL)**
  [https://ssd.jpl.nasa.gov/sats/phys_par/](https://ssd.jpl.nasa.gov/sats/phys_par/)

* **Jet Propulsion Laboratory (JPL)**
  [https://www.jpl.nasa.gov/](https://www.jpl.nasa.gov/)

* **NASA – National Aeronautics and Space Administration**
  [https://www.nasa.gov/](https://www.nasa.gov/)

O conjunto de dados reúne **parâmetros físicos médios consolidados** das luas do Sistema Solar, derivados de observações astronômicas, modelos dinâmicos e resultados de missões espaciais.

⚠️ Importante:
Os dados **não representam séries temporais** nem medições instrumentais brutas. Eles são adequados para **análises comparativas, inferência estatística exploratória e aprendizado não supervisionado**, respeitando as limitações inerentes a parâmetros agregados.

---

## 🔬 Metodologia

O projeto segue um fluxo metodológico claro e reproduzível:

1. **Auditoria e preparação dos dados**
2. **Análise Exploratória de Dados (EDA)** com interpretação física
3. **Inferência estatística não paramétrica**, considerando assimetrias e tamanhos amostrais distintos
4. **Aprendizado não supervisionado (K-Means)** para identificação de grupos naturais
5. **Validação visual dos clusters**
6. **Análise dirigida de um cluster físico específico**

Cada etapa é documentada com explicações objetivas e visualizações adequadas, evitando extrapolações indevidas.

---

## 📊 Principais Resultados

* As propriedades físicas das luas apresentam **forte heterogeneidade e assimetria**.
* Diferenças visuais entre sistemas planetários nem sempre se traduzem em **diferenças estatisticamente significativas**.
* A clusterização multivariada revela **grupos naturais de luas**, associados a:

  * corpos pequenos e ricos em gelo,
  * grupos intermediários de composição mista,
  * um conjunto restrito de luas grandes e densas, fisicamente distinto.
* Mesmo clusters pequenos refletem **realidades físicas extremas**, e não artefatos algorítmicos.

---

## 🧠 Interpretação Científica

Os grupos identificados emergem diretamente da estrutura dos dados, sem uso de rótulos prévios. Eles refletem diferenças reais de **tamanho, composição e massa**, coerentes com teorias de formação e evolução dos sistemas planetários.

O projeto demonstra como técnicas de ciência de dados podem **complementar a análise astrofísica tradicional**, oferecendo uma abordagem multivariada e integrada.

---

## 🛠️ Tecnologias Utilizadas

* **Python**
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Yellowbrick

---

## 📁 Estrutura do Repositório

* `luas_sistema_solar.ipynb` — Notebook principal do projeto
* `README.md` — Descrição e contextualização do estudo

---
📢 Conecte-se e acompanhe mais projetos
Se você se interessa por ciência de dados aplicada, astrofísica e análises exploratórias baseadas em dados reais, fique à vontade para se conectar comigo no [LinkedIn]([https://www.linkedin.com/feed/)](https://www.linkedin.com/in/ednei-cunha-vicente-551b64187/), acompanhar meus artigos no Medium https://medium.com/@ednei_vicente ou entrar em contato por e-mail ednei.adgpo@gmail.com para trocas técnicas, colaborações ou feedbacks sobre o projeto.

## 📌 Observação Final

Este projeto possui caráter **exploratório e educacional**, priorizando clareza, rigor metodológico e interpretação física responsável. Ele não busca generalizações além do escopo dos dados analisados.
