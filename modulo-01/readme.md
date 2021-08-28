# Módulo 1 - Introdução ao SCRUM

## Introdução a Gestão de Projetos e ao SCRUM

### Conceitos básicos

O desafio do desenvolvimento de software é tornar os objetivos de negócio em software.
Os objetivos de negócio são transformados em requisitos e depois passam pelo processo de desenvolvimento que podem conter as etapas abaixo para criar um software:

- Concepção
- Análise e Design
- Desenvolvimento
- Testes
- Implantação

### A realidade do desenvolvimento de software

As estatísticas dizem que:

- 20 % das funcionalidades do software costumam gerar 80 % ou mais do benefício esperado.
- 80 % das funcionalidades do software nunca, rararemente ou às vezes são utilizadas.

| Percentual | Uso da funcionalidades |
| ---------- | ---------------------- |
| 7 %        | Sempre                 |
| 13 %       | Frequentemente         |
| 16 %       | Às vezes               |
| 19 %       | Raramente              |
| 45 %       | Nunca                  |

### Gestão de Projetos Tradicional x Gestão de Projetos Ágil

#### Tradicional (Waterfall)

Só permite que o projeto avance quando uma fase está inteiramente completa.
As fases do projeto são:

1. Requirement (requirement doc, prepare use cases)
2. Design (software architecture, map the stackholders)
3. Implementation (construct the software, data storage & retrieval)
4. Verification (install, test and debug)
5. Maintenance (check erros, optmize capatibilities)

#### Ágil

Software construído por partes (incremental) e cada parte executa-se em um ciclo (iterativo)
As fases de cada ciclo:

1. Requisitos
2. Análise
3. Construção
4. Testes
5. Liberação

#### Diferenças de abordagem

| Tradicional                                                   | Ágil                                                                        |
| :------------------------------------------------------------ | :-------------------------------------------------------------------------- |
| Escopo definido na fase inicial do projeto (preditivo)        | Escopo definido ao longo do Projeto (Adaptativo)                            |
| Projeto é controlado por fases e marcos                       | Projeto é controlado por funcionalidades entregues                          |
| Cliente só vê o software funcionando na fase final do Projeto | Cliente pode ver parte do software funcionando na parte inicial do projeto. |
| Resistência a mudanças                                        | Mudanças constatntes de acordo com o feedback contínuos                     |

> Em projetos tradicionais, você corre o risco de descobrir que estava errado depois de meses. Com o SCRUM, você descobre que estava errado em no máximo 30 dias.

#### O que é ser Ágil

- Ágil não é ser rápido;
- Rapidez (mudança) e desembaraço;
- Fazer coisas complexas de forma simples;
- Equipe comprometida com os objetivos;
- Maior valor para o cliente;
- Ter capacidade de responder rapidamente a mudanças.

#### O que é o SCRUM

- SCRUM é um dos frameworks de gerenciamento de projetos ágeis;
- Projetos usando equipes pequenas e multidisciplinares produzem os melhores resultados.

#### Pilares do SCRUM

- **Transparência**
  - Conversar mais e escrever menos;
  - Demonstrar o software constantemente aos usuários e obter feedbacks constates.
- **Adaptação**
  - Requisitos mudam ao longo do tempo;
- **Inspeção**
  - Aprender progressivamente com o uso do software

#### Razões para adotar o SCRUM

- Desenvolvimento e entregue em partes menores (2 a 4 semanas), com constante feedback dos usuários;
- Melhor gerenciamento de riscos (redução de incertezas);
- Comprometimento, motivação e transparência da equipe (Daily Meeting);
- Maior valor para o negócio (priorização do backlog);
- Usuários envolvidos durante todo o ciclo;
- Aplicação das lições aprendidas (melhoria contínua).

#### Características do time SCRUM

- Equipes capazes de se auto-organizarem
- As tarefas são do time e todos sãos responsáveis
- Forte comprometimento com os resultados

## Papéis e Responsabilidades de cada um do time

#### Product Owner (PO)

- Representante da área de Negócios;
- PO não é um Comitê, é uma pessoa;
- Define as funcionalidades do software (Product Backlog);
- Prioriza as funcionalidades de acordo com o valor do negócio;
- Garante que o time de desenvolvimento entenda os itens dos Backlog no nível necessário.

#### Scrum Master (SM)

- Garantir o uso correto do SCRUM;
- Scrum Master não é Gerente de Projetos;
- Age como facilitador;
- Auxilia o Product Owner no planejamento e estimativas do backlog;
- Auxilia a equipe a remove impedimentos;
- Treina o time em autogerenciamento e interdisciplinaridade;

#### Time de Desenvolvimento (DEV; 3-9 pessoas)

- Possui habilidades suficientes para desenvolver, testar, criar e desenhar, ou seja, tudo que for necessário para entregar o software funcionando.

## Cerimônias do SCRUM

### Conceitos básicos da Cerimônias do SCRUM

#### Time Box

Tempo máximo para fazer uma cerimônia ou sprint

Exemplo:

- Daily Meeting com Time Box de no máximo 15 minutos;
- Sprint com Time Box de 30 dias corridos.

#### Sprint

O significado da palavra é corrida ou arrancada.
É o principal evento do SCRUM e cada Sprint tem o período de 30 dias corridos (ou menos).

Composição de uma Sprint:

- Planejamento da Sprint (Planning);
- Reuniões Diárias (Daily Meeting)
- Revisão da Sprint (Review)
- Retrospectiva da Sprint

### Cerimônia do Planejamento da Sprint

#### Participantes

- Product Owner
- Time DEV
- Scrum Master

#### Time Box para a Sprint

- Time Box de 8 horas para uma Sprint de 30 dias, as primeiras 4 horas são para decidir o que fazer e as outras 4 horas são para decidir como fazer.

#### Cerimônia

- Após a priorização do Backlog pelo Product Owner, as primeiras 4 horas são utilizadas para explicar o que ele quer, qual a importância.
- Nas próximas 4 horas no time DEV define como fazer, quanto tempo é necessário, uma das ferramentas para estimativas pode ser o Planning Poker.

### Reuniões Diárias (Daily Meeting)

#### Participantes da Reunião diária

- Product Owner (Opcional)
- Time DEV
- Scrum Master

#### Time Box da Reunião diária

- Time Box de no máximo de 15 minutos.

#### Cerimônia da Reunião diária

- O Time DEV responde a 3 perguntas:
  - O que fez no dia anterior
  - O que está programado para o dia
  - Se existe algum impedimento
- Reunião feita em pé e sempre no mesmo horário e local definido pelo time, também conhecida como Standup Meeting.
- Atualização do quadro KANBAN para visibilidade do andamento da sprint.

### Revisão da Sprint (Review)

#### Participantes da Revisão da Sprint

- Product Owner
- Time DEV
- Scrum Master
- Stakeholder (Opcional)

#### Time Box da Revisão da Sprint

- Time Box de no máximo de 4 horas (Sprint 30 dias).

#### Cerimônia da Revisão da Sprint

- Ocorre no último dia da Sprint;
- O Time DEV apresenta para o Product Owner (PO) o trabalho feito;
- Todo feedback sobre o desenvolvimento é registrado para a próxima Sprint;
- O Product Owner (PO) decide o que vai ou não para Produção.

### Retrospectiva da Sprint

#### Participantes Retrospectiva da Sprint

- Time DEV
- Product Owner
- Scrum Master

#### Time Box da Retrospectiva da Sprint

- Time Box de no máximo de 3 horas (Sprint 30 dias).

#### Cerimônia da Retrospectiva da Sprint

- Ocorre no último dia da Sprint;
- O Time DEV de maneira transparente se reune para falar sobre as lições aprendidas, quais erros ocorreram no desenvolvimento, na review, no planejamento da Sprint, ou dúvidas sobre informações que não foram esclarecidas com o Product Owner;

## Gestão de Projetos Tradicional x Ágil

### Diferença prática

#### Exemplo Nubank

##### Gestão de Projetos Tradicional

No planejamento inicial do projeto poderíamos ter todas as funcionalidades:

- Cartão de crédito;
- Benefícios;
- Conta digital;
- Empréstimos;

##### Gestão de Projetos Ágil

No planejamento inicial do projeto poderíamos o mínimo produto viável, ou seja, o mínimo esforço de desenvolvimento

- Cartão de crédito

Receber os feedbacks, melhorar a funcionalidade inicial e depois partir para a próxima funcionalidade, sempre ouvindo o cliente e vendo o que faz a diferença.
