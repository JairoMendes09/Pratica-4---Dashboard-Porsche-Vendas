# Pratica-4---Dashboard-Porsche-Vendas
Dashboard em html de vendas realizadas de Porsche
# 🏎️ Porsche | Sales Intelligence & Executive Dashboard

Dashboard web interativo desenvolvido para a análise de inteligência de vendas e monitoramento de desempenho comercial da marca Porsche, permitindo filtragem dinâmica, acompanhamento de KPIs e exportação de dados analíticos.

---

## 🎯 Sobre o Projeto

Este projeto tem como objetivo consolidar dados transacionais de vendas de veículos de luxo em uma interface moderna e responsiva (*Single Page Application*). A aplicação foi construída para auxiliar gestores e analistas na tomada de decisões estratégicas por meio de filtros em cascata, visualização de barras comparativas por modelo, localização, forma de pagamento e status de entrega.

---

## ⚙️ Funcionalidades Principais

1. **Filtros Dinâmicos em Cascata:**
   * Segmentação cruzada por Mês da Venda, Ano da Venda, Ano do Modelo, Modelo do Veículo, Forma de Pagamento, Estado e Status.
2. **Cartões de KPIs (Indicadores Chave de Desempenho):**
   * Quantidade total de veículos vendidos (ajustada em tempo real conforme os filtros).
   * Valor total faturado (em dólares americanos - US$).
3. **Gráficos e Indicadores Comerciais:**
   * Modelos mais vendidos.
   * Volume de vendas por Estado (UF).
   * Formas de pagamento mais utilizadas.
   * Distribuição por status operacional da venda (*Delivered*, *In Transit*, *Pending*, *Cancelled*, etc.).
4. **Tabela de Detalhamento e Exportação:**
   * Listagem detalhada de registros com ordenação cronológica.
   * Funcionalidade de **Exportação para CSV** baseada no recorte dos filtros aplicados.

---

## 📂 Estrutura do Arquivo HTML

O projeto está encapsulado em um único arquivo estruturado contendo:
* **`HTML5`**: Marcação semântica da estrutura executiva.
* **`CSS3 Moderno`**: Estilização inspirada na identidade visual da Porsche (escala de cinza corporativa, detalhes em vermelho característico `--red: #d5001c`, design responsivo com *Grid* e *Flexbox*).
* **`JavaScript Vanilla (ES6+)`**: Motor de reatividade responsável pelo gerenciamento do estado dos filtros, cálculos agregados em memória, renderização dinâmica de barras e manipulação de arquivos CSV.

---

## 📊 Dicionário de Dados da Base

Cada registro comercial na base de dados transacional contempla os seguintes atributos:

| Coluna / Propriedade | Tipo | Descrição |
| :--- | :--- | :--- |
| `date` | Data (AAAA-MM-DD) | Data em que a venda foi efetuada. |
| `model` | Texto | Modelo do veículo Porsche (ex: *911 Turbo S*, *Taycan*, *Cayenne*, *718 Cayman*). |
| `modelYear` | Numérico | Ano de fabricação do modelo do veículo. |
| `price` | Numérico (USD) | Preço de comercialização do veículo em dólares americanos. |
| `mileage` | Numérico (km) | Quilometragem atual do veículo no momento da venda. |
| `payment` | Texto | Modalidade de pagamento (ex: *Wire Transfer*, *Credit Card*, *Cash*, *Financing*). |
| `city` | Texto | Cidade onde a transação ou concessionária está localizada. |
| `state` | Texto (Sigla) | Estado federativo dos EUA (ex: *CA*, *TX*, *FL*, *NY*). |
| `status` | Texto | Status logístico/comercial (*Delivered*, *Pending*, *In Transit*, *Cancelled*, etc.). |

---

## 🛠️ Tecnologias Utilizadas
* **HTML5 & CSS3:** Construção e estilização de interfaces executivas.
* **JavaScript (ES6):** Manipulação de DOM, algoritmos de agrupamento (*aggregation*) e geração nativa de Blob/CSV.
* **Git & GitHub:** Versionamento de código e documentação.

---

## 🚀 Como Utilizar a Aplicação

1. Faça o download ou clone este repositório contendo o arquivo `Dashboard_Vendas_Porsche.html`.
2. Dê um duplo clique no arquivo para abri-lo em qualquer navegador web moderno (Google Chrome, Microsoft Edge, Firefox, Safari).
3. Utilize os seletores no painel superior para filtrar as vendas por período, modelo ou estado.
4. Clique no botão **"Exportar dados filtrados CSV"** caso deseje baixar a base tratada para análises complementares em softwares como Excel ou Power BI.

---

## 📌 Licença
Este projeto é de uso educacional e portfólio profissional. Sinta-se livre para utilizar, modificar e adaptar o código para seus estudos em análise de dados e desenvolvimento web!
