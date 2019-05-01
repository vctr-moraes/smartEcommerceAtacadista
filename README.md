# Smart E-commerce Atacadista

O Smart E-commerce Atacadista é um projeto de marketplace para automação comercial de vendas por atacado B2B desenvolvido dentro do Programa Institucional de Voluntariado de Iniciação em Desenvolvimento Tecnológico e Inovação no Instituto Federal do Espírito Santo.

A proposta primordial do projeto é conceber um meio informatizado para que empresas do comércio varejista possa comprar mercadorias para a loja de forma autônoma e independente do atendimento de vendedores e representantes comerciais.

É proposta uma solução além do convencional, algo que agregue valor aos principais envolvidos nos processos comerciais, um sistema programado que ofereça ferramentas e funcionalidades diferenciadas à rotina de compras. Essas funcionalidades do sistema permitirão decisões estratégicas de alto nível, impossíveis ou inviáveis de serem realizadas manualmente.

<h2>Metodologia de Desenvolvimento Utilizada</h2>

Existem diversas metodologias e cada uma agrega uma série de vantagens e desvantagens em relação ao tipo de software e tipo de contexto em que se esteja desenvolvendo. Para determinados tipos de softwares uma metodologia se mostrará mais adequada ao desenvolvimento, ao passo em que poderá ser totalmente inapropriada ao desenvolvimento de outros tipos.

Todo processo de desenvolvimento de software é dividido em etapas. Cada uma delas contém uma série de atividades e procedimentos que contribuem para a construção. Dentre as várias atividades inerentes a cada fase, algumas poderão ser adotadas de acordo com necessidades particulares do um projeto em questão.

As fases do ciclo de vida de desenvolvimento de sistemas seguem uma linearidade, e cada autor propõe uma série de etapas sequenciais que se distinguem de outras propostas. No projeto Smart E-commerce Atacadista foi utilizada a metodologia de desenvolvimento Iterativo e incremental e estabeleceu-se as fases Planejamento, Análise, Projeto e Implementação.

<p align="center">
  <img  src="https://victoranalyst.files.wordpress.com/2018/12/modelo-iterativo-e-incremental.png" style="max-width:100%;"> 
</p>

<h2>Engenharia de Requisitos</h2>

A engenharia de requisitos iniciou-se pelas primeiras declarações de alto nível sobre o futuro sistema. Esta etapa é muito importante, pois é o momento em que o software começa a tomar forma sob a utilização de modelos de análise.

Durante a elicitação de requisitos foi possível esboçar o primeiro modelo, o Modelo de Domínio, necessário à representação dos objetos do mundo real, pertencentes ao domínio do problema em estudo. Posteriormente, uma série de novos modelos foram utilizados para retratar a realidade do futuro sistema sob diferentes perspectivas. O modelo de domínio é apresentado a seguir e compõe os principais objetos que participam do negócio.

<p align="center">
  <img  src="https://victoranalyst.files.wordpress.com/2018/05/modelo-de-dominio.jpg" style="max-width:100%;"> 
</p>

<h2>Documentação das regras de negócio</h2>

As regras de negócio capturadas possibilitaram realizar um projeto que atendesse a maioria das necessidades de digitalização dos processos de trabalho de distribuidoras e varejistas, considerando seu propósito acadêmico.

Para organizar as informações utilizou-se um template que permitiu estruturar devidamente cada regra de negócio. Com o modelo adotado foi possível gerenciar cada regra de negócio ao longo de todo o ciclo de vida de desenvolvimento do sistema.

<p align="center">
  <img  src="https://victoranalyst.files.wordpress.com/2018/12/template-para-regras-de-negc3b3cio.png" style="max-width:100%;"> 
</p>

<h2>Documentação de requisitos utilizando linguagem natural</h2>

Uma vez elaborado o diagrama de casos de uso foi possível decompor os cenários de uso e identificar diversas funcionalidades do sistema, as quais integram uma série de requisitos funcionais. Os requisitos funcionais originaram-se a partir das regras de negócio e foram declarados sob linguagem natural, estando estes, atrelados aos casos de uso no diagrama.

A documentação dos requisitos funcionais segue um template de atributos tido como ideal para sua descrição. Este compõe informações entendidas como relevantes e adequadas à descrição dos requisitos do sistema. A seguir é apresentado o template utilizado na documentação dos requisitos funcionais.

<p align="center">
  <img  src="https://victoranalyst.files.wordpress.com/2018/12/template-para-requisitos-funcionais.png" style="max-width:100%;">
</p>

<h2>Criação dos Cenários de Uso</h2>

O diagrama de casos de uso foi construído integrando todos os cenários de uso, os quais compõem o software proposto, os atores com os quais interage, bem como os relacionamentos entre estes. Este conjunto de elementos da modelagem do diagrama de casos de uso possibilita conhecer o contexto do sistema.

<p align="center">
  <img  src="https://victoranalyst.files.wordpress.com/2018/05/usecase-diagram0.jpg?w=984" style="max-width:100%;">
</p>

O ator Distribuidora interage com cenários de uso referentes ao gerenciamento de produtos. Há um ‘CRUD’ para que ele possa manter seus produtos. Apenas há uma exceção para a operação de deleção – para que seja mantida a integridade dos dados, bem como, a necessidade de realização de consultas de históricos de vendas, os produtos não podem ser deletados. A solução adotada para um produto que não esteja mais disponível é mudar o seu status, assumindo o estado de inativo. A Distribuidora também gerencia o relacionamento que mantém com seus clientes, com os quais possui um vínculo a nível de sistema para que as transações comerciais possam acontecer. Ainda, ele pode gerenciar suas vendas, as quais podem assumir 3 diferentes estados: aguardando, cancelada ou atendida.

O ator Varejista interage com cenários de uso, tais como, pesquisar produto. Para esta ação, é necessário que um varejista já possua um vínculo a nível de sistema com a Distribuidora. Isto é necessário para que o Varejista possa ter acesso ao catálogo de produtos da Distribuidora em questão, de modo a refletir o que se dá, de fato, na realidade. Este vínculo entre Varejista e Distribuidora se dá por meio do mecanismo de envio de solicitação comercial. Um Varejista faz a solicitação e esta aguarda pela resposta da Distribuidora, podendo assumir 3 estados distintos: aguardando, recusada ou aceita.

A modelagem do sistema por meio da utilização de casos de uso utiliza duas técnicas para sua documentação. Inicialmente foi construído o diagrama. Este, documenta as funcionalidades do sistema sob o ponto de vista de sua utilização. No entanto, apenas o diagrama é insuficiente para o pleno conhecimento e entendimento dos cenários de uso do software, sendo necessária uma documentação complementar ao diagrama. Esta documentação é denominada especificação de casos de uso e leva em consideração propriedades essenciais, inerentes a cada caso de uso.

Para a organização destas informações foi utilizado um template que compõe os detalhes dos casos de uso. Cada informação composta foi entendida como relevante e necessária ao bom detalhamento dos cenários. A seguir é apresentado o template utilizado para o preenchimento das informações.

<p align="center">
  <img  src="https://victoranalyst.files.wordpress.com/2018/12/especificac3a7c3a3o-de-caso-de-uso.png" style="max-width:100%;">
</p>

<h2>Modelagem Comportamental – diagrama de estados</h2>

Em uma atividade de modelagem bem elaborada e que envolva a utilização de certos diagramas da UML é possível conhecer as diversas perspectivas de um sistema em desenvolvimento. Isto porque os modelos possibilitam demonstrar graficamente, sob vários aspectos, aquilo que se pretende construir com linguagem de programação.

O modelo é adotado em um projeto quando se faz necessário entender melhor como ocorrem os fluxos de controle entre estados assumidos por um objeto. O diagrama de estados pode basear-se em um caso de uso, mas também pode ser utilizado para acompanhar os estados de outros elementos, como, por exemplo, uma instância de uma classe.

Este projeto adotou a utilização do diagrama de estados para obter um melhor entendimento do comportamento das instâncias da entidade Venda no que diz respeito aos estados que estas podem assumir. O diagrama integra o objeto participante da interação, bem como os demais elementos gráficos que compõem o modelo como pode ser observado a seguir.

<p align="center">
  <img  src="https://victoranalyst.files.wordpress.com/2018/12/diagrama-de-estados2.png" style="max-width:100%;">
</p>

<h2>Construção do Diagrama de Classes</h2>

A elaboração do diagrama de classes teve como base o modelo de domínio anteriormente criado. Inicialmente foram modeladas as principais entidades constantes no domínio do problema; agora, são identificadas novas classes que fazem parte do diagrama completo que atenderá uma especificação mais detalhada na perspectiva estrutural. As novas classes inseridas ao diagrama são necessárias a representação dos objetos que farão parte do sistema de software.

<p align="center">
  <img src="https://victoranalyst.files.wordpress.com/2018/12/diagramadeclasses.jpg?w=984" style="max-width:100%;">
</p>

<h2>Modelagem de Dados</h2>

A modelagem de dados evolui paralelamente à modelagem dos processos compostos pelo sistema. Ambos partem de modelos mais conceituais até representações mais complexas, necessárias à construção do sistema.

Uma vez tendo evoluído o modelo de domínio para o diagrama de classes da UML, foi possível ter o conhecimento da estrutura do software, a qual, em uma abordagem orientada a objetos, compõe as classes que representam os objetos comuns do mundo real pertencentes ao domínio do problema.

O início das atividades de modelagem se deu por meio do mapeamento objeto-relacional, no qual as classes do sistema representam as tabelas de armazenamento de dados. Não há necessariamente uma transformação direta de classes para tabelas do banco de dados, nem mesmo uma correspondência exata entre ambas; isto apenas ocorrerá para as classes que manipulam dados e serem armazenados pela aplicação. Desta forma, foi elaborado o diagrama entidade-relacionamento que trata-se de uma representação diagramática que ilustra os dados criados, armazenados e utilizados pelo software.

A elaboração do modelo lógico do banco de dados tem sua evolução a partir do modelo conceitual. Nesta etapa o conjunto de entidades anteriormente identificadas ganharam o conceito de tabelas e foram adaptadas para representar a forma na qual os dados estarão armazenados no banco de dados. O diagrama contém tabelas que armazenarão todos os dados relevantes ao domínio do problema e necessários ao funcionamento do software. O modelo lógico do banco de dados é apresentado a seguir.

<p align="center">
  <img src="https://victoranalyst.files.wordpress.com/2018/12/entitydesignerdiagramoficial.png?w=984" style="max-width:100%;">
</p>

<h2>Especificação do Sistema</h2>

O produto da atividade de especificação de sistema é o Documento de Especificação do Sistema. Este artefato compreende as informações técnicas que satisfarão as necessidades do negócio por meio da construção do novo software. Ele contém especificações que foram estabelecidas para que a fase de Implementação proceda conforme o planejado. Este documento pode conter maior ou menor nível de formalidade e detalhamento, a depender da necessidade do projeto em questão ou da forma com a equipe de profissionais trabalha. É comum este tipo de atividade ser ignorada pela equipe, no entanto, é indispensável o mínimo de um conjunto de artefatos de software que viabilizem o início das atividades de programação do sistema, são eles:
<ul>
  <li>Design de arquitetura</li>
  <li>Especificação de hardware e software</li>
  <li>Design de interface</li>
  <li>Design de armazenamento de dados</li>
  <li>Modelo físico de dados</li>
</ul>

Deste modo, a fase de Projeto cumpre sua parte e dá condições para que a programação do software seja iniciada.

<h2>Design de Arquitetura</h2>

O design de arquitetura é resultado da análise dos requisitos não-funcionais, os quais dão origem à arquitetura do sistema e às especificações de hardware e de software. Seu objetivo é estabelecer a forma com que os recursos de hardware sustentarão a implementação dos componentes de software do sistema. Para tanto, realiza-se uma análise arquitetural que pode ser vista como uma especialização da análise de requisitos, com foco nos requisitos que influenciam a arquitetura.

Todo projeto de arquitetura de software deve levar em consideração quatro funções fundamentais de um sistema, são elas:
<ul>
  <li>Armazenamento de dados</li>
  <li>Lógica de acesso aos dados</li>
  <li>Lógica de aplicação</li>
  <li>Lógica de apresentação</li>
</ul>

Para este projeto foi adotada a arquitetura cliente-servidor. Esta arquitetura é a mais utilizada por aplicações Web e viabiliza o acesso ao sistema, bem como aos recursos computacionais para usuários conectados à Internet.

<h2>Requisitos Não-funcionais</h2>

Requisitos não-funcionais são requisitos de software; inerentes ao software. Na fase de Projeto os requisitos não-funcionais são a entrada para a criação do projeto de arquitetura. Requisitos não-funcionais agregam informações de suma importância ao desenvolvimento do software e dizem respeito às restrições impostas a este. Geralmente são em menor número que requisitos funcionais, mas têm maior abrangência no sistema e estão relacionados a diversos aspectos deste. São várias as categorias de requisitos e suas atribuições.

Para este projeto foram abordadas as categorias de requisitos de desempenho, requisitos de segurança, requisitos operacionais e requisitos culturais e políticos e suas respectivas subcategorias conforme a seguir:
<ul>
  <li>Requisito de desempenho</li>
       &nbsp &nbsp &nbsp - Requisito de velocidade
  <li>Requisitos de segurança</li>
       &nbsp &nbsp &nbsp - Requisitos de controle de acesso
  <li>Requisitos operacionais</li>
       &nbsp &nbsp &nbsp - Requisitos do ambiente técnico<br>
       &nbsp &nbsp &nbsp - Requisitos de manutenção<br>
       &nbsp &nbsp &nbsp - Requisitos de portabilidade<br>
  <li>Requisitos culturais e políticos</li>
       &nbsp &nbsp &nbsp - Requisitos multilíngues
</ul>

Para a organização dos requisitos não-funcionais foi utilizado um template que contém os atributos necessários à sua descrição.

<p align="center">
  <img src="https://victoranalyst.files.wordpress.com/2018/12/template-para-requisitos-nc3a3o-funcionais.png" style="max-width:100%;">
</p>

<h2>Especificação de Hardware e Software</h2>

A especificação de hardware e software se dá por meio da seleção de um conjunto de recursos de tecnologia que darão suporte à utilização do sistema. A configuração a ser obtida deve vir de encontro às necessidades do projeto, ou mais especificamente, deve ser compatível e viável para com os detalhes de implementação especificados.

A especificação dos recursos computacionais relaciona uma configuração básica e suficiente ao desenvolvimento do sistema e não considerou, neste momento, a implantação do software em um servidor na Web. O resultado da especificação de hardware e software é apresentado a seguir.

<p align="center">
  <img src="https://victoranalyst.files.wordpress.com/2018/12/especificac3a7c3a3o-de-hardware-e-software.png" style="max-width:100%;">
</p>

<h2>Design da Interface com o Usuário</h2>

té este momento, tudo o que foi projetado faz parte do funcionamento interno do sistema, e está oculto ao usuário – trata-se do desenvolvimento do back-end do software. Essas estruturas fazem a maior parte do trabalho da aplicação; isto, considerando a arquitetura cliente-servidor adotada. Como apresentado anteriormente, um sistema é comumente dividido em quatro funções principais: armazenamento de dados, lógica de acesso a dados, lógica de aplicação e lógica de apresentação, esta última sendo atribuída à construção do design de interface com o usuário.

A construção da interface gráfica com o usuário deve prover três propriedades fundamentais:
<ul>
  <li>Mecanismo de navegação</li>
  <li>Mecanismo de entrada</li>
  <li>Mecanismo de saída</li>
</ul>

Esses mecanismos são as principais vias de tráfego de informações que entram e saem do sistema, bem como recebem os comandos do usuário. Elas permitem que o usuário interaja com as funcionalidades implementadas à aplicação do lado do servidor.

Há uma vasta gama de ferramentas e tecnologias utilizadas na construção de interfaces gráficas. O projeto Smart E-commerce Atacadista, como um projeto de sistema Web, faz uso de tecnologias modernas e amplamente utilizadas na programação front-end. Elas foram escolhidas seguindo tendências de mercado, adequação ao tipo de projeto, resultado da análise de viabilidade técnica e domínio acadêmico por parte do autor. A seguir são listadas as tecnologias utilizadas na construção da interface gráfica com o usuário:
<ul>
  <li>ASP.NET</li>
  <li>Razor</li>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>Bootstrap</li>
</ul>

Um projeto de interface gráfica que atenda adequadamente às necessidades de interação do usuário com o sistema não deve ser elaborado com base em soluções empíricas. Isto porque há uma série de diretrizes e boas práticas que devem guiar o desenvolvimento desta tarefa. O conjunto de atividades e conceitos relacionados ao projeto de interface com o usuário faz parte dos estudos da interação humano-computador.

<h2>Interface Humano-computador</h2>

Projetar uma interface gráfica para um sistema computacional envolve seguir princípios que resultam em maior eficácia na interação com o usuário:
<ul>
  <li>Familiaridade para o usuário</li>
  <li>Consistência da interface</li>
  <li>Mínimo de surpresa</li>
  <li>Facilidade de recuperar-se</li>
  <li>Guia do usuário</li>
  <li>Diversidade de usuários</li>
</ul>

Com base nestes princípios, obteve-se uma direção para a elaboração da interface gráfica que atendesse adequadamente às necessidades envolvidas no projeto. Eles orientaram na elaboração do layout, obedecendo as propriedades fundamentais de interface gráfica.

<h2>User Interface – UI</h2>

A interface gráfica é o elemento que torna transparente ao usuário todo o complexo funcionamento do software e o possibilita utilizar de forma intuitiva e amigável. Utiliza-se, basicamente, de elementos de interação criados a partir da programação em linguagem de marcação, tipicamente o HTML. Para alcançar este objetivo, alguns princípios de design foram observados:
<ul>
  <li>Layout</li>
  <li>Conhecimento do conteúdo</li>
  <li>Experiência do usuário</li>
  <li>Consistência</li>
  <li>Minimização do esforço do usuário</li>
</ul>

Shneiderman apresenta um processo de cinco etapas para a elaboração da interface gráfica do utilizador, são elas:
<ul>  
  <li>Desenvolvimento dos cenários de uso</li>
  <li>Desenvolvimento do diagrama de estrutura de interface</li>
  <li>Desenvolvimento dos padrões de interface</li>
  <li>Prototipação do design de interface</li>
  <li>Avaliação da interface gráfica proposta</li>
</ul>

Para este projeto foram adotadas as etapas de desenvolvimento do diagrama de estruturas de interface e prototipação de interface.

O diagrama de estrutura de interface é um recurso muito útil para uma representação visual simplificada das interfaces que compõem o sistema, bem como as ligações que existem entre elas. Para auxiliar na elaboração do modelo, utiliza-se o diagrama de fluxo de dados e os cenários de uso. Estes dois artefatos anteriormente produzidos dão suporte à construção do diagrama de estrutura de interface. Para este projeto foram utilizados apenas os cenários de uso. O diagrama elaborado é apresentado a seguir.

<p align="center">
  <img src="https://victoranalyst.files.wordpress.com/2018/12/diagrama-de-estrutura-de-interface.png?w=984" style="max-width:100%;">
</p>

A segunda atividade realizada no projeto da interface gráfica foi a elaboração de protótipos de design. Estes foram criados utilizando wireframes que possibilitaram criar um layout sugestivo à apresentação do conteúdo na tela do computador. Para isto, foi utilizada a ferramenta de software Balsamiq na versão Web App. A seguir é apresentado um wireframe que representa a página para a compra de um produto.

<p align="center">
  <img src="https://victoranalyst.files.wordpress.com/2018/12/24-informac3a7c3b5es-de-um-produto-para-compra.png?w=984" style="max-width:100%;">
</p>

<h2>Design de Armazenamento de Dados</h2>

A criação do modelo físico de dados é a última das 3 etapas da modelagem de dados. A atividade consiste em escrever scripts utilizando a linguagem SQL, a partir das especificações presentes no modelo lógico. Esses códigos em SQL posteriormente serão interpretados por um sistema gerenciador de banco de dados previamente escolhido. Assim que o SGBD executa os scripts, surge um novo banco de dados, e então existirá, de fato, um local estabelecido que já poderá armazenar dados de uma aplicação. Para tanto, foi escolhido o formato de armazenamento que atendesse mais adequadamente as necessidades da aplicação. Foi selecionado o formato de banco de dados do tipo relacional, levando-se em consideração os seguintes aspectos:
<ul>
  <li>Tipos de dados</li>
  <li>Tipo de sistema de aplicação</li>
  <li>Formatos de armazenamento existentes</li>
  <li>Necessidades futuras</li>
</ul>

O sistema gerenciador de banco de dados adotado foi o Microsoft SQL Server 2017 edição Developer. Obtido o script SQL conforme especificado no modelo lógico, executou-se o código utilizando o ambiente integrado de gerenciamento, SQL Server Management Studio na versão 17.7. Após este procedimento obteve-se, então, a estrutura de banco de dados para o sistema.

<h2>Implementação – Construção do Sistema</h2>

A atividade de construção/programação do sistema iniciou-se a partir da base de dados já implementada, em um processo de engenharia reversa com o uso do ADO.NET Entity Framework, adotando uma técnica de implementação denominada database first.

Na técnica database first o modelo de dados é copiado para um arquivo dentro do IDE, podendo ser manipulado pelo desenvolvedor. Uma vez importado para o IDE, é possível executar a técnica de mapeamento objeto-relacional, na qual as tabelas do banco de dados dão origem a classes em uma abordagem orientada a objeto. Esta técnica permite uma correspondência entre tabelas e classes, onde cada registro em uma tabela representa uma instância na classe que a corresponde. Deste modo, construiu-se a parte inicial da aplicação, em um padrão de arquitetura em camadas, adotando o modelo Model-View-Controller, onde estabeleceu-se a conexão entre aplicação e o banco de dados.

A programação do software foi realiza no Visual Studio edição 2017. Este ambiente de desenvolvimento integra a .NET Framework. Com ela, foi utilizado o ASP.NET, um conjunto de bibliotecas e ferramentas para o desenvolvimento de aplicações baseadas na Web que engloba as diferentes partes da Web para dar aos desenvolvedores de sites da Web mais poder. Para o desenvolvimento deste projeto, foram utilizadas as seguintes linguagens:
<ul>
  <li>C#</li>
  <li>Razor</li>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>SQL</li>
</ul>

O processo de implementação evoluiu atendendo aos requisitos funcionais. Cada requisito era abordado ou parcialmente abordado à medida em que se obtinha o entendimento de como implementá-lo.

<h2>Implementação de Testes</h2>

Neste projeto de software, para o qual foi adotado um ciclo de vida de desenvolvimento de sistema com quatro fases, as atividades de testes foram incorporadas à fase de implementação.

Um processo de implementação de testes se divide em quatro estágios distintos e sequenciais, e cada um compreende diferentes tipos de teste e seus objetivos, são ele.

Este projeto adotou as técnicas de testes da interface com o usuário; testes de requisitos e testes de usabilidade. Cada teste teve maior ou menor participação, de acordo com a evolução da implementação do software.
