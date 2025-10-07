# Teste de Performance - PAA (Plano de Ação Anual)

Este repositório contém os testes de performance realizados com o Apache JMeter no ambiente de (PROD) da aplicação PAA.

## Ambiente testado

[https://paa.qualitin.com/](https://paa.qualitin.com/)

## Estrutura do repositório

- `Scripts/` → Contém os arquivos `.jmx` utilizados para simulação de carga e estresse.
-  Para visualizar o resultados em formato HTTP Report, entrar na pasta de interesse, salvar e abrir o arquivo `index`.
- `README.md` → Este arquivo de documentação.

## Objetivo dos testes

Avaliar a performance e estabilidade da aplicação Stratega sob diferentes cargas de usuários simultâneos, simulando:

## Teste 01

| Cenário                          |                                                                    |
| -------------------------------- | ------------------------------------------------------------------ |
| Teste de carga                   | `Carga - 50 Usuários; Ramp-up: 60 segundos (1 minuto) `            |
| Teste de estresse                | `Estresse - 200 Usuários Simultâneos; Ramp-up: 600 (10 minutos)`   |


## Ferramentas utilizadas

- [Apache JMeter](https://jmeter.apache.org/) v5.6.3
- BlazeMeter v 6.6.7
- Navegador Google Chrome
- Windows 10

## Autor

Gabriella Braz — Analista de QA Jr  
📧 E-mail: gabriella.braz@quattrus.com
