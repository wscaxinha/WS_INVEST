# 📈 Simulador de Investimentos em Fundos Imobiliários

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
 - Inserção de dados pelo usário
 - Simular investimentos

## 🌉 Estrutura da Planilha

A planilha é organizada **abas funcionais**:

 - Entrada de dados
 - Regras de negócio
 - Cálculos
 - Resultados

### 📂 Abas pricipais

`CONFIGURAÇÕES` |
`TIPOS PERFIS` |
`INVESTIMENTO MENSAL` |
`CENÁRIOS`



## ✅ Boas Práticas

Foram utilizadas **células nomeadas**, facilitando:

 - Leitura das fórmulas
 - Manutenção do projeto
 
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
### 🔎 SOMA

Usada para somar os valores de referêntes tipo de  perfil do investidor.

```
=SOMA(D27:D32)
```










 

 

