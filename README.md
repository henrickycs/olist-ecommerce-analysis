# 📊 Análise de Dados - E-commerce Brasileiro (Olist)

Este projeto realiza uma análise exploratória dos dados de uma plataforma real de e-commerce brasileira, disponibilizada pela Olist no Kaggle. O objetivo é entender os padrões de compra, entrega, pagamento e satisfação dos clientes.

---

## 🔍 Objetivos da Análise

- 📦 **Quais são as categorias de produtos mais vendidas?**
- 🛒 **Qual o tempo de entrega e como ele varia entre os estados?**
- ⏳ **Atrasos nas entregas impactam as avaliações dos clientes?**

## 🗃️ Fonte dos Dados

- Dataset: [Brazilian E-commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Tamanho: ~100 MB (CSV)
- Estrutura: Múltiplas tabelas relacionais (pedidos, produtos, pagamentos, avaliações, clientes, vendedores)

## 📁 Sobre os Dados

O dataset contém múltiplas tabelas relacionais com informações sobre:
- Pedidos (`orders`)
- Clientes (`customers`)
- Produtos (`products`)
- Pagamentos (`payments`)
- Avaliações (`reviews`)
- Entregas (`order_items`)
- Vendedores (`sellers`)

---

## 🛠️ Tecnologias Usadas

- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📌 Principais Análises e Insights

### 📦 Categorias Mais Vendidas
- As categorias **"bed_bath_table"**, **"health_beauty"** e **"sports_leisure"** lideram as vendas.
- Indicam interesse do consumidor por conforto, bem-estar e lazer.

### 🚚 Tempo de Entrega por Estado
- Estados do Norte e Nordeste apresentam **tempo médio de entrega significativamente maior**.
- Isso sugere oportunidades para **melhoria na malha logística**.

### 💬 Atrasos vs Avaliação do Cliente
- Clientes que receberam pedidos com atraso deram, em média, **notas menores**.
- Existe uma **correlação direta entre entrega pontual e satisfação**.

---

## ✅ Conclusão

A análise demonstra como a integração de diferentes fontes de dados permite:

- Mapear gargalos logísticos
- Identificar segmentos com alto valor comercial
- Compreender os fatores que afetam a satisfação do cliente

---

## 📎 Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/olist-ecommerce-analysis.git
