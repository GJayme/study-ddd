# Domain Driven Design - DDD

## Introdução
- DDD é fundamentalmente utilizado em projetos grandes, no qual não temos clareza de tudo que esta acontecendo no projeto todo.
- DDD fornece clareza

### Ponto de partida do DDD
Normalmente quando estamos falando de DDD, nós não estamos falando de código, nós estamos falando de princípios e entender como a gente consegue modelar um software.

Quando estamos falando de DDD não estamos falando apenas de patterns apenas, estamos indo muito mais além para saber como modelar um software.

#### O que é DDD?
É uma forma de desenvolver softwware com o foco no coração da aplicação - o que chamamos de domínio - tendo o objetivo de entender suas regras, processos e complexidades, separando-as assim de outros pontos complexos que normalmente são adicionados durante o processo de desenvolvimento.

#### Origem do DDD
- Eric Evans
- Livro lançado em 2003
    - Filosofia -> é o ponto principal da ideia do DDD
    - Exemplos gerais
    - Patterns
- Comunidade de entusiastas seguindo essa prática
- Lançamento de outros livros
    - Implementing Domain Driven Design - Vaughn Vernon
    - Domain Driven Design Distilled - Vaughn Vernon -> bacana de se ler, mas deixa alguns pontos importantes para trás.

### Complexidades de um software
- DDD é/ou deve ser aplicado para casos de projetos de softwares complexos;
- Grandes projetos possuem muitas áreas, muitas regras de negócio, muitas pessoas com diferentes visões em diferentes contextos;
- Não há como não utilizar técnicas avaçadas em projetos de alta complexidade;
- Grande parte da complexidade desse tipo de software não vem da tecnologia, mas sim da comunicação, separação de contextos, entendimento do negócio por diversos ângulos;
- Pessoas, complexidade de software involve pessoas.

### Como DDD pode ajudar?
- Entender com profundidade o domínio e subdomínios da aplicação
    - Domínio: é o coração do software, ou seja, é algo que esta inteiramente ligado a função princípal da aplicação que estamos desenvolvendo. É uma visão geral.
    - Subdomínio: são partes do nosso sistema, que em conjunto consegue gerar e entregar valor para a empresa.
- Ter uma linguagem universal (linguagem ubíqua) entre todos os envolvidos.
    - A falta de uma linguagem universal gera problemas na hora de desenvolver o software.
    - A linguagem universal do projeto tem que estar organizado e documentado.
- Criar o design estratégico utilizando **Bounded Contexts**
- Criar o design tático para conseguir mapear e agregar as entidades e objetos de valor da aplicação, bem como os eventos de domínio.
- Clareza do que é complexidade de negócio e complexidade técnica.

### Resumindo
"In short, DDD is primarily about modeling a Ubiquitous Language in an explicitly Bounded Context." - Vernon, Vaughn. Domain-Driven Design Distilled (p.11). Pearson Education. Kindle Edition.
