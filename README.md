# 📈 Mercado-Ações – Análise com Google Planilhas

Este projeto utiliza **Google Sheets** para realizar uma análise completa de dados relacionados ao mercado de ações. O objetivo é organizar, filtrar, visualizar e interpretar dados financeiros de forma eficiente e visual. 🧮📊

---

## 🛠️ Funcionalidades Utilizadas no Google Sheets

### 📊 Manipulação de Dados
- Organização e estruturação das informações
- Aplicação de filtros e códigos personalizados
- Criação de páginas específicas para diferentes análises

### 📈 Análise de Dados
- Normalização de dados para consistência
- Cálculo de estatísticas e indicadores relevantes
- Aplicação de funções para insights automatizados

### 📐 Tabelas Dinâmicas
- Criação de tabelas dinâmicas para facilitar a análise interativa
- Agrupamento e sumarização de dados com facilidade

### 📊 Construção de Gráficos
- Visualizações com gráficos de barras, colunas, linhas, pizza etc.
- Auxilia na interpretação rápida dos dados

### 📊 Fórmulas básicas de cálculo

=SOMA(A1:A10)	Soma os valores das células A1 até A10.
=MÉDIA(A1:A10)	Calcula a média dos valores entre A1 e A10.
=MÍNIMO(A1:A10)	Retorna o menor valor no intervalo.
=MÁXIMO(A1:A10)	Retorna o maior valor no intervalo.
=CONT.VALORES(A1:A10)	Conta quantas células não estão vazias.
=CONT.SE(A1:A10;">10")	Conta quantas células têm valor maior que 10.

### 🔤 Manipulação de texto

=CONCATENAR(A1;B1)	Junta o conteúdo das células A1 e B1.
=TEXTO(A1;"dd/mm/aaaa")	Formata um número ou data como texto.
=ESQUERDA(A1;5)	Retorna os primeiros 5 caracteres de A1.
=DIREITA(A1;3)	Retorna os últimos 3 caracteres de A1.

### 🧠 Funções lógicas

=SE(A1>10;"OK";"Erro")	Retorna "OK" se A1 for maior que 10, senão "Erro".
=E(A1>10;B1<5)	Retorna VERDADEIRO se ambas as condições forem verdadeiras.
=OU(A1>10;B1<5)	Retorna VERDADEIRO se pelo menos uma condição for verdadeira.

### 🔁 Fórmulas de pesquisa e referência

=PROCV("Produto A";A2:B10;2;FALSO)	Procura "Produto A" na primeira coluna do intervalo e retorna da 2ª.
=ÍNDICE(A2:C10;2;3)	Retorna o valor da linha 2, coluna 3 do intervalo.
=CORRESP("João";A1:A10;0)	Retorna a posição de "João" no intervalo.
=FILTER(A2:B10;B2:B10>100)	Retorna linhas onde os valores da coluna B são maiores que 100.
=UNIQUE(A2:A100)	Remove valores duplicados e mostra apenas os únicos.
