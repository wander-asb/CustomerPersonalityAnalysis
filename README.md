# Customer Personality Analysis

<p align="center">
  <img width="780" height="300" src="[[https://www.jornalismo.ufv.br/cinecom/wp-content/uploads/2021/06/reality-show.jpg](https://miro.medium.com/v2/resize:fit:1200/0*VTBz1Op6jnk0_wZ4.jpg)](https://storage.googleapis.com/kaggle-datasets-images/1546318/2549419/519ae15c262818cdd94fa315325858aa/dataset-cover.png?t=2021-08-22-18-33-50)">
</p>

## Storytelling:

Havia uma vez uma pequena loja de brinquedos em uma encantadora rua de paralelepípedos. O dono, um senhor de cabelos grisalhos chamado Sr. Bernard, estava sempre preocupado em entender melhor seus clientes. Ele percebeu que cada criança que entrava em sua loja era única, com gostos e preferências diferentes. Determinado a oferecer a melhor experiência possível, Sr. Bernard decidiu embarcar em uma jornada de descoberta.

Ele começou a observar atentamente seus clientes, conversando com eles e fazendo anotações em um caderno antigo. Logo, ele começou a notar padrões intrigantes. Algumas crianças adoravam brinquedos coloridos e barulhentos, enquanto outras preferiam brinquedos mais silenciosos e educativos. Foi então que ele teve uma ideia brilhante - Análise de Personalidade do Cliente.


## Contexto
Análise de Personalidade do Cliente é uma análise detalhada dos clientes ideais de uma empresa. Isso ajuda um negócio a entender melhor seus clientes e facilita a modificação de produtos de acordo com as necessidades específicas, comportamentos e preocupações de diferentes tipos de clientes.

A análise de personalidade do cliente ajuda um negócio a modificar seu produto com base nos clientes-alvo de diferentes segmentos de clientes. Por exemplo, em vez de gastar dinheiro para comercializar um novo produto para todos os clientes no banco de dados da empresa, uma empresa pode analisar qual segmento de clientes é mais propenso a comprar o produto e depois comercializar o produto apenas nesse segmento específico.

## Descrição de Features

- People
  - ID: Customer's unique identifier
  - Year_Birth: Customer's birth year
  - Education: Customer's education level
  - Marital_Status: Customer's marital status
  - Income: Customer's yearly household income
  - Kidhome: Number of children in customer's household
  - Teenhome: Number of teenagers in customer's household
  - Dt_Customer: Date of customer's enrollment with the company
  - Recency: Number of days since customer's last purchase
  - Complain: 1 if the customer complained in the last 2 years, 0 otherwise

- Products
  - MntWines: Amount spent on wine in last 2 years
  - MntFruits: Amount spent on fruits in last 2 years
  - MntMeatProducts: Amount spent on meat in last 2 years
  - MntFishProducts: Amount spent on fish in last 2 years
  - MntSweetProducts: Amount spent on sweets in last 2 years
  - MntGoldProds: Amount spent on gold in last 2 years


- Promotion
  - NumDealsPurchases: Number of purchases made with a discount
  - AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
  - AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
  - AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
  - AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
  - AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
  - Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

- Place
  - NumWebPurchases: Number of purchases made through the company’s website
  - NumCatalogPurchases: Number of purchases made using a catalogue
  - NumStorePurchases: Number of purchases made directly in stores
  - NumWebVisitsMonth: Number of visits to company’s website in the last month



 
**História de Usuário: Análise de Desempenho de Clientes no Power BI**

Como um analista de marketing da empresa de vinhos gourmet, desejo criar indicadores no Power BI para entender melhor o perfil e o comportamento dos nossos clientes, a fim de direcionar estratégias de marketing de forma mais eficaz e aumentar as vendas.

**Objetivo:**
- Realizar tratamentos de dados para garantir a qualidade das análises.
- Desenvolver indicadores-chave de desempenho (KPIs) que nos ajudem a compreender o perfil e comportamento dos clientes.


**Indicadores a serem criados:**

1. **Idade Média dos Clientes:** Calculado com base no ano de nascimento dos clientes para entender a faixa etária predominante em nossa base de clientes.

2. **Nível Médio de Educação dos Clientes:** Determinado a partir do nível de escolaridade dos clientes para compreender o grau de instrução predominante.

3. **Estado Civil Predominante dos Clientes:** Análise da distribuição dos clientes por estado civil para identificar se temos um público majoritariamente casado, solteiro, divorciado, etc.

4. **Renda Média Anual dos Clientes:** Calculada com base na renda anual dos clientes para entender o poder aquisitivo médio de nossa base.

5. **Número Médio de Filhos nos Lares dos Clientes:** Calculado a partir do número de crianças e adolescentes nos lares dos clientes para compreender o tamanho médio das famílias.

6. **Recência Média das Compras:** Média do tempo decorrido desde a última compra de cada cliente para entender a frequência de compras.

7. **Taxa de Reclamações:** Percentual de clientes que registraram reclamações nos últimos dois anos para avaliar a satisfação e identificar áreas de melhoria.

8. **Total Gasto em Categorias de Produtos:** Análise do montante gasto pelos clientes em diferentes categorias de produtos (vinhos, frutas, carne, peixe, doces e produtos de ouro) nos últimos dois anos.

9. **Número Médio de Compras com Desconto:** Média do número de compras realizadas com desconto para avaliar a eficácia das campanhas promocionais.

10. **Taxa de Resposta às Campanhas:** Percentual de clientes que aceitaram as ofertas nas diferentes campanhas promocionais para avaliar o engajamento dos clientes.

11. **Canal de Compra Predominante:** Análise da distribuição dos clientes pelos canais de compra (website, catálogo, lojas físicas) para entender as preferências de compra.

12. **Número Médio de Visitas ao Website por Mês:** Média do número de visitas ao website da empresa nos últimos meses para avaliar o engajamento online dos clientes.



