# Aja com Prudência

> *"Seja qual for seu empreendimento, aja com prudência e considere as consequências" Anon*

Não importa o quanto um prazo pareça confortável no início de uma iteração, você não conseguirá evitar ficar sob pressão em algum momento. Se você precisar escolher entre "fazer a coisa certa" e "fazer a coisa rápido" é frequentemente tentador "fazer a coisa rápido" esperando poder voltar e consertá-la mais tarde. Quando você faz essa promessa a você mesmo, a seu time e s seu cliente, você estabelece um compromisso. Mas quase sempre a próxima iteração traz novos problemas e você foca neles. Esse tipo de trabalho adiado é conhecido como débito técnico e ele não é seu amigo. Especificamente, Martin Fowler chama isso de débito técnico deliberado no artigo [taxonomima do débito técnico](http://martinfowler.com/bliki/TechnicalDebtQuadrant.html), que não pode ser confundido com o débito técnico inadvertido.

Débito técnico é como uma conta: Você se beneficia no curto prazo, mas precisa dar atenção a ela até que esteja totalmente paga. Atalhos no código deixam mais difícil adicionar funcionalidades ou refatorá-lo. Eles são terrenos férteis para defeitos ou casos de teste confusos. Quanto mais você os largar, pior eles ficam. Quando você voltar para realizar o conserto original poderá existir um monte de escolhas de projeto não-tão-certas empilhadas sobre o problema original tornando o código muito mais difícil de refatorar e corrigir. De fato, muitas vezes só quando as coisas ficam muito ruins é que você volta para consertá-las. E nesse momento tudo fica tão difícil que você não pode assumir o tempo nem o risco.

Há casos que você precisa incorrer em débito técnico para cumprir um prazo ou implementar uma parte pequena de uma funcionalidade. Tente não ficar nessa posição, mas se a situação realmente exigir, vá em frente. Mas (e esse é um enorme MAS) você deve rastrear o débito técnico e pagá-lo o quanto antes ou as coisas vão piorar rapidamente. Assim que você fizer essa decisão de endividar-se, escreva uma tarefa ou anote no seu sistema de *bug tracking* para assegurar-se que ela não foi esquecida.

Se você agendar o pagamento do débito na próxima iteração, o custo será mínimo. Deixando o débito em aberto serão acrescidos juros e esses juros devem ser monitorados para deixar o custo visível. Isso irá enfatizar o efeito no valor de negócio do débito técnico do projeto e permitir a priorização apropriada do pagamento. A escolha de como calcular e rastrear os juros vai depender de cada projeto, mas monitorá-lo é uma necessidade.

Pague o débito técnico o quanto antes. Seria imprudente agir de maneira diferente.

Por [Seb Rose](http://programmer.97things.oreilly.com/wiki/index.php/Seb_Rose)
