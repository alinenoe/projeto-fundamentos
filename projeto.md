<img src='/img/logo.png' alt='logo da empresa' width='150px' heidth='150px'/>

# MoreTech

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Yan Fernando Lobato|Gerente de Projeto|yanlobato84@gmail.com|
|Mateus Orocondo Lopes Aguirre|Desenvolvedor|Mateusorocondo78@gmail.com|
|Elias Moreira dos Santos|Desenvolvedor|elias.moreiradossantos.28@gmail.com|
|Eduardo dos Santos Edegar Fernandes|Desenvolvedor|eduardoedegarfernandes@gmail.com|
|Sidnei Salustiano paulino Junior|Desenvolvedor|juniorsalustianopaulino@gmail.com|
|Janine Rodrigues Schulz|Desenvolvedor|rodrigijanine2@gmail.com|
|Aline Noemerg Grey|Desenvolvedor|noemerggrey@gmail.com|

# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES](#convenções-termos-e-abreviações)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO |MoreTech |
| GERENTE DO PROJETO | Yan Fernando Lobato |
| PRINCIPAL OBJETIVO | Vender os melhores produtos e oferecer atualização do mundo tecnológico ao cliente |
| BENEFÍCIOS ESPERADOS |* Melhor conforto com periféricos;<br/>* Produtos baratos com ótima qualidade;<br/>* Uma boa experiencia;<br/>* Noticias atualizadas sobre tecnologia|
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](#fibonacci-management-system) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_MoreTech_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem.

## CONCEPÇÃO DO SISTEMA

Esse projeto surgiu nas ferias do primeiro para o segundo ano, com 2 dos nossos 6 desenvolvedores que resolveram fazer um mini site juntos, para treinar uma determinada linguagem de programação, o orientador deu uma atividade para o final do ano e pensamos em dar um passo a frente para o projeto, ja que tinhamos parado na metade. Agora com mais conhecimento devemos conseguir ainda mais nossos objetivos.



## CONVENÇÕES, TERMOS E ABREVIAÇÕES

Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:

* EaD: Eaducação a Distância
* Moodle: Ambiente Virtual que hospedará os cursos oferecidos
* Exame Final: Avaliação destinada aos estudantes que obtiveram média anual inferior à 60 pontos

[ [INÍCIO](#fibonacci-management-system) ]

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO

### NO ESCOPO

O projeto consiste na construção de uma ferramenta para todos os amantes de tecnolgia ou até mesmo um mero novato que está chegando agora a conhecer essa área tão extraordinária. Ele visa deixar qualquer pessoa dentro das notícias desse imenso mundo da tecnologia que vem evoluindo rapidamente, sendo que muitas vezes até mesmo nós não conseguimos acompanhar tamanha evolução, mas com nosso projeto garantimos que você não perderá nada e também com a nossa loja o cliente consegue satisfazer suas necessidades com a nossa variedade de produtos, como laptops, desktops, periféricos, smartphones e muito mais.

### FORA DO ESCOPO

Não fazem parte do escopo do projeto:
* Contato frequente com o usuário;
* Acessibilidade para deficientes visuais e auditivos;
* Local de publicidade e anuncios para de divulgação de terceiros;
* Conteudos divergentes a tecnologia;
* Disponibilidade de entrega da loja para determinados países e cidades.

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e enviar mensagens. Todos demais usuários estendem as funcionalidades do UsuárioPadrão|
|**Administrador:**|Responsáveis pelo gerenciamento das entidades pertinentes à instituição e pela alocação de outros administradores|
|**Coordenador:**|Responsáveis pela aprovação de disciplinas, turmas e matrículas realizadas pela secretaria do curso, além de ser responsável pela alocação da secretaria|
|**Secretaria:**|Responsáveis pelo cadastramento de disciplinas e turmas, pela alocação de professores e monitores de um curso e matrículas dos alunos|
|**Professor:**|Responsáveis pela criação do programa da disciplina através de ferramentas de planejamento e criação de atividades|
|**Aluno:**|Seguem o programa da disciplina criada pelo professor, tendo como apoio ferramentas de comunicação, tal como: chat e fórum|

## Abrangência e sistemas similares

### Abrangência:

O sistema irá conter ferramentas para construção de um plano de aulas que esteja de acordo com os objetivos e metodologia de uma turma ministrada pelo professor. O professor através de ferramentas (como Chat, Fórum, Base de Documentos) irá montar o programa desta disciplina que deverá ser seguido pelo aluno usuário do sistema. O professor terá a liberdade de criar atividades (textos e questionários) e determinar prazos a serem cumpridos pelos alunos. Serão armazenadas as resoluções dos alunos para serem corrigidas pelo professor posteriormente, gerando estatísticas do desempenho de cada aluno e da turma. O sistema também irá prover o gerenciamento das entidades que compõem a instituição e os usuários do sistema.

Dentre as ferramentas de comunicação do sistema existirão as assíncronas, como Chat, onde poderão ser feitas reuniões, discussões, explicações conjuntas ou qualquer outra atividade de comunicação. O Fórum consiste na ferramenta síncrona usada para os mesmos fins do Chat.

Das ferramentas de planejamento podemos citar:

* **Avaliações e Exercícios:** serão criadas tarefas a serem entregues pelos alunos nos determinados prazos;

* **Anúncios:** espaço para criação de avisos e informes aos alunos de uma determinada turma;

* **Manipulação de Arquivos:** haverá um diretório onde podem ser acumulados arquivos de diversos tipos pelos usuários;

* **Planejamento de Aulas:** planejamento de uma aula estruturada com leituras e exercícios.

### Sistemas similares:

No cenário atual da universidade se encontra um sistema que é responsável por realizar tal tarefa, denominado Virtus, porém o sistema não atende todas as necessidades, não sendo considerado satisfatório pela maioria dos usuários.

No cenário nacional encontram-se três sistemas que se destacam:

**AulaNet:** é um ambiente de software baseado na Web, desenvolvido no Laboratório de Engenharia de Software - LES - do Departamento de Informática da PUC-Rio, para administração, criação, manutenção e participação em cursos à distância.
WebAula: é um produto formado por soluções integradas de gerenciamento de aprendizagem, conhecimento e conteúdos on-line, resultado de uma joint venture entre as empresas Zargon e Poliedro.

**TelEduc:** é um ambiente para a criação, participação e administração de cursos na Web. Ele foi concebido tendo como alvo o processo de formação de professores para informática educativa, baseado na metodologia de formação contextualizada desenvolvida por pesquisadores do Nied (Núcleo de Informática Aplicada à Educação) da Unicamp.

No cenário internacional os sistemas de maior porte são:

**WebCT:** O WebCT é um programa que possibilita a criação de ambientes educacionais na Internet, desenvolvido pela University of British Columbia - Canadá. Ele permite a colocação do conteúdo de um curso na Internet pelo professor e, em seguida, o cadastro os alunos que participarão daquele curso. O objetivo principal é possibilitar a interação entre tais sujeitos através de ferramentas de trabalho em grupo, tais como: fóruns de discussão, chat, palestras on-line, além de facilitar a comunicação professor-aluno, através da publicação de notas e gabaritos de avaliações.

**Blackboard:** é um sistema de autoria extremamente amigável, desenvolvido para ser utilizado por educadores e profissionais interessados em aplicar as novas tecnologias interativas da rede na educação, contribuindo para a metodologia de ensino presencial e potencializando o processo de ensino e aprendizagem a distância.

## Suposições e dependências
O sistema necessita de um servidor web para sua hospedagem.

Os usuários devem utilizar um computador com a seguinte configuração mínima:

* Processador Dual Core 2GHz ou superior
* 2Gb de memória RAM
* 5Gb de armazenamento em disco
* Para uso do sistema é preciso ter instalado o Java SE versão 8 e o MySql versão 8.0.28.

# ESTUDO DE VIABILIDADE

Uma vez definidos a necessidade para o sistema e seus requisitos de negócio, é possível compreender melhor o projeto do sistema proposto para elaborar o estudo de viabilidade com os seguintes destaques:

## Viabilidade Técnica
Para a MoreTech, que vende eletrônicos e tem um site de notícias sobre tecnologia, é importante pensar em algumas coisas práticas. Para vender online, eles precisam de um site que funcione bem e seja seguro, e também de pessoas que saibam como vender pela internet. Eles devem cuidar do estoque e proteger os dados dos clientes. Quanto ao site de notícias, é bom ter um site que permita publicar notícias com facilidade, com textos, fotos e talvez vídeos. É importante ter gente que entenda de tecnologia para escrever as notícias. E é sempre bom ficar de olho para ver como o site está se saindo. Investir do jeito certo em tecnologia, segurança e gerenciamento é fundamental para ter sucesso nas vendas online e nas notícias de tecnologia.

## Viabilidade Econômica

O site é Viável do ponto de vista econômico custando na contratação de desenvolvedores e designer em torno de R$ 30.000, mas com os
funcionarios do projeto que iram tratar da manutênção do site e outros com os updates, os funcionarios da manutênção vão fazer
atualizações de 4 em 4 meses, custará em média de R$ 12.000/ano. Para sustentar esse valor será cobrado do vendedor uma taxa de 8% por
venda e a sua hospedagem no site com o valor de R$ 89.99/mês. Para ganhar dinheiro, eles podem usar anúncios ou assinaturas. Investir do jeito certo em tecnologia, segurança e gerenciamento é fundamental para ter sucesso nas vendas online e nas notícias de tecnologia.

## Viabilidade Organizacional

Do ponto de vista organizacional o software foi feito para ser intuitivo para adesão de novos clientes, para o facilitamento de compras e a viabilidade sobre o mundo tecnológico. De modo geral o nosso público alvo está acostumado a usar sites para compras de produtos  de informática, porém acreditamos que nosso site poderá ser atrativo para o nosso público por ser focado somente no mundo da informática, tendo análises críticas feitas por profissionais da área. Em resumo, a aplicação será aceita pelos nossos futuros clientes por ser algo novo e especializado na área.



[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento
Para a construção desse software usaremos o scrum. O scrum foi escolhido por ser uma metodologia mais flexível, visando que poderemos sofrer mudanças no que se trata a venda de produtos, permitindo rapidamente a ajustar ao nosso objetivo. O segundo ponto é que essa metodologia está fortemente ligada ao trabalho em equipe e uma grande comunicação entre os setores, facilitando o entendimento necessário para a aplicação do software, já que que será usado a abordagem incremental será vantajoso a entregas de pequenas partes da loja virtual sendo testado e avaliado pelos nossos proprietários. Mais um ponto para a escolha do scrum é o gerenciamento de risco pelas avaliações dos sprints, após feita a revisão e identificando os erros, o projeto pode ser maior preparado após concluído. 



[ [INÍCIO](#fibonacci-management-system) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 |Tela de cadastro | Oaplicativo deve conter uma tela de cadastro para o usuário colocar as seguintes informações: nome completo, E-mail,  numero de telefone e CPF.| 
|RF-002 | Carrinho de compra. |permitir o cliente adicionar produtos em um carrinho de compra virtual, visualize a quantidade e o valor do produto.|
|RF-003 | Cancelar pedido |permitir o cliente cancelar uma futura compra|
|RF-004 | Opções de pagamento |facilitar o sistema de pagamento oferecendo varias forma de pagamento, como cartão de crédito, débito, paypal  e etc.|
|RF-005 | Visualizar informações do produto |permitir visualização de informações do produto, bem como imagens, descrição, e funcionalidades.|
|RF-006| Buscar produtos |permitir o usuário buscar o produto que deseja com palavras chaves.|
|RF-007| Postar noticias |permitir certos usuários postarem noticias  do mundo tecnológico.|
|RF-008| Opção de comentarios |permitir o usuário compartilhar noticias e opiniões.|
|RF-009|Visualizar estoque |Emitir relatório da quantidade dos produtos que estão disponíveis
|RF-010|notificador o cliente|o sistema deve notificar o cliente ao ser atualizado e quando novas notícias|
|RF-011| colocar imagens do produto| permitir ao vendedor colocar imagens do seu produto, para maior confiança do cliente|
|RF-012| permitindo ao cliente escolher o local de entrega| disponipizar uma aba para serem colocadas informações do local de entrega.
|RF-013| enviar rastreamento| oferecendo sistema de rastreamento para cliente receber atualização do seu produto|
|RF-014| Calcular o valor total da compra|calcular os itens que estão no carrinho do cliente|
|RF-015| menu adicionar | o sistema deve ter um menu que siga recomendações de produtos e notícias para o usuário, de acordo com suas movimentações|
|RF-015| Tela inicial | O sistema deve apresentar uma tela inicial, exibindo as opções do site
|RF-017| Tela de ajuda | a tela inicial deve apresentar uma opção de ajuda para o usuário|
|RF-018| opção de falar com o suporte| na tela de ajuda possibilitar ao cliente falar com o suporte|
|RF-019| A tela de ajuda deve conter perguntas frequentes | ter um painel com respostas de perguntas frequentes|
|RF-020| recuperação de senhas  | real de cadastro deve ter uma opção de recuperar senha, através do dados cadastrados|
## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001|Verificado vendedor|O aplicativo deve verificar os vendedores|
|RNF-002|Aplicação Responsiva| O aplicativo deve ser responsivo a determinados aparelhos conectados|
|RNF-003|Visualização bem legível|O aplicativo dele conter uma boa visualização de navegação| 
|RNF-004|Abrir em menos de 5 segundos|Não deixar o usuário esperar muito tempo|
|RNF-005|Não consumir muito espaço no computador|O aplicativo deve ter bem otimizado para uso|
|RNF-006|Privacidade de dados pessoais|Deve manter as informações do usuário e dados pessoais em anonimato|
|RNF-007| Estalabilidade|deve não ocorrer travamentos|
|RNF-008| Aplicativo seguro|O aplicativo deve ser seguro para o usuário fazer tranzações|
|RNF-009|Vendedor confiável|Deve conter vendedores confiaveis|
|RNF-010|Transações rápidas|O aplicativo deve conter transações rápidas e seguras|



[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

https://www.figma.com/file/FwQ2dFRINnI8tQhk4Du9en/Untitled?type=design&node-id=0%3A1&mode=design&t=tuc6sXD2L7VIz74y-1

![Imagem do Protótipo](/img/more.png)
)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Casos de Uso


![Diagrama de Casos de Uso](/img/caso.png)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Cadastrar Professor

### UC-01 - Manter noticias  
### UC-02 - Verificar estoque 
### UC-03 - Manter clientes 
### UC-04 - Selecionar cliente 
### UC-04 - Manter produto 
### UC-05 - Adicionar item
### UC-06 - Remover item 
### UC-07 - Adicionar desconto 
### UC-08 - Fazer pedido
### UC-09 - Cancelar Pedidos
### UC-10 - Incluir informações de entrega
### UC-11 - Selecionar forma de pagamento
### UC-13 - Vizualizar pedido
### UC-14 - Vizualizar informações de entrega
### UC-15 - Cadastrar usuario
### UC-16 - Compartilhar noticia
### UC-17 - Vizualizar noticias
### UC-18 - Comentar noticia
### UC-19 - Alterar informações de cadastro
 
## Matriz de Rastreabilidade


| REQUISITO |UC-01|UC-02|UC-03|UC-04|UC-05|UC-06|UC-07|UC-08|UC-09|UC-10|UC-12|UC-13|UC-14|UC-15|UC-16|UC-17|UC-18|UC-19|UC-20| 
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X| | | |X| | | | | | | | | | | |X| | |
|RF-002| |X| | | | | | | | | | | |X| | | | | |
|RF-003| | | | | | | | | | | | | | | | | | | |
|RF-004| || |X| | | | | | | | | | | | | | | |
|RF-005| | | | | X| | | | | | | |X| | | | | | |
|RF-006| | | |X| | | | | | | | | | | | | | | |
|RF-007|| | | | | |X | | |X| | | |X| | | | | |
|RF-008| | | | | | | | | | | | | | | | | | | |
|RF-009|X| | | | | | | | |X | | | | | | | | | |
|RF-010| |X| |X| | | | | | | | | | | | | | | |
|RF-011|X| | | | | |X| | |X | | | | | | | | | |
|RF-012| |X| || | | |X | | | | | | | | | | | |
|RF-013|X| | | | | | | | | | | | | | | | | | |
|RF-014| |X| || | | |X| | | | | | | | | | | |
|RF-015|X| | | | | | | | | | || | | X| | | | |
|RF-016| || |X| | | | | | | | | | | | | | | |
|RF-017|X| | | | | | | | | | | | | | | | | | |
|RF-018| || |X| | | | | | | | | | | | | | | |
|RF-019| | | | | | | | | | | | | | | | | | | |
|RF-020| || |X| | | | | | | | | | | | | | | |


[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes
![Diagrama de Classes](/img/imgClasses.png)


[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Sequências

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
