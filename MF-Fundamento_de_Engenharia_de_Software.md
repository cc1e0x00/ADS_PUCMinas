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
