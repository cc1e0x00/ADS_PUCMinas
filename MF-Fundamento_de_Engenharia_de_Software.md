# UNIDADE 1: CONCEITOS E PROCESSOS DE SOFTWARE
## Tema1: Introdução à Engenharia de Software

## Desafios e contribuições da área
O termo Engenharia de Software foi cunhado em 1968 na conferência da NATO/OTAN (North Atlantic Ttreaty  Organization). É espero que um engenheiro de software atue em três atribuições da área: Desenvolvimento, evolução e operação do software.

Uma atual definação de engenharia de softwere é definada pelo IEEE

> “[...] aplicação de um método sistemático, disciplinado e quantificável ao desenvolvimento, operação e manutenção de software; isto é, a aplicação da engenharia ao software.” IEEE Standard Computer Dictionary.


Um reporte da Caos report 2020 endereço algumas problemáticas de projetos de desenvolvimento de software

- 1/3 dos projectos de software são cancelados
- 1/2 dos projetos ultrapassam o orçamento ou o prazo previsto
- 1/6 dos projetos são bem sucedidos; entrengues com prazo e orçamentos previsto além de possuírem todos os requisitos acordados no ínicio do projeto

**Algumas da contribuições da engenharia de software**

Paradigmas de processo de desenvolvimento de software
- Processos ágeis
- Processos prescritivos

Criação de Padrões
- Padrões de projetos
- Padrões de arquiteturas de software
- Liguagens de padrões
- Templates de soluções (frameworks)

Paradigmas de trabalho em equipe
- Tradicionais como um líder/gerente
- Auto-organizáveis
- Squads
- De alto desempenho
- Distribuídas geograficamente

Métricas de qualidade de software
- Processo
- Produto
- Projeto

## Definições
Algumas nomenclaturas como programa de computador, software, sistemas de informação são utilizadas no dia a dia. Com isso, é importante termos em mente se estamos utilizados esses termos corretamente.

**Programa**

- Conjuto de instruções que serão executas sequêncialmente por um computador
- Programa é o código a ser executado

**Software**

- Conjunto de instruções (programa) que, quando executados produzem função e o desempenho desejados;
- Estruturas de dados que permitem a manipulação das informações
- Documentos que descrevam a operação e o uso dos programas
- Produto que os engenheiros de software projetam e constroem
- Parte lógicas de um sistemas cuja a função é comandar o hardware

**Sistema**

- Conjunto de elementos interdependentes de modo a formar um todo organizado (Programa, software, hardware, pessoas etc)

## Ciclo de desenvolvimento de software

Processo de desenvolvimento de software é conjunto estruturado de atividades necessárias para desenvolver um sistemas de software.

- As atividades
- Duração
- ordem

**Descrição de processos**

- Atividade: Indicam o que precisa ser feito e indicando também uma prática ou técnicas que deve ser usada.
- Produtos ou artefatos: São resultados de uma ativade do processo
- Insumos: São artefatos que servem de entrada para a execução de uma atividade
- Papéis: Refletem as reponsabilidades das pessoas envolvidas no processo;
- Pré e pós condições: São declarações que são verdadeiras antes e depois de uma ativdade do processo ser executada, ou um produto produzido

**Modelos de ciclos de vida**

- Modelo sequencial linear
- Modelo em casczta (watarFall)
- Modelo Incremental
- Modelo Incremental evolutivo
- Modelo Espiral
- Modelo iterativo (permitir repetir atividades/passos)
- Modelo V (Combinar testes com o desenvolvimento)

* Leitura aditional
https://www.devmedia.com.br/ciclos-de-vida-do-software/21099

## Tema 2: Processos de Software

## Processos Ágeis

Nesta seção teremos um primeiro contato com SCRUM que é um processo ágeis bastente utilizado em todo mundo. Com base no SCRUM, veremos caracteristicas dos processos ágeis e o manifesto ágil.

Uma das crises do software foi resolvido temporáriamente com a criação da ideia da Engenharia de software. Entretanto, uma segunda leva da crise do software surgiu com os desenvolvedores tendo dificuldades em entregar projetos dentro custo previsto ou mesmo evitar grande gama de projetos cancelados.

Aliança ágel (agile aliance em 2001) 17 metodologistas

Além disso, muitos dos desenvolvedores não se sentiam parte ou com voz ativa, com possibilidades de tomar de decisões em muitos dos projetos. Com esse sentimento e insastifação, os desenvolvedores se organizaram e surgiu o manifesto ágil.

*Processos ágeis seguem o modelo incremental e interativos com pequenas e contantes entregas (entre duas ou três semanas)*

Manifesto ágil surgiu em 2001 junto com a crianção da aliança ágil (agille alliance) com grupo de 17 desenvolvedores ou pessoas que fazem prática da engenharia de software.

**Valores para o desenvolvimento de software**
- Individuos e interações têm mais valor que processos e ferramentas
- Software operacional tem mais valor que uma documentação abrangemte
- Colaboração com o cliente tem mais valor que negociação contratual
- Repostas a mudanças têm mais valor que aderência a um plano

**Os 12 princípios Ágeis**

1. **valor**: A maior prioridade está em satisfazer o cliente por meio da entrega adiantada e contínua de software de valor.
2. **Flexibilidade**: Processos ágeis se adequam a mudanças, para que o cliente poosa tirar vantgens competitivas, aceitando alterações de requisitos mesmo no fim do desenvolvimento.
3. **Frequência**: Entrega o software em funcionamento com frequência, seja na escala de semanas ou meses, dando preferência a períodos mais curtos.
4. **União**: Tanto pessoaos relacionadas a negócios como desenvolvedores devem trabalhar em conjunto diariamente, durante todo o curso do projeto.
5. **Motivação**: Para construir projetos ao redor de indivíduos motivados, é preciso dar a eles o ambiente e o suporte necessários confiando que farão seu trabalho.
6. **Comunicação**: O método mais eficiente de transmitir informações tanto externas como internas um time de desenvolvimento é por meio de uma conversa cara a cara.
7. **Funcionalidade**: Um software funcional é a medida primária do profresso.
8. **Sustentabilidade**: Processos ágeis promovem um ambiente sustentável como patrocionadores, desenvolvedores e usuários sendo capazes de manter passos contantes.
9. **Revisão**: A contínua atenção à excelência técnica e ao bom design aumenta a agilidade.
10. **Simplicidade**: Simplicidade é a arte de maximizar a quantidade de trabalho que não precisou ser feito.
11. **Organização**: As melhores arquiteturas, os requísitos e os designs emergem de times auto organizáveis.
12. **Autoavaliação**: Em intervalos regulares, o time reflete em como ficar efetivo, então, se ajustam e otimizam o seu comportamento de acordo.

Exemplos de processos ágeis

- eXteme Programming(XP)
- SCRUM
- Dyamic System Development Method (DSDM)
- Crystel Families

**Introdução ao SCRUM**

SCRUM tem como abordagem entender que inicialmente o problema não está compreendido em sua totalidade inicialmente. Aceitam que requisitos mudarão com o passar do tempo, dessa forma aceitando mudanças no projeto.
                                              
Plenajamento geral e arquiterura --> Avaliar --> Selecionar --> Desenvolver --> Revisar --> Encerramento do projeto

O ciclo do SCRUM pode ser repetido N vezes antes do seu encerramento

Características

- Equipes pequenas e multidisciplinares
- Versões incrementais com iterações curtas
- Equipes auto-organizadas com liderança diluída
- Facilitador: Scrum Master
- Trabalho organizado a partir da lista de backlog de tarafes do produto (priorizada)
- Comunicação e cooperação entre as equipes se intensificam para produzir resultados

Os três papéis

*Productor Owner*
+ Responsável pelo valor de negócio do produto
+ Representante do cliente junto da equipe
+ Controla, gerencia e prioriza o backlog do produto

*Scrum Master*
+ Toma iniciativas para melhora o trabalho, resolve os impedimentos
+ Não se envolve com o trabalho técnico

*Desenvolvedores*
+ Auto-organizada
+ Responsável por entregar valor por meio de software com qualidade

**Cerimônias e artefatos do SCRUM**

_Artefatos_

- backlog do produto
  - Lista de requisitos de tudo que precisa ser feito no produto
  - Contêm história de usuário. Informa quem é o usuário, o que ele precisa do software e a justificativa
  - Quem? (Exemplo: Stakeholders como Clientes, Atendente e **gestor**) O quê?, Por quê?
  - O quê? ( Exemplo: Descrever a necissidade; Gestor "Eu quero consultar informações sobre histórico de clientes")
  - Por quê? (Exemplo: Para prover promoções e transformá-lo em VIP)

- Incremento do produto (nova parte ser produzida do produto)
    - Sublista do backlog do produto que serão movidos para backlog da sprint

- Backlog da sprint
  - Items do backlog que serão trabalhos durante a spring
 
_As quatro cerimônias_

- Reunião de planejamento da Sprint (definir backlog)
- Reunião diária (Daily 15 min)
- Revisão da sprint
- Retrospectiva da Sprint

https://scrumreferencecard.com/ScrumReferenceCard.pdf
https://artia.com/blog/scrum/

## Processos prescitivos

Os processos prescitivos, todas as tarefas são definidas inicialmente

**RUP - Rational Unified Process** 

Pricípios
- Atacar os riscos principais de forma rápida e contínua
- Garantir que se está provendo algo de valor ao cliente
- Concentrar se em produzir software executável
- Acomodar mudanças no projeto
- Definir a arquitetura o mais cedo possível
- Construir o sistema com componentes
- Trabalhar em equipe
- Fazer da qualidade uma forma de vida

Problematicas com processos prescritivos

- É baseado no paradigma comando e controle
- São mais atrativos para gerentes que para a maioria dos desenvolvimentos
- Segmenta o desenvolvimento de software em espacialidades que não possuem visão do todo
- Muitas vezes são abandonadas em situações críticas

https://www.ibm.com/developerworks/rational/library/content/03July/1000/1251/1251_bestpractices_TP026B.pdf
https://www.tutorialspoint.com/uml/uml_overview.htm

## Tema 3: Características do software

## Requisitos funcionais
Os requisitos funcionais descreve funcionalidades, comportamentos, interações etc do sistema. Dependendo do processo de software utilizado, terá diferentes formas de descrever os requisitos funcionais:

SCRUM - Histórias de usuário no backlog do produto;
RUP - Casos de uso na Especificação de requisitos de software (ERS)

Exemplo de requisistos funcionais

- O sistema deve permitir ao usuário incliur um perfil de cliente;
- O sistema deve emitir um relat;orio de vendas, indicando a data da compra, o que foi comprado, a rentabilidade do cliente para empresa;
- O sistema deve permitir a consulta de saldo ou estoque para as impressoras 3D

https://www.inf.ufsc.br/~jean.hauck/guias/29110/Norma%20ISO%2029110%20Perfil%20de%20Entrada%20Básico/guidances/examples/documento_especificao_de_requisitos_2CFB343D.html

## Requisitos não funcionais
Esse tipo de requisito não descreve uma funcionalidade mas as características de qualidade que o sistema todo ou uma funcionalidade devem ter. Como segurança, usabilidade, padrões se serem seguidos, confiabilidade, disponibilidade etc.

- O Sistema deve funcionar 24hrs por dia, todos os dias da semana;
- Os sistema deve funcionar perfeitamente com 100.00 usuários
- O sistema deve ser suportado em todos os sistemas operacionais mobile
- O software deve apresentar as opções de restautes próximos em no máximo 2 segundos
- 

https://www.ateomomento.com.br/o-que-e-um-requisito-nao-funcional/
https://leonardo-matsumota.com/2019/03/18/definicao-de-pronto-dod-definition-of-done/

# UNIDADE 2: ATIVIDADES e ARTEFATOS DA ENGENHARIA DE SOFTWARE

## Tema 1: Atividades de engranharia de software

**ATIVIDADES TÉCNICAS**

Todas engenharias incluem atividades atividades técnicas e gerencias.

- Técnicas

  
  Engenharia de requisitos, Projeto de Software, implementação, testes, manutenção e evolução, medição.

- Gerenciais


  Aceite pelo cliente, garência de configuração, gerência de requisitos, gerência de projetos, gerência da qualidade, gestão do processo, estimativas

- Apoio
  
  Comunição, gestão de pessoas, gestão de equipes


Dando mais pronfundidades nas atividades técnicas relacionadas descrição e levantamento de requisitos, abaixo estarão mais detalhes de cada atividade:

- Levantamento de requisitos (Elicitação)
  
  Aqui se encontra os levantamento de requisitos funcionais e não funcionais para descobrir os problemas, e as necessidades do clientes. Entevista, questinários, leitura de docs, observações, pesquisas de levantamento de dados, prototipação etc.

- Análise dos requisitos
  
  Estudo detalhado do requisitos para que sejam encontradas lacunas, inconsistência, e conflitos. Nesse estágio, é comum a utilização de **modelagem**.

- Especifição dos requisitos (descrição)

  Descrever em detalhes os requisitos de maneira clara, precisa e sem ambuiguidades.

- Validação dos requisitos

  
  Revisão os items que foram descritos para validar se os requisitos estão corretos. Pode ser utilizado: Protótipos e notação
  
Temos também atividades técnicas relacionadas no desenvolvimento da solução:

- Projeto (design) de software

Neste estágio, serão estudados diversas alternativas de solução e ponderação entre elas, e por fim a escolha da solução que será adotada no projeto. 
  - Arquitetura do software de forma abstração representando onde estarão os componentes e suas comuniçãos
  - Projeto detalhas com cada parte ou elementos com riqueza de detalhes como: Funções, responsabilidades, algoritmos, estruturas de dados etc.

- Implementação ou condificação
  
  Transforma modelos de projeto em código escrito em uma linguagem de programação

- Testes de software

Verificação se o software funciona devidamente como esperado satisfazendo os requisitos do cliente. Testes podem ser realizadas de forma manuais ou automatizados podem se concentrar no código, usuário ou na especificação dos requisitos.

- Aceitação

Cliente verifica, teste se o software estar de acordo com as espectativas.

- Manutenção de software (Evolução)
  - Correções
  - Melhorias
  - Novos requisitos
  - Novas necessidades
  - Mudanças de tecnologias

- Medição do software

  Incluem tarefas como metas, definição de prioridades.

**ATIVIDADES GERENCIAIS DE ENGENHARIA DE SOFTWARE**
 Atividades gerencias como o nome diz, refere-se as atividades de gestão como controle de processos, qualidade dos produtos, as estimativas acertadas, satisfação do cliente e cuidar da complexidade do produto.

 - Gestão de configuração (versionamento) e controle de mudanças
 - Gerência de Projetos (prazo, custo, recursos, ferramentas etc)
 - Gerência de requisitos
    - Priorização dos requisitos
    - Aprovações de mudanças
    - Controle de escopo
    - Rastrabilidade
- Gestão de processsos
 - Estimativas de software (tempo, time da equipe, esforço, custo, tamanho do software)

**TESTES DE SOFTWARE**

O objetivo dos teste é revelar possíveis defeito porém é possível que após diversos teste o software contenha defeitos (bugs). Em geral testes são dividos em **testes funcionais** e **testes estruturais**.

 - Teste Funcional: Busca testar o código na pespectiva do usuário do software.
 - Teste estrutura: Busca testar o software na pespectiva do desenvolvedor, olhando para a estrutura do código.

Um conjunto de teste é chamado de plano de testes. Plano de testes contêm a documentação de casos de teste e objetivos de cada conjunto de testes como: Teste de desempenho, testes funcionais da história de usuário x, testes de responsividade, teste de campos de formulários, testes de navegabilidade ou links e testes ponta a ponta.

- **Testes para aplicações Front End**

    - Testes navegabilidade (HyperLink e abas funcionan?)
    - Testes de responsividade (Págiba WEB funciona em dispositivos móveis)
    - testes de compos e páginas (Validar campos Ex.: Campo "Nome"apenas letras, campo "CPF" apenas números inteiros)
    - Testes ponta a ponta 

Exemplo de tabela específica para determina aplicação

|ID hist. de usuário | Funcionalidade | Campos    | Obrigatório? | Tipo       |  Tamanho   | Editável   | Permite Caract. especiáis? |
| -------------------|----------------|-----------|--------------|------------|------------|------------|--------------------------- |
|#1234               |   Login        | Usuário   |      Sim     | Alfa Num.  |    14      |     Sim    |           Não              |
|                    |                | Senha     |      Sim     | Alfa. Num. |    10      |    Sim     |           Sim              |
|                    |                | Enviar    |      Sim     | N/A        |    N/A     |    N/A     |           N/A              |
|                    |                | Cancelar  |      Não     | N/A        |    N/A     |    N/A     |           N/A              |




