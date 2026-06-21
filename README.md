# FIAP_tech_challenge_fase_01
Entrega para pós graduação IA Scientist fase 01
# 📊 NPS Preditivo em E-commerce

## 🎯 Objetivo

Analisar os fatores operacionais que impactam a satisfação do cliente em um e-commerce, utilizando o NPS como métrica principal, com o objetivo de antecipar detratores e gerar insights para melhoria da experiência do cliente.

---

## 🗂️ Base de Dados

A base contém dados históricos da jornada do cliente, incluindo:

* **Pedidos:** valor, quantidade de itens...
* **Logística:** tempo de entrega, atrasos, tentativas de entrega...
* **Atendimento:** número de contatos, tempo de resolução, reclamações...
* **Clientes:** idade, região, tempo de relacionamento...
* **Satisfação:** NPS (0 a 10) coletado ao final da jornada

A variável alvo é o **nps_score**, podendo ser tratada como:

* Contínua (0 a 10)
* Categórica: Promotores, Neutros e Detratores

---

## ⚙️ Metodologia

O projeto segue uma abordagem orientada a negócio:

1. **Entendimento do problema**

   * Identificação dos desafios de experiência do cliente
   * Contextualização do impacto do NPS

2. **Definição da target**

   * Uso do NPS como proxy de satisfação
   * Avaliação de limitações e possíveis vieses

3. **Análise Exploratória (EDA)**

   * Identificação dos principais drivers de satisfação
   * Análise de detratores
   * Detecção de pontos de ruptura na jornada

4. **Geração de insights**

   * Tradução dos resultados em recomendações práticas
   * Apoio à tomada de decisão nas áreas de negócio

---

## ▶️ Como Reproduzir

1. Clone o repositório:

```bash
git clone https://github.com/arthuralexandre10aa-sys/FIAP_tech_challenge_fase_01.git
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute os notebooks:

```bash
tech_challenge_fase_01_Arthur_Alexandre```

---

## 📌 Resultados Esperados

* Identificação dos principais fatores que impactam o NPS
* Compreensão dos perfis de clientes mais propensos a serem detratores
* Descoberta de pontos críticos na experiência (pontos de ruptura)
* Recomendações para melhoria da jornada do cliente

---

## 🚀 Conclusão

O projeto demonstra como dados operacionais podem ser utilizados para antecipar a satisfação do cliente e apoiar decisões estratégicas, promovendo uma experiência mais eficiente e orientada a dados.
