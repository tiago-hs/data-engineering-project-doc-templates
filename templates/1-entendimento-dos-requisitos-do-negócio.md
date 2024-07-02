{{ Nome do Projeto }}

Compreensão do Negócio

{{ Equipe envolvida }}

| Nome | Slack | E-mail |
| ---- | ----- | ------ |
|      |       |        |
|      |       |        |

{{ Versão do Documento }}

{{DATA}}

Histórico de Revisões

| Versão | Autor | Data | Descrição |
| ------ | ----- | ---- | --------- |
|        |       |      |           |
|        |       |      |           |
|        |       |      |           |

_Esta fase inicial foca em compreender os objetivos e requisitos do projeto do ponto de vista do
negócio, convertendo esse conhecimento em uma definição do problema de engenharia/análise de dados e
um plano preliminar projetado para atingir os objetivos._

_Nosso principal objetivo, tanto como engenheiros, quanto como analistas, é entender completamente,
do ponto de vista do negócio, o que o cliente realmente deseja alcançar. Muitas vezes, o cliente tem
muitos objetivos e restrições concorrentes que devem ser equilibrados adequadamente. Nosso objetivo
é descobrir fatores importantes, no início, que podem influenciar o resultado do projeto. Uma
possível consequência de negligenciar esta etapa é despender um grande esforço produzindo as
respostas certas para as perguntas erradas._

# Contexto

_Registre qualquer informação conhecida sobre a situação atual no início do projeto. Já existe uma
solução em vigor? Descreva quaisquer soluções em vigor e por que estão buscando uma nova solução. O
que a nova solução deve melhorar?_

# Objetivos de Negócio

_Descreva o objetivo principal do cliente, do ponto de vista do negócio. Além do objetivo principal
de negócio, geralmente há outras questões empresariais relacionadas que o cliente gostaria de
abordar – inclua-as aqui também._

# Critérios de Sucesso para o Negócio

_Descreva os critérios para um resultado bem-sucedido ou útil do projeto do ponto de vista do
negócio. Isso pode ser bastante específico e mensurável objetivamente, por exemplo, "criar uma base
de receita e margem financeira". Caso contrário, pode ser mais subjetivo como: "criar um conjunto de
dados para autoatendimento para nos ajudar a fazer X". Quem avaliará os resultados finais?_

# Inventário de Recursos

_Liste os recursos disponíveis para o projeto, incluindo pessoal (especialistas em negócios,
especialistas em analise de dados, suporte técnico, especialistas em engenharia de dados), dados
(datasets, acesso a dados, armazenados ou operacionais), recursos de computação (plataformas de
hardware) e software (ferramentas de engenharia e análise de dados, outros softwares relevantes)._

## Pessoal

| Nome | Unidade de Negócio | Função                      | Informações de Contato |
| ---- | ------------------ | --------------------------- | ---------------------- |
|      |                    | Função da pessoa no projeto | email/telefone         |
|      |                    |                             |                        |
|      |                    |                             |                        |
|      |                    |                             |                        |

## Dados

| Origem                                     | Tipo            | Forma            | Tamanho | Descrição                                                                          | Armazenamento | Contatos                                   |
| ------------------------------------------ | --------------- | ---------------- | ------- | ---------------------------------------------------------------------------------- | ------------- | ------------------------------------------ |
| Descreva brevemente como acessar os dados. | CSV/Parquet/etc | Tabular/JSON/etc |         | Descreva brevemente do que os dados consistem. Com que frequência são atualizados? |               | <br>Liste qualquer pessoa que possa ajudar |
|                                            |                 |                  |         |                                                                                    |               |                                            |
|                                            |                 |                  |         |                                                                                    |               |                                            |
|                                            |                 |                  |         |                                                                                    |               |                                            |

## Software

_Liste qualquer software relevante para completar os objetivos._

- _AWS EMR_
- _Apache Airflow_
- _Databricks_
- _Etc._

# Requisitos

_Liste todos os requisitos do projeto, por exemplo: ticket Jira, cronograma de conclusão,
compreensibilidade e qualidade dos resultados, segurança, bem como questões relacionadas a
sensibilidade dos dados. Como parte desse resultado, certifique-se de que você pode usar os dados.
Além disso, certifique-se de incluir – frequência de carregamento de dados, transformações,
fórmulas, como lidar com dados ausentes/ruins. Alguns requisitos podem não ser identificados até a
próxima fase, "Compreensão dos Dados"._

# Premissas

_Liste as premissas feitas pelo projeto. Estas podem ser premissas sobre os dados que podem ser
verificadas durante o planejamento, mas também podem incluir premissas não verificáveis sobre o
negócio relacionado ao projeto. É particularmente importante listar estas últimas se elas afetarem a
validade dos resultados._

# Restrições

_Liste as restrições do projeto. Estas podem ser restrições sobre a disponibilidade de recursos, mas
também podem incluir restrições tecnológicas._

- _Você tem todos os acessos necessárias?_
- _Você verificou todas as restrições legais sobre o uso dos dados?_
- _Todas as restrições financeiras estão cobertas no orçamento do projeto?_

# Riscos e Contingências

_Liste os riscos ou eventos que podem atrasar o projeto ou causar seu fracasso. Liste os planos de
contingência correspondentes, que ações serão tomadas se esses riscos ou eventos ocorrerem._

# Terminologia

_Compile um glossário de terminologia empresarial relevante, que faz parte da compreensão
empresarial disponível para o projeto. Construir esse glossário é um exercício útil de “elicitação
de conhecimento” e educação._

# Custos e Benefícios

_Construa uma análise de custo-benefício para o projeto, que compare os custos do projeto com os
benefícios potenciais para o negócio se ele for bem-sucedido. A comparação deve ser o mais
específica possível. Sinta-se à vontade para usar valores monetários quando aplicável._

- _Cronograma - E se o projeto demorar mais do que o previsto?_
- _Financeiro - E se o projeto enfrentar problemas orçamentários?_
- _Dados - E se os dados forem de baixa qualidade ou cobertura?_
- _Resultados - E se os resultados iniciais forem abaixo esperado?_

# Metas do Projeto

_Descreva as metas do projeto em termos técnicos. A meta técnica pode ser realizar a ingestão e
integração de dados para X, Y, Z equipes consumidoras, ou implementar uma nova análise acessível
para monitoramento dos times de performance._

# Resultados do Projeto

_Descreva os resultados do projeto para possibilitar o alcance dos objetivos do negócio. Quais dados
serão produzidos? Quais pipelines precisam ser implementados? Relatórios?_

# Critérios de Sucesso do Projeto

_Defina os critérios para um resultado bem-sucedido do projeto em termos técnicos. Assim como no
tópico "Critérios de Sucesso para o Negócio", pode ser necessário descrevê-los em termos subjetivos,
caso em que a pessoa ou pessoas que farão o julgamento subjetivo devem ser identificadas._
