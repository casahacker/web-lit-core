---
layout: page
title: "Marcação Básica"
following: _articles/construindo-paginas-basicas.md
toc:
- "Introdução"
- "Conteúdo e Tags"
- "Off-line: Marque o Mundo"
- "Off-line: Revolução das Marcações"
- "Marcação em Ação"
- "Reflexão da Experiência de Aprendizagem"

---
![tagging](../images/code-2434271_640.jpg)

#### Descrição
Nesta atividade, os alunos exploram como as informações, como texto e imagens, podem ser apresentadas para serem facilmente legíveis/compreensíveis, e como isso funciona na web usando _tags_ HTML. Essa atividade explora como os navegadores funcionam, como as páginas web são estruturadas, a relação entre as _tags_ HTML e o conteúdo.

#### Objetivos da Aprendizagem
* Descrever como o código HTML é usado para criar páginas web.
* Identificar _tags_ HTML comuns.
* Criar um arquivo de texto que possa ser exibido como uma página web usando _tags_ HTML

#### Tempo Necessário
45 minutos a 1 hora, dependendo do tamanho do grupo

#### Público-alvo
Pode ser adaptado para públicos de 13 anos ou mais; com níveis variados de experiência com a web.

#### Materiais
* Notas autoadesivas
* Lápis, marcadores
* Notebook com conexão à Internet
* Imprima cartões com _tags_ para _TagTag Revolution_ ou faça o seu próprio em pedaços separados de papel, escreva as seguintes _“tags”_ (não se esqueça de incluir a seta!):
    * Abra as _tags_: "\<aplaudir> →" (também cantar, pisar, girar, agitar).
    * Feche as _tags_: "</aplaudir> ←" (também cantar, pisar, girar, agitar).

#### Habilidades de Alfabetização Web
* Código
* Design

#### Habilidades do Século XXI
* Comunicação
* Colaboração
* Criatividade

#### Ganhando Emblemas Digitais
Os emblemas digitais capturam a evidência e são a demonstração do conhecimento e da realização. Cada Atividade Principal abrange múltiplas habilidades de alfabetização web. A conclusão de todas as Atividades Principais permitirá que qualquer um ganhe todos os emblemas da alfabetização web e habilidades do século XXI. Assim, encorajamos você a concluir todas as Atividades Principais e ganhar emblemas para capturar o que aprendeu. A Digitalme está oferecendo emblemas de alfabetização web através do [Open Badges Academy](https://www.openbadgeacademy.com/mozilladirectory). 

### Introdução
[3 min]
* Revise os principais conceitos, enquadre e conecte este tópico a uma grande ideia. Explique:
    * A Internet é um sistema de computadores interconectados, e a _world wide web_ é um sistema de páginas interconectadas que vivem na Internet.
    * Sites são espaços para acessar, compartilhar e interagir com conteúdo multimídia.
    * As pessoas que criam a web - desenvolvedores e _designers_ web - usam uma linguagem de codificação de computador chamada _HyperText Markup Language_ ou HTML para criar páginas web.
    * Quando você acessa a web, está usando um _software_ chamado navegador para exibir páginas.

> Dica! Pergunte quem sabe alguns exemplos de navegadores web.

* Vamos explorar hoje o HTML, especificamente como usamos o HTML para tornar nosso conteúdo - texto, imagens, etc. - legível pelos navegadores e fácil para os humanos lerem e entenderem.

### Conteúdo e Tags 
(5-7 mins)
* Para esta atividade, você precisa de dois recursos visuais:
    * 1) a primeira página de um jornal mostrando imagens, títulos, linhas de texto, texto, parágrafos, colunas.
    * 2) o texto e as imagens da primeira página despojados de toda formatação, na mesma fonte de tamanho, sem parágrafos, colunas, etc, impressos em uma única página. Você pode fazer isso acessando uma cópia digital de um jornal da edição impressa, como o [New York Times](http://www.nytimes.com/pages/todayspaper/index.html), selecionando todo o conteúdo e copiando e colando-o em um Editor de Texto e removendo toda a formatação (através do comando “_make plain text_”). Você pode ter que fazer um pouco de edição extra para remover toda a formatação. O objetivo é mostrar aos alunos uma página inicial típica de um artigo, além do conteúdo como um bloco de texto uniforme e contínuo.
* Mostre aos alunos as duas páginas; diga-lhes que o conteúdo é o mesmo em ambas as páginas.
* Discuta juntos - qual é a diferença aqui? O que está faltando? Qual página é mais atraente? Qual página é mais interessante? Qual é mais fácil de ler? Por quê?
* Discuta em conjunto como elementos como títulos, colunas, linhas de texto, tamanhos de fonte diferentes e blocos de texto ajudam a organizar o conteúdo e direcionam nossos olhos para o que é importante na página.

> Dica! Mantenha uma lista dos elementos de design que surgirem na discussão - mapeie-os para as _tags_ HTML mais adiante na lição.

* Conceito-chave! Explique que é assim que os _web designers_ usam o _HyperText Markup Language_ (Linguagem de Marcação Hipertexo): para adicionar formatação ao conteúdo na Web, para que o navegador possa exibi-lo de maneira fácil de ler e interessante.
* Os _web designers_ usam _“tags”_ de HTML para informar ao navegador o que fazer com o conteúdo.
    * Pergunte aos alunos, o que é uma _tag_? Onde você tem _tags_? O que eles fazem?

> Dica! Se os alunos estiverem com dificuldades, explique: você tem marcações em suas roupas ou na sua bagagem, pessoas marcam você nas mídias sociais, você pode marcar uma postagem no blog... Uma _tag_ é um pouco de informação que você anexa a alguma coisa, para identificá-la de alguma forma ou adicionar instruções especiais.

* Explique: Quando os _web designers_ escrevem HTML, eles pegam partes do conteúdo e “marcam-os” com _tags_ para dizer ao navegador como mostrar esse conteúdo. Eles colocam uma _tag_ no início do conteúdo (a _tag_ de abertura) e uma _tag_ no final (a _tag_ de fechamento), para que o navegador saiba quando iniciar e parar.

> Dica! A visualização são realmente úteis aqui - escreva ou projete um exemplo (como abaixo) onde todos possam vê-lo.

* Explique as regras para marcação são:
    * Quando queremos marcar algum conteúdo, nós o cercamos com um par combinado de palavras, cada palavra é cercada por um conjunto de colchetes “< >”.
    * Veja uma _tag_ de exemplo: `<title>` Marque o mundo `</title>`

    > Dica! pergunte aos alunos, neste exemplo, qual é o título?

    * Quando as tags são usadas on-line, os colchetes alertam o software do navegador de que é uma _tag_. A palavra ou caractere dentro de cada colchete informa ao navegador informações importantes sobre o que está dentro dele. <title> é uma _tag_ de abertura - sinalizando que o conteúdo marcado começa aqui.
    * Você pode ver que há algo diferente no segundo conjunto de colchetes: </title> a barra invertida significa que é uma _tag_ de FECHAMENTO - informando ao navegador que a marcação foi concluída.
    * Nós SEMPRE usamos _tags_ de abertura e fechamento para cercar o conteúdo.
* Com pouquíssimas exceções, as _tags_ são SEMPRE compatíveis com o conteúdo, assim como os exemplos de marcação que discutimos.
* Informe aos alunos que agora vamos experimentar o CONCEITO de marcação e marcação em atividades off-line antes de nos aprofundarmos e vermos como elas funcionam on-line.

### Off-line: Marque o Mundo
[10 min]
> Dica! Se os seus alunos parecem confortáveis com o conceito de abertura e fechamento de _tags_ (ou você está pressionado por tempo), você pode pular esta e passar para a próxima seção. Se eles precisarem de mais tempo com esse conceito, faça a atividade Marque o Mundo.

* Introdução: Explique aos participantes que eles experimentarão fazer marcações e atribuir marcações a coisas do mundo real na sala. Distribua folhas de papel, marcadores e fita adesiva. Explique que este é um exercício para mostrar o CONCEITO de marcação e abertura e fechamento de _tags_.
* Aqui no mundo real, você tem total liberdade para criar seus próprios nomes de _tags_. Mais tarde, veremos que no HTML de codificação, usamos um conjunto restrito de nomes de _tags_ com os quais todos concordam. Mas, por enquanto, crie a _tag_ que quiser.

> Dica! Escreva o seguinte exemplo em letras grandes no quadro ou crie um slide para mostrá-lo. Use o tempo que for necessário para este conteúdo e certifique-se de que todos entenderam - é importante!

* Revise as regras de marcação:
* Quando queremos marcar algum conteúdo, nós o cercamos com um par combinado de palavras, cada palavra é cercada por um conjunto de colchetes “< >”. Aqui está uma _tag_ de exemplo:
    * `<title>` Marque o Mundo `</title>`
* Nós SEMPRE usamos _tags_ de abertura e fechamento para cercar o conteúdo.
* Você pode marcar qualquer coisa na sala - faça suas próprias _tags_ e feche-as!

> Dica! Para ajudar os alunos a começarem, crie uma _tag_ de exemplo e coloque-a na sala - `<cadeira>` `</cadeira>`. Incentive as pessoas a se divertirem e serem criativas!

### Off-line: Revolução das Marcações
[10 min]
* Introdução: Explique aos participantes que eles estão prestes a ter uma divertida dança das cadeiras para mostrar como as _tags_ HTML atribuem instruções ao conteúdo.

> Dica! Este jogo é melhor com grupos acima de 10. Se você tem um grupo maior, você pode querer adicionar algumas _tags_ extras. Se você tiver um grupo pequeno, talvez queira usar menos. Sinta-se livre para fazer o seu próprio.

* Passos:
    1. Organize os jogadores em um círculo, certificando-se de que haja espaço suficiente para andar pelo lado de fora do círculo.
    1. Selecione dois jogadores do grupo para serem os “Programadores”. Entregue a um deles a primeira _tag_ aberta e ao outro a _tag_ correspondente fechada. Comece com uma _tag_ fácil como `<palmas>` e `</palmas>`.
    1. Inicie a música e faça com que os dois “Programadores” andem pelo lado de fora do círculo enquanto os outros jogadores ficam parados. Certifique-se de que os “Programadores” mantenham uma pequena distância entre eles. Você poderia fazer com que eles começassem a andar a cinco passos um do outro.
    1. Quando você parar a música, os “Programadores” anexarão as _tags_ aos membros do círculo que estão mais próximos. Lembre-se de que as _tags_ devem envolver o conteúdo.
    1. Todos que estão entre as setas da _tag_ aberta `<palmas>` e da _tag_ fechada `</palmas>, agora terão que começar a bater palmas (as pessoas que usam as _tags_, não precisam). Os jogadores que aplaudem devem continuar a bater palmas pelo resto do jogo.
    1. Agora selecione duas novas _tags_ e entregue-as aos “Programadores” (por exemplo, `<cantar>` e `</cantar>`).
    1. Repita os passos 3 e 4. Desta vez, quando os “Programadores” passarem as _tags_, qualquer um que esteja entre as _tags_ `<cantar>` terá que cantar. Se algum jogador estiver entre as _tags_ `<palmas>` e as _tags_ `<cantar>`, eles terão que bater palmas e cantar.
    1. Continue estas etapas novamente com o resto das _tags_ (e quaisquer outras _tags_ que você deseja adicionar ao jogo) para fazer uma divertida e complicada festa dançante de _tags_! Quando os “Programadores” tiverem com as _tags_ finais, peça-lhes que se juntem ao círculo onde quer que estejam, quando a música parar (em vez de entregar as _tags_ às pessoas no círculo). Todos entre as _tags_ que os “Programadores” estão segurando executam as ações em suas _tags_.
    1. Depois que todas as _tags_ forem usadas, você poderá fazer com que os jogadores com _tags_ movam-se um de cada vez para alterar quem está fazendo o quê. Isso ajudará os alunos a entender como as _tags_ são aplicadas ao conteúdo, como elas são abertas e fechadas no HTML.
* Aqui no mundo real, você tem total liberdade para criar seus próprios nomes de _tags_ - mais tarde veremos que na linguagem de codificação HTML, usamos um conjunto restrito de nomes de _tags_ com os quais todos concordam, que fazem sentido para o conteúdo web. Mas, por enquanto, crie a _tag_ que quiser.

### Marcação em Ação 
[15 min]
* Introdução: explique que vimos como são as _tags_ e como elas funcionam com o conteúdo (o que há dentro das _tags_). Agora, vamos praticar usando algumas _tags_ reais que fazem parte do _HyperText Markup Language_ (HTML).
* Primeiro, vamos verificar um documento HTML simples - adivinhem - a partir de um web designer e desenvolvedor, quando eles estão construindo páginas web, o que eles estão trabalhando é o código HTML em um arquivo de texto simples.

> Dica! Abra um documento HTML simples em um editor de texto - o NotePad para PC ou o TextEdit para Mac, e também mostre-o em um navegador. Aponte as _tags_ no documento e mostre o que elas fazem. _Tags_ básicas sugeridas: h1, h2, h3, p, a, body. Você também pode mostrar um documento mais complexo (use o código-fonte do navegador) para mostrar que todas as páginas web são textos e códigos interpretados pelo computador.

* Essas _tags_ têm significados acordados, de modo que tanto os desenvolvedores web quanto as pessoas que escrevem o software do navegador entendem o que elas significam. A única razão pela qual essas _tags_ funcionam é por causa desses acordos - se você tentar usar algumas de suas _tags_ divertidas do “Marque o Mundo” ou “Revolução das Marcações” em uma página web, você não verá nada, infelizmente.

> Dica! Se os alunos estiverem confusos sobre quais tipos de _tags_ seriam relevantes em HTML, lembre-os de que HTML significa "_HyperText Markup Language_ (Linguagem de Marcação Hipertexto)" e que atribuímos _tags_ ao conteúdo de texto. Pergunte: por que “parágrafo” seria uma _tag_ HTML e não “palmas” ou “cantar”?

* Quando você usa essas _tags_, você está escrevendo HTML! E quando o navegador as vê, ele transformará sua página web de um chato bloco de texto para algo interessante e fácil de ler.
* Vamos marcar! Faça com que os alunos adicionem _tags_ a algum conteúdo existente.
* OFF-LINE, para esta parte, você vai precisar de algum conteúdo - talvez uma notícia divertida ou uma biografia de alguém, ou algum outro conteúdo interessante, impresso em folhas 11x7 e cortadas em pedaços - parágrafos, títulos, links, etc. Você também precisará de alguma nota autoadesiva ou papel para _tags_. Escreva as _tags_ ou deixe os alunos criá-las (somente da lista). Divida os usuários em pequenos grupos e dê a cada grupo uma coleção de texto e _tags_.
* ON-LINE, Para esta parte, você precisará de um arquivo de texto com algum conteúdo básico não formatado, mesmo tipo acima. Primeiro, peça aos usuários para salvar o arquivo como .html. Explique o objetivo das _tags_ `<head>` e `<title>`. Em seguida, deixe-os digitar as suas _tags_!

> Dica! Para o ON-LINE, crie um arquivo de texto com o conteúdo e peça aos usuários que o editem com o editor de texto MAIS BÁSICO - Bloco de notas em um PC ou TextEdit em um Mac - no modo de texto simples. O(A) facilitador(a) pode precisar explicar o cabeçalho e as _tags_ do título.

* Explique aos alunos que eles precisam primeiro cercar todo o conteúdo com as _tags_ body - para informar ao navegador que todo o conteúdo aqui é para exibição na web!
* Peça aos alunos para organizar o conteúdo usando as _tags_. Encontre os cabeçalhos mais importantes, divida os parágrafos, adicione pequenos títulos e procure por itens que possam ser _hiperlinks_. Ande pela sala e ajude aqui e ali.
* No final do exercício, se possível, os alunos on-line e off-line deverão ver a página carregada em um navegador. Os alunos on-line podem salvar e abrir o arquivo .html em um navegador. Para alunos off-line, o(a) facilitador(a) deve, se possível, mostrar a página finalizada em um computador e monitor.
* Explique aos usuários que esses arquivos ainda estão em seus computadores locais e só podem ser visualizados lá. Você ainda não os colocou "on-line" em um servidor, onde outras pessoas podem encontrá-los, portanto, elas não estão na web.

> Dica! Lembre aos usuários da atividade Mapear a Web para ajudá-los a visualizar como o computador cliente está conectado. Eles podem acessar o conteúdo em servidores web, mas outros computadores na Web não podem acessar os arquivos dos clientes.

### Reflexão da Experiência de Aprendizagem 
[5 min]
* O que você gostou sobre esta atividade?
* Se você puder ensinar essa atividade a um público específico, o que você mudaria no processo, estrutura ou conteúdo para melhor atender às necessidades desse público? 

### Deixe a sua opinião sobre o Currículo Principal
* Conte-nos [como e onde você está usando o currículo](https://github.com/mozilla/web-lit-core/issues/8) e [o que você aprendeu e o que você gostaria de mudar](https://github.com/mozilla/web-lit-core/issues/9).