# 📈 Simulador de Investimentos em Fundos Imobiliários

> Link:  
<a href = "https://github.com/wscaxinha/WS_INVEST.git" title = "Clique Aqui" target = "_blank">WS INVESTIMENTOS</a>

## 📝 Descrição

*Aplicar os conceitos fundamentais de Excel no desenvolvimento de um app de simulação de investimentos em Fundos Imobiliários (FIIs).*

A partir de uma compreensão como os **FIIs** funcionam e sobre as principais perguntas feitas sobre investimentos, houve uma necessidades de desenvolver uma planilha que auxilie o usuário a:

- Simular diferentes cenários de investimentos

- Compreender o o tempo do aporte mensal
- Valor total de investido
- Patrimônio acumulado ao longo do tempo
- Estimativa de dividendos mensais 
- Tomar decisões mais informadas sobre seus investimentos 

## 🎯 Objetivo

Desenvolver um **simulador financeiro em excel**, organizado e que permita:

 - Realizar calculos
 - Inserção de dados pelo usuário
 - Sugestão de aplicação
 - Simular investimentos

## 🌉 Estrutura da Planilha

A planilha é organizada **abas funcionais**:

 - Entrada de dados
 - Regras de negócio
 - Cálculos
 - Resultados

### 📂 Abas principais

`CONFIGURAÇÕES` |
`TIPOS PERFIS` |
`INVESTIMENTO MENSAL` |
`CENÁRIOS`



## 🚀 Boas Práticas

Durante o desenvolvimento da planilha, foram aplicadas boas práticas que visam organização, clareza e facilidade de manutenção, tais como:

 - **Células nomeadas**, utilizadas como variáveis globais, facilitando a compreensão das fórmulas

 - **Padronização e uniformidade visual**, melhorando a experiência do usuário

 - **tabelas de apoio**, centralizando regras de negócio e evitando duplicidade de informações
 
## 🧪 Fórmulas Utilizadas

### 💸 Função VF (Valor Futuro)

Utilizada para calcular o patrimônio acumulado ao logo do tempo.

```
=VF(taxa_mensal;qtde_anos*12;-aporte)
```
### 🔎 PROCV

Usada para buscar percentuais de acordo o tipo de investimento.

```
=PROCV(G3;$B:$E;4;)
```
### 🧮 SOMA

Usada para somar os valores de baseados no salário, tipo de  perfil é percentual sugerido.

```
=SOMA(D27:D32)
```
### 📷 Apresentação Visual

Nesta seção são apresentadas imagens do simulador, com o objetivo de demonstrar a estrutura da planilha e a organização. 

### 📌 Visão geral

<img src = "img\t1.PNG">

#

<img src = "img\t2.PNG">

### 📌 Tabela de Apoio

<img src = "img\t3.PNG">

## ✅ Conclusão

Este simulador mostra como o Excel pode ser usado na prática para organizar dados, automatizar cálculos financeiros e apoiar decisões de investimento. A ferramenta ajuda o usuário a visualizar melhor seus cenários e entender o impacto das suas escolhas financeiras.

> **Ano:** 2026
>
> **Ferramentas:** Excel + Visual Code
>
> Link:  
<a href = "https://github.com/wscaxinha/WS_INVEST.git" title = "Clique Aqui" target = "_blank">WS INVESTIMENTOS</a>

 








 

 



[def]: ws_invest/./img