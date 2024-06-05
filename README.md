# Relatório de Processamento de Dados

## Introdução

Este relatório é sobre o trabalho que fiz para organizar e analisar os dados. Vou explicar passo a passo o que foi feito.

## 1. Remoção de Colunas

Primeiro, eu removi algumas colunas que só tinham valores do tipo "Value" ou "Table". Essas colunas não eram úteis para o que precisávamos.

## 2. União de Tabelas

Depois, juntei várias tabelas em uma só. Isso facilitou muito a análise dos dados.

## 3. Unificação de Nome e Sobrenome

Vi que não precisava ter os nomes separados em "nome" e "sobrenome", então juntei tudo em um campo chamado "Nome Colaborador".

## 4. Separação e Ajuste de Endereço

Separei os dados de endereço em diferentes partes. Percebi que alguns traços nos dados não eram divisores de nome, então tive que ajustar um dos dados de endereço para que ficasse correto.

## 5. Alteração de Tipos de Dados

O Power Query detecta números como inteiros automaticamente. Mas, para campos como ID's ou números de endereço, eu mudei de inteiro para texto.

## 6. Substituição do Dado "Gerente"

A coluna "Gerente" não estava na base de dados. Então, usei a coluna "Super_ssn", dupliquei essa coluna e substituí os valores pelos nomes dos gerentes.

## 7. Análise de Supervisores e Colaboradores

Depois de analisar, encontrei a seguinte distribuição de colaboradores por supervisor:
- Supervisor Franklin: 9 colaboradores
- Supervisor James: 5 colaboradores
- Supervisor Jennifer: 2 colaboradores

## 8. Opção de Mescla de Dados

Foi solicitado verificar se era melhor mesclar os dados. Percebi que sim, pois usar a função "atribuir" duplicaria muitos valores, tornando os dados confusos.

## 9. Total de Horas por Projeto

Calculei o total de horas para cada projeto:
- Computerization: 55 horas
- Newbenefits: 55 horas
- ProductX: 52 horas e meia
- ProductZ: 50 horas
- ProductY: 37 horas e meia
- Reorganization: 25 horas

## Conclusão

Com este trabalho, consegui organizar e analisar os dados de forma clara. As decisões tomadas ajudaram a manter a integridade e utilidade das informações, permitindo uma análise eficiente.
