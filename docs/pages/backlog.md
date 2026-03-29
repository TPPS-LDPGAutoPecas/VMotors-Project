<span style="background-color:#96191d; color:white; font-size:0.8em; font-weight: bold; padding:2px 6px; border-radius:4px;">Versão 1.0</span>

# Backlog do Produto

## 1.1 - Backlog Geral

O backlog de produto é uma lista dinâmica e priorizada que contém todos os requisitos, funcionalidades, melhorias e correções que serão necessárias para o desenvolvimento de um produto. Ele funciona como um guia para a equipe de desenvolvimento, servindo de referência para todas as tarefas que precisam ser realizadas ao longo do ciclo de vida do projeto. Essa lista não é fixa, mas sim atualizável conforme o produto evolui e novas necessidades surgem, garantindo que o time esteja sempre alinhado às prioridades e expectativas do projeto.

Dentro do backlog, um dos principais elementos são as User Stories (US), ou histórias de usuário. As histórias de usuário descrevem, em uma linguagem simples e direta, as necessidades do usuário final de forma que todos da equipe possam compreender o valor de cada funcionalidade. Elas são compostas por três elementos principais: quem é o usuário, o que ele deseja fazer e qual o benefício dessa ação. Esse formato ajuda a manter o foco nas necessidades dos usuários, incentivando a equipe a desenvolver soluções que realmente agreguem valor ao produto.

As User Stories mais complexas ou que englobam várias funcionalidades estão agrupadas em Épicos. Um épico é uma descrição ampla de uma necessidade maior, que será posteriormente dividida em histórias menores e mais detalhadas. Esse processo de desmembramento ajuda a equipe a compreender o escopo do projeto e a definir prioridades para desenvolver partes do produto em blocos mais manejáveis. Épicos podem ser definidos com base nas principais funcionalidades ou objetivos do produto, e cada um pode se desdobrar em várias histórias de usuário que detalham as tarefas específicas.

Por sua vez, os Temas funcionam como agrupamentos de histórias e épicos que compartilham um propósito ou um objetivo comum dentro do produto. Eles são úteis para organizar o backlog em seções que representem áreas ou funcionalidades do sistema, facilitando a priorização de desenvolvimento de acordo com as metas do projeto. Diferente dos épicos, que normalmente possuem um escopo mais restrito, os temas são mais amplos e podem abranger múltiplos épicos e histórias de usuário, fornecendo uma visão geral das grandes áreas do produto.

### 1.1.1 - Temas:

| Código | Título                               | Descrição                                                            |
| ------ | ------------------------------------ | -------------------------------------------------------------------- |
| TM01   | Experiência do Usuário com a Empresa | Funcionalidades que permitem ao usuário interagir com a empresa.     |
| TM02   | Gestão do Software                   | Funcionalidades voltadas para a administração do site institucional. |

### 1.1.2 - Épicos:

| Código | Tema Associado | Título                         | Descrição                                                                                                                                                                                                                                                                                                                                                                                                     |
| ------ | -------------- | ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP01   | TM02           | Configurações de Negócio e BI  | Engloba o desenvolvimento do dashboard administrativo e das ferramentas de Inteligência de Negócio (BI) que darão autonomia à equipe da Vellux Motors. O objetivo principal é permitir que a administração do sistema possa parametrizar as regras de negócio de forma dinâmica. Além disso, provê as ferramentas de análise de dados necessárias para monitorar a saúde financeira e operacional da oficina. |
| EP02   | TM02           | Gestão de Atendimento          | Contempla a gestão operacional do atendimento da oficina, permitindo atualizar o status de agendamentos em calendário, gerar orçamentos detalhados dos serviços e designar mecânicos responsáveis por cada ordem de serviço para garantir organização, comunicação com o cliente e acompanhamento eficiente da equipe.                                                                                        |
| EP03   | TM01           | Monitoramento do Veículo       | Concentra-se no fornecimento das informações de forma transparente do veículo para o cliente. A ideia deste épico é criar um ambiente no sistema onde o usuário possa gerenciar as informações dos seus veículos pessoais.                                                                                                                                                                                    |
| EP04   | TM01           | Engajamento e Relacionamento   | Disponibilidade de mecanismos de interação entre cliente e oficina, como notificações, acompanhamento de serviços, avaliações e vinculação com canais de comunicação para promover engajamento contínuo e fortalecer o relacionamento com o cliente.                                                                                                                                                          |
| EP05   | TM02           | Interface do Mecânico          | Disponibilidade de uma visão organizada do fluxo de trabalho, permitindo consulta da lista de serviços prestados.                                                                                                                                                                                                                                                                                             |
| EP06   | TM02           | Segurança e Controle de Acesso | Engloba mecanismos de autenticação de usuários e controle de permissões, com o objetivo de permitir acesso seguro ao sistema, conforme os perfis estabelecidos.                                                                                                                                                                                                                                               |

### 1.1.3 - User Story dos Requisitos Funcionais

| Código | Requisito Funcional Associado | Épico Associado | User Story                                                                                                                                                                                                               |
| ------ | ----------------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| US01   | RF01                          | EP01            | Eu, como administrador do sistema, quero manipular as informações do catálogo de serviços disponíveis no site para que eu mantenha os serviços sempre atualizados.                                                       |
| US02   | RF08                          | EP01            | Eu, como administrador do sistema, quero consultar, por meio de gráficos, o faturamento bruto e o volume de serviços com filtros por período mensal e anual, para que eu possa planejar decisões futuras do meu negócio. |
| US03   | RF11                          | EP01            | Eu, como administrador do sistema, quero ativar ou desativar funções do meu sistema para que o site se adapte com a demanda da oficina e regras de negócio do momento.                                                   |
| US04   | RF03                          | EP02            | Eu, como administrador do sistema, quero atualizar a situação de agendamentos dispostos em um calendário no site para que eu possa planejar as revisões da semana.                                                       |
| US05   | RF05                          | EP02            | Eu, como administrador do sistema, quero gerar um documento de orçamento detalhado do serviço a ser cobrado para que eu possa enviar para o cliente do serviço a ser realizado.                                          |
| US06   | RF12                          | EP02            | Eu, como administrador do sistema, quero designar qual mecânico será responsável por cada ordem de serviço para que eu possa monitorar a equipe.                                                                         |
| US07   | RF06                          | EP03            | Eu, como cliente, quero consultar o histórico de manutenções que já realizei no meu veículo para que eu possa olhar os serviços que já solicitei.                                                                        |
| US08   | RF07                          | EP03            | Eu, como cliente, gostaria de visualizar o status das manutenções, para que eu possa acompanhar o progresso do serviço.                                                                                                  |
| US09   | RF09                          | EP03            | Eu, como cliente, quero registrar os dados dos meus veículos para que eu possa consultar as interações que a oficina teve com o veículo.                                                                                 |
| US10   | RF10                          | EP04            | Eu, como administrador do sistema, quero atualizar os meios de contato para a oficina para que o site sempre mantenha o direcionamento ao atendimento atualizado.                                                        |
| US11   | RF13                          | EP04            | Eu, como cliente, quero receber notificações automáticas sobre prazos de manutenções futuras para que eu possa manter a saúde do meu veículo em dia.                                                                     |
| US12   | RF14                          | EP04            | Eu, como cliente, quero avaliar a prestação de serviço e dos mecânicos responsáveis para que a oficina possa utilizar os dados para melhoria.                                                                            |
| US13   | RF15                          | EP05            | Eu, como mecânico, quero visualizar minha lista de serviços para que eu possa organizar o meu fluxo de trabalho e acompanhar minhas comissões.                                                                           |
| US14   | RF02                          | EP06            | Eu, como administrador do sistema, quero me autenticar na plataforma para ter acesso aos controles administrativos do site.                                                                                              |
| US15   | RF04                          | EP06            | Eu, como administrador do sistema, quero restringir as funcionalidades do site para diferentes perfis para que eu mantenha o acesso administrativo seguro de usuários não autorizados.                                   |

---

## Histórico de Versão

Data       | Versão | Autor(es) | Mudanças
---------- | ------ | --------- | --------
28/03/2026 | `1.0`  | Arthur, Daniel, Davi, Marcella, Vinicius, Yves | Criação do documento e adição dos tópicos básicos       |
