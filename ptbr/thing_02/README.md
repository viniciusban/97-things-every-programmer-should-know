# Aplique Princípios de Programação Funcional

A programação funcional tem experimentado recentemente um interesse renovado vindo das principais comunidades de programadores. Parte disso é porque as *propriedades emergentes* do paradigma funcional estão bem posicionadas para enfrentar os desafios lançados pela mudança de nossa indústria em direção a tecnologias multi-core. Entretanto, mesmo sendo essa uma aplicação importante, essa não é a razão desse texto dizer-lhe *aprenda programação funcional*

O domínio do paradigma de programação funcional pode melhorar enormemente a qualidade do código que você escreve em outros contextos. Se você entender profundamente e aplicar o paradigma funcional, seus designs exibirão um grau muito maior de *transparência referencial*.

A transparência referencial é uma característica muito desejável: Ela estabelece que as funções retornam consistentemente os mesmos resultados, dadas as mesmas entradas, independente de quando ou onde elas são invocadas. Isto é, a execução de uma função depende menos — idealmente, nada — dos efeitos colaterais do estado mutável.

Uma das principais causas de defeitos no código imperativo é atribuída a variáveis mutáveis. Todos que lerem esse texto já tiveram que investigar por que algum valor estava diferente do esperado em alguma situação particular. A semântica de visibilidade pode ajudar a diminuir esse problema, ou, pelo menos restringir sua localização, mas o real culpado pode, de fato, ser a condescendência de designs que usam mutabilidade indiscriminada.

E certamente nós não encontramos muita ajuda da nossa área nesse sentido. As introduções a orientação a objetos tacitamente promovem esse design, porque elas mostram exemplos compostos de grafos e objetos com vida longa e que alegremente chamam métodos que mudam estados uns dos outros, o que pode ser perigoso. Entretanto, com um design astuto guiado por testes, particularmente tendo certeza de ["Mockar Papéis, ao invés de Objetos"](http://www.jmock.org/oopsla2004.pdf), a mutabilidade desnecessária pode ser afastada do seu design.

O resultado é um design que tipicamente tem uma melhor alocação de responsabilidade com funções mais numerosas e menores, que agem sobre argumentos passados a elas, ao invés de referenciarem variáveis-membro mutáveis. Haverá menos defeitos e, quando aparecerem, serão mais fáceis de depurar, porque é mais fácil localizar onde um valor maroto é introduzido nesses designs do que deduzir um contexto particular que resulta em uma atribuição equivocada. Além disso, eleva a um nível muito mais alto de transparência referencial e certamente nada inculcará em você essas ideias tão profundamente como aprender uma linguagem de programação funcional, onde esse modelo de computação é a norma.

É claro que essa abordagem não é a melhor em todas as situações. Por exemplo, em sistemas orientados a objetos esse estilo frequentemente traz melhores resultados com o desenvolvimento do modelo de domínio (p.ex., onde colaborações servem para dividir a complexidade de regras de negócio) do que no desenvolvimento da interface com o usuário.

Domine o paradigma de programação funcional para você poder aplicar as lições aprendidas a outros domínios. Seus sistemas orientados a objetos irão destacar-se com a benevolência da transparência referencial e estarão muito mais perto de seus companheiros funcionais do que você imaginaria. De fato, alguns até defenderiam que o ápice da programação funcional e da orientação a objetos é *meramente o reflexo um do outro*, uma forma de ying e yang computacional.

Por [Edward Garson](http://programmer.97things.oreilly.com/wiki/index.php/Edward_Garson)
