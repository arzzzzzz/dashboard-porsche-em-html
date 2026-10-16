# dashboard-porsche-em-html
Projeto para a DIO sobre dashboard com ChatGPT
# Porsche Sales Dashboard

## Sobre o projeto

Este projeto consiste em uma dashboard interativa para análise de vendas de veículos Porsche, desenvolvida como estudo de visualização de dados e construção de dashboards com auxílio de inteligência artificial.

O objetivo foi transformar uma base de dados em uma interface visualmente organizada, facilitando a identificação de padrões de vendas por cidade, ano do modelo, estado e forma de pagamento.

O design foi inspirado no site oficial da Porsche Brasil, buscando transmitir elegância, sofisticação e clareza na apresentação das informações.

## Perguntas de negócio

Foram escolhidas três perguntas principais para orientar a construção da dashboard:

**1. Quais são os modelos Porsche mais vendidos em cada cidade?**

Essa pergunta permite identificar quais veículos possuem maior volume de vendas em diferentes localidades, ajudando a compreender as preferências de cada mercado.

**2. Qual ano-modelo apresentou o maior número de vendas em determinado período?**

O objetivo é identificar quais anos-modelo tiveram maior saída dentro de um intervalo de tempo, permitindo observar a distribuição das vendas e possíveis tendências.

**3. Quais modelos são mais populares em cada cidade?**

Essa análise busca destacar os veículos com maior presença nas vendas de cada cidade, facilitando a comparação entre localidades e a identificação de padrões de consumo.

Essas perguntas foram escolhidas por permitirem explorar diferentes dimensões da base de dados e transformar registros individuais em informações úteis para a análise comercial.

## Indicadores e filtros

A dashboard apresenta indicadores e gráficos voltados à análise do volume de vendas, dos modelos mais vendidos e da distribuição por ano-modelo.

Foram incluídos os seguintes filtros interativos:

- **Modelo Porsche:** permite analisar um modelo específico.
- **Year:** filtra os veículos pelo ano-modelo.
- **Estado:** restringe a análise a uma unidade federativa.
- **Pay Method:** permite observar as vendas de acordo com a forma de pagamento.

Os filtros permitem explorar diferentes recortes dos dados e observar como os resultados se comportam conforme os critérios selecionados.

## Desenvolvimento com inteligência artificial

O ChatGPT foi utilizado como apoio na criação da dashboard em HTML, CSS e JavaScript. A ferramenta auxiliou na estruturação da interface, na organização dos gráficos e na implementação dos elementos interativos.

### Prompt inicial

O prompt utilizado para orientar a criação da dashboard foi:

> Utilizando o recurso de Canvas, renderize uma dashboard em HTML.
>
> **Filtros**
> - Modelo da Porsche;
> - Modelo do Ano (Year);
> - Estado;
> - Pay Method.
>
> **Perguntas de negócio e KPIs**
> - Quais os principais modelos de carro vendidos por cidade?
> - Qual ano-modelo teve maior saída em determinado período?
> - Quais são os modelos mais populares em cada cidade?
>
> Para o UI/UX, utilize como referência o site oficial da Porsche Brasil: https://www.porsche.com/brazil/pt/.
>
> A dashboard deve transmitir elegância e sofisticação.

### Ajustes realizados

Durante o processo, o objetivo foi refinar a apresentação visual e tornar a dashboard mais adequada à proposta de análise comercial. A identidade visual foi direcionada para uma estética minimalista, com cores sóbrias, detalhes em vermelho e uma hierarquia visual inspirada na comunicação da Porsche.

Também foram definidos os filtros e as perguntas de negócio que orientariam os indicadores e os gráficos, buscando facilitar a exploração dos dados.

O resultado foi uma dashboard em HTML com componentes interativos, desenvolvida com auxílio do ChatGPT.

## Tratamento dos dados

A base de vendas foi fornecida em uma planilha Excel. Antes de utilizar os dados na dashboard, foi necessário considerar a consistência dos campos, especialmente os relacionados às datas.

Foram identificados registros com datas inválidas (`INVALID`), que exigem cuidado em análises temporais. Esses registros não devem ser atribuídos a períodos específicos sem que exista uma data válida.

Na análise por período, os registros sem datas válidas são desconsiderados, evitando distorções nos resultados temporais.


