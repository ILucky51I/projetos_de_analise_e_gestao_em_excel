# Projetos de Análise e Gestão em Excel

## Sobre o repositório

Este repositório reúne dois projetos desenvolvidos em **Microsoft Excel**, com foco em **organização de dados, análise de informações, indicadores e apoio à tomada de decisão**.

Os projetos exploram diferentes aplicações do Excel, desde o controle e acompanhamento de atividades até a análise de vendas por marketplace.

---

# Projetos

## 1. Ferramenta de Controle de Tarefas

Uma ferramenta desenvolvida em Excel para auxiliar no **gerenciamento e acompanhamento de tarefas**, permitindo visualizar atividades, responsáveis, status, prazos e prioridades.

### Objetivo

Criar uma ferramenta simples e visual para facilitar o acompanhamento das atividades de uma equipe, permitindo identificar:

- Atividades em andamento;
- Atividades concluídas;
- Atividades bloqueadas;
- Responsáveis pelas tarefas;
- Prazos;
- Prioridade das atividades;
- Total de atividades;
- Quantidade de atividades concluídas.

### Informações utilizadas

A ferramenta possui informações como:

| Campo | Descrição |
|---|---|
| Task | Nome da atividade |
| Owner | Responsável pela atividade |
| Status | Situação atual da atividade |
| Data | Data associada à atividade |
| Prioridade | Nível de prioridade da tarefa |

### Indicadores

O projeto também apresenta indicadores para facilitar o acompanhamento do trabalho, como:

- **Total de Atividades**
- **Atividades Concluídas**

Além disso, as tarefas são organizadas de acordo com seu status e prioridade.

### Status das atividades

Exemplos de status utilizados:

- `In Progress`
- `Stuck`
- `Done`

### Aplicações

A ferramenta pode ser utilizada para:

- Gestão de projetos;
- Acompanhamento de atividades;
- Organização de equipes;
- Controle de prazos;
- Priorização de tarefas;
- Acompanhamento de produtividade.

---

## 2. Análise de Vendas por Marketplace

Projeto desenvolvido em Excel para análise de vendas realizadas em diferentes **marketplaces**, utilizando dados de pedidos, clientes, produtos, marcas, valores, descontos, pagamentos e status dos pedidos.

### Objetivo

Analisar os dados de vendas e criar uma visão consolidada do desempenho comercial por marketplace e período.

O projeto permite explorar informações relacionadas a:

- Volume de vendas;
- Marketplaces;
- Produtos;
- Marcas;
- Clientes;
- Formas de pagamento;
- Status dos pedidos;
- Avaliação dos clientes;
- Datas das compras.

### Base de dados

A planilha possui uma base de pedidos contendo informações como:

| Campo | Descrição |
|---|---|
| Pedido_ID | Identificador do pedido |
| Cliente_Nome | Nome do cliente |
| Produto | Produto adquirido |
| Marca | Marca do produto |
| Preço(R$) | Preço do produto |
| Desconto(%) | Percentual de desconto |
| Quantidade | Quantidade de produtos |
| Total de Vendas | Valor total da venda |
| Marketplace | Canal onde a venda foi realizada |
| Forma_Pagamento | Forma de pagamento utilizada |
| Status_Pedido | Situação do pedido |
| Data_Compra | Data da compra |
| CEP_Entrega | CEP de entrega |
| Avaliação_Cliente | Nota atribuída pelo cliente |
| Comentário | Comentário realizado pelo cliente |

### Análise por Marketplace

O projeto possui uma área de análise dinâmica que permite visualizar o **total de vendas por mês**, possibilitando comparar o desempenho dos marketplaces ao longo do período analisado.

Entre os marketplaces presentes na base estão:

- Amazon
- Kabum
- Submarino
- Magazine Luiza

### Indicadores analisados

A base permite desenvolver análises como:

- Total de vendas;
- Vendas por marketplace;
- Vendas por mês;
- Vendas por produto;
- Vendas por marca;
- Quantidade de pedidos;
- Ticket médio;
- Descontos aplicados;
- Status dos pedidos;
- Formas de pagamento;
- Avaliação dos clientes.

### Aplicações

A análise pode ser utilizada para:

- Acompanhamento de vendas;
- Comparação entre marketplaces;
- Análise de desempenho comercial;
- Identificação de produtos com maior volume de vendas;
- Análise de comportamento dos clientes;
- Apoio à tomada de decisões comerciais.

---

# Tecnologias e ferramentas

Os projetos foram desenvolvidos utilizando principalmente:

- **Microsoft Excel**
- Tabelas
- Fórmulas
- Organização e tratamento de dados
- Indicadores
- Análise exploratória
- Tabelas dinâmicas
- Visualização de dados

---

# Estrutura do repositório

```text
projetos-excel/
│
├── Ferramenta de Controle de Tarefas.xlsx
│
├── Vendas por Marketplace Mês a Mês.xlsx
│
└── README.md
