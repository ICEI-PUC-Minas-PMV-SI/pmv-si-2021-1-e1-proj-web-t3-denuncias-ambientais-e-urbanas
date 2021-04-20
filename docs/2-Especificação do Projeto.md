# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Como já mencionado, é notória a necessidade de se preservar o meio ambiente, com este projeto tentamos buscar resultados positivos referentes ao engajamento da sociedade civil no papel participativo, ciente e fiscalizador do meio ambiente. Através da exposição dos problemas ambientais, idealizamos se possível a curto, médio ou longo prazo solução para todas as denúncias ambientais.
A partir da definição do público alvo, identifica-se de forma mais especifica qual seria o usuário ideal do sistema que está sendo desenvolvido, desenvolvendo sua persona e as histórias de usuário. 
Para atender as demandas dos usuários, faz-se necessário o levantamento dos requisitos adequados, visualizando todas as funcionalidades que o sistema precisa ter para que seja funcional e que seja utilizado da forma que foi idealizado. Sendo assim, foram realizadas discussões entre o grupo para determinar as funcionalidades e telas essenciais para o funcionamento do sistema. 
Além disso, pensando no futuro do projeto e seu escalonamento, foram definidos alguns requisitos não -funcionais, que, apesar de não serem parte do projeto no momento, podem ser implementados no futuro. 
E ainda visualizamos algumas restrições ao sistema, fazendo algumas delimitações para que o desenvolvimento seja realizado de acordo com as diretrizes informadas. 


## Personas

1ª  Dona Cida tem 47 anos, moradora de Ribeirão das Neves, não tem formação acadêmica e trabalha de forma autônoma como revendedora de produtos de beleza. Ela pensa em criar bem os seus filhos, cuidar de sua moradia e de seu marido, com quem é casada há 20 anos. Frequentemente Cida tem problemas com seu vizinho, Pedro, que faz o descarte de seu esgoto em frente à sua casa. Não sabendo a quem recorrer dona Cida vive constantemente amargurada.

2ª  O senhor Claudio tem 49 anos, morador de Contagem, possui bacharelado em contabilidade e trabalha em seu escritório próprio, possuindo clientes e contatos em várias cidades. Claudio gosta de viajar para a praia e tomar uma cerveja. Por conta de sua rotina de trabalho, Claudio precisa viajar muito e constantemente em suas viagens percebe diversas queimadas ao longo de seu percurso, se sentindo muito incomodado com a situação, contudo desconhece a que órgão encaminhar uma denúncia.

3ª  José Felipe tem 32 anos, morador de Betim, possui experiencia na área de T.I trabalhando como programador e cursa Ciência da Computação. Em seu tempo livre, José gosta de assistir series e doramas. Como trabalha em home office ele passa bastante tempo em casa, contudo seu vizinho possui uma área verde extensa onde, após a limpeza, faz queimadas de suas folhas secas dia sim dia não, incomodando José que sempre tem que lidar com a fumaça causada por seu vizinho. Apesar de já ter recorrido à polícia através de um boletim, ele não obteve sucesso em sua reclamação. 

4ª  Fernanda tem 26 anos, é moradora de Sabará e trabalha como técnica em enfermagem. Quando está de folga de seus longos e cansativos plantões, gosta de ter contato com a natureza fazendo trilhas pela Serra do Cipó. Por fazer muitas trilhas Fernanda acaba visitando muitas cachoeiras onde se depara com resíduos de lixos e poluentes descartados pelos visitantes, prejudicando a fauna e a flora local. Consciente da necessidade de preservação ambiental Fernanda se sente frustrada por não conseguir realizar denúncias sobre tais situações, além do sentimento de impunidade para tal.

5ª  Antonio Joaquim tem 48 anos, é morador da região norte de Belo Horizonte é professor de Geografia da rede estadual e nas horas vagas gosta de praticar a fotografia como hobby. Por ser hipertenso gosta de realizar caminhadas matinais dentro do Parque Municipal Fazenda Lagoa do Nado, que fica próximo a sua residência, Antonio geralmente percebe que as nascentes que avista durante suas caminhadas estão sendo frequentemente pisoteadas, atrapalhando seu desenvolvimento. Preocupado com a preservação ambiental, Antonio se incomoda com tal situação e quer expor para a sociedade a degradação daquele parque. 

6ª  Maria Luiza tem 24 anos, é moradora de Juiz de Fora é estudante de Psicologia e quando não está em aula, gosta de ir ao cinema com os amigos e comer fora. Maria percebeu que ao lado de sua república um de seus vizinhos constantemente deixa as gaiolas de seus pássaros pela janela e que um deles se trata de uma arara azul, animal em extinção. Ao perceber a situação deplorável e ilegal do animal, Maria busca uma forma de realizar uma forma anônima este vizinho.

7ª  Kettyllyn Kamylle tem 18 anos e mora no nordeste do Estado, na cidade de Nanuque. Recém formada no Ensino Médio, sonha em ser veterinária e está estudando bastante para a prova do Enem. Kettyllyn faz visitas regulares a casa de sua avó e lá vê que os jovens da região realizam maus tratos aos animais abandonados pelos moradores dali, presenciando todos os tipos de violência física contra os bichinhos. Muito entristecida com o que vê, Kettyllyn quer uma forma de reprimir os maus tratos realizados. 

8ª  Joaquim, morador de Três Marias, não teve oportunidade de estudar durante a infância, possuindo apenas o Ensino Fundamental incompleto. Ele tem 42 anos e desde de criança pesca no rio São Francisco, tanto para consumo quanto para venda na barraca que possui com sua esposa. Como está sempre pescando, Joaquim percebeu que há algum tempo a qualidade e quantidade dos peixes está diminuindo, e ao navegar ao longo do rio visualiza que umas das indústrias locais estão descartando seus dejetos químicos ali. Revoltado com o comprometimento de sua única fonte de renda, Joaquim quer expor a atividade ilegal desta indústria para toda a população. 


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Cida                | denunciar descarte ilegal de esgoto| evitar que tal prática se repita, causando a proliferação de pragas como baratas e ratos.  |
|Claudio| comunicar às autoridades competentes a ocorrência de queimadas e desmate de áreas verdes remotas | facilitar a ciência do órgão competente destas ocorrências, agilizando assim sua ação.|
|José Felipe| denunciar seu vizinho que constantemente realiza queimadas em seu quintal | que o vizinho seja notificado da ilegalidade de sua ação pelas autoridades.|
|Fernanda| denunciar para o órgão competente ocorrência de descarte de lixo em áreas de preservação | preservar reservas ambientais, incentivando maior fiscalização destas áreas.  |
|Antonio Joaquim | denunciar pisoteamento de nascentes no Parque Municipal Fazenda Lagoa do Nado | expor para a sociedade a degradação daquele parque. |  
|Maria Luiza | denunciar, de forma anônima possuidor de animal silvestre |  preservar especies em extinção. |
|Kettyllyn Kamylle | denunciar maus tratos aos animais em situação de rua | coibir a violêcia contra os animais. |
|Francisco | denunciar descarte ilegal de dejetos químicos | preservar o meio ambiente, denuciando esta pratica ilegal.  |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001 Cadastro| O sistema deve permitir aos usuários realizar cadastro. 
|RF-002 Login| O sistema deve permitir aos usuários realizar login para acesso à área restrita do sistema. | ALTA | 
|RF-003 Minha Conta| O sistema deve permitir aos usuários ter sua propria página de conta. | ALTA | 
|RF-004 Foto| O sistema deve permitir aos usuários carregar no máximo 2 fotos vínculadas às denúncias. | ALTA |
|RF-004 Mapa| O sistema deve permitir aos usuários adicionar o endereço da ocorrência na denûncia. | ALTA |
|RF-005 Denúncia| O sistema deve permitir aos usuários realizar uma ou mais denúncias. | MÉDIA |
|RF-006 Denúncia| O sistema deve permitir aos usuários realizar denúncia de forma anonima ou não. | MÉDIA |
|RF-007 Logout| O sistema deve permitir  que o usuário realize logout para sair do sistema. | MÉDIA |
|RF-008 Pesquisa| O sistema deve permitir que o usuário procure por denúncias. | MÉDIA 
|RF-009 Interação| O sistema deve permitir que o usuário interaja com a denúncia, no espaço para comentários com limite de caracteres. | BAIXA |
|RF-010 Exclusão| O sistema deve permitir que o usuário exclua as denúncias realizadas por ele mesmo. | BAIXA |
|RF-011 Acesso| O sistema deve permitir que o usuário tenha acesso á pagina de denúncias. | ALTA |
|RF-012 Próxima Página| O sistema deve permitir que o usuário navegue para a próxima página até a paginação alcançar o seu limite de denúncias. | ALTA |
|RF-013 Página Anterior| O sistema deve permitir que o usuário retorne à página anterior até a paginação alcançar o seu limite de denúncias. | ALTA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser implementado utilizando as seguintes ferramentas e linguagens de programação para o Front-End: HTML, CSS e JavaScript. | ALTA | 
|RNF-002| Todos os dados pessoais dos usuários devem passar por medidas de proteção e criptografia de mais alto nível, a fim de garantir o máximo de segurança e privacidade possível. | ALTA | 
|RNF-003| O sistema deve ser implementado primeiramente na forma de um site e, posteriormente, conforme o avanço dos semestres, será implementado também na forma de um aplicativo. | MÉDIA |
|RNF-004| O sistema deve ser compatível com os navegadores mais utilizados no mercado (Google Chrome, Firefox, Microsoft Edge). | ALTA | 
|RNF-005| O sistema não deve conter anúncios invasivos e fraudulentos que prejudiquem a experiência do usuário. | MÉDIA |
|RNF-006| O sistema deve fornecer uma funcionalidade de Alto Contraste, garantindo assim a acessibilidade de usuários com dificuldades visuais. | MÉDIA |


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| A primeira parte do projeto (Front-End) deve ser entregue até o final do semestre, não podendo extrapolar a data de 12/07/2021, onde será avaliado pelo professor e o feedback será passado aos alunos. |
|02| A equipe não pode tercerizar o desenvolvimento de funcionalidades do sistema. |
|03| O projeto não pode ser desenvolvido um módulo de backend. |



