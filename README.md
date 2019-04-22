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
