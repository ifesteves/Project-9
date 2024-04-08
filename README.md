# Projeto de Análise do Comportamento do Usuário em um Aplicativo de uma Startup de Produtos Alimentícios

## Descrição do Projeto
Este projeto tem como objetivo analisar o comportamento do usuário em um aplicativo de uma startup que vende produtos alimentícios. Primeiramente, será estudado o funil de vendas para entender como os usuários interagem com o aplicativo e quantos chegam à etapa de compra. Em seguida, serão analisados os resultados de um teste A/A/B para determinar qual conjunto de fontes de design produz melhores resultados.

## Dados Utilizados
Os dados utilizados neste projeto estão disponíveis no arquivo CSV:

- `logs_exp_us.csv`: Contém registros de ações do usuário ou eventos, incluindo o nome do evento, identificador de usuário exclusivo, hora do evento e número do experimento.

## Passo 1: Preparação dos Dados
- Renomear as colunas para uma melhor compreensão.
- Verificar e corrigir valores ausentes e tipos de dados, se necessário.
- Adicionar colunas de data e hora e uma coluna separada para datas.

## Passo 2: Estudo e Verificação dos Dados
- Verificar a quantidade de eventos e usuários nos registros.
- Calcular o número médio de eventos por usuário.
- Identificar o período de tempo coberto pelos dados e garantir que estejam completos.
- Verificar a presença de usuários em todos os grupos experimentais.

## Passo 3: Estudo do Funil de Eventos
- Identificar e classificar os eventos por frequência.
- Encontrar o número de usuários que executaram cada evento e calcular a proporção de usuários.
- Analisar a ordem dos eventos e calcular a parcela de usuários que passam de uma etapa para a próxima.
- Identificar em qual fase há maior perda de usuários e calcular a parcela de usuários que completam todo o caminho.

## Passo 4: Estudo dos Resultados do Experimento
- Verificar a quantidade de usuários em cada grupo experimental.
- Analisar se há uma diferença estatisticamente significativa entre os grupos de controle no teste A/A.
- Analisar a proporção de usuários que realizaram o evento mais popular em cada grupo e verificar a diferença entre eles.
- Comparar os resultados do grupo com fontes alteradas com os grupos de controle individualmente e em conjunto.

## Nível de Significância
O nível de significância estatística padrão de 0,05 será utilizado para testar as hipóteses estatísticas. Será calculado o número de testes de hipóteses realizados e, se necessário, será ajustado o nível de significância para reduzir o risco de resultados falsos.

Ao concluir este projeto, serão demonstradas habilidades em análise de dados, estatística e interpretação de resultados experimentais.
