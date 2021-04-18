# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

1*    Dona Cida tem 47 anos, moradora de Ribeirão das Neves, não tem formação acadêmica e trabalha de forma autônoma como revendedora de produtos de beleza. Ela pensa em criar bem os seus filhos, cuidar de sua moradia e de seu marido, com quem é casada há 20 anos. Frequentemente Cida tem problemas com seu vizinho, Pedro, que faz o descarte de seu esgoto em frente à sua casa. Não sabendo a quem recorrer dona Cida vive constantemente amargurada.

2*    O senhor Claudio tem 49 anos, morador de Contagem, possui bacharelado em contabilidade e trabalha em seu escritório próprio, possuindo clientes e contatos em várias cidades. Claudio gosta de viajar para a praia e tomar uma cerveja. Por conta de sua rotina de trabalho, Claudio precisa viajar muito e constantemente em suas viagens percebe diversas queimadas ao longo de seu percurso, se sentindo muito incomodado com a situação, contudo desconhece a que órgão encaminhar uma denúncia.

3*    José Felipe tem 32 anos, morador de Betim, possui experiencia na área de T.I trabalhando como programador e cursa Ciência da Computação. Em seu tempo livre, José gosta de assistir series e doramas. Como trabalha em home office ele passa bastante tempo em casa, contudo seu vizinho possui uma área verde extensa onde, após a limpeza, faz queimadas de suas folhas secas dia sim dia não, incomodando José que sempre tem que lidar com a fumaça causada por seu vizinho. Apesar de já ter recorrido à polícia através de um boletim, ele não obteve sucesso em sua reclamação. 

4*    Fernanda tem 26 anos, é moradora de Sabará e trabalha como técnica em enfermagem. Quando está de folga de seus longos e cansativos plantões, gosta de ter contato com a natureza fazendo trilhas pela Serra do Cipó. Por fazer muitas trilhas Fernanda acaba visitando muitas cachoeiras onde se depara com resíduos de lixos e poluentes descartados pelos visitantes, prejudicando a fauna e a flora local. Consciente da necessidade de preservação ambiental Fernanda se sente frustrada por não conseguir realizar denúncias sobre tais situações, além do sentimento de impunidade para tal.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Cida                | denunciar descarte ilegal de esgoto| evitar que tal prática se repita, causando a proliferação de pragas como baratas e ratos.  |
|Claudio| comunicar às autoridades competentes a ocorrência de queimadas e desmate de áreas verdes remotas | facilitar a ciência do órgão competente destas ocorrências, agilizando assim sua ação.|
|José Felipe| denunciar seu vizinho que constantemente realiza queimadas em seu quintal | que o vizinho seja notificado da ilegalidade de sua ação pelas autoridades.|
|Fernanda| denunciar para o órgão competente ocorrência de descarte de lixo em áreas de preservação | preservar reservas ambientais, incentivando maior fiscalização destas áreas.  

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001 Cadastro| O sistema deve permitir aos usuários cadastrados realizar login para acesso à área restrita do sistema. Login por número de Celular ou e-mail mais senha de acesso definida pelo usuário. | ALTA | 
|RF-002 Denúncia| O sistema permite aos usuários realizar uma ou mais denúncias. Usuário opta por fazer denúncia anônima ou não. | MÉDIA |
|RF-003 Logout| O sistema permite que o usuário realize logout para sair do sistema. | MÉDIA |
|RF-004 Pesquisa| O sistema permite que o usuário procure por denúncias. | MÉDIA 
|RF-005 Interação| O sistema permite que o usuário interaja com a denúncia, no espaço para comentários com limite de caracteres. | BAIXA |
|RF-006 Exclusão| O sistema permite que o usuário exclua as denúncias realizadas por ele mesmo. | BAIXA |
|RF-007 Acesso| O sistema permite que o usuário tenha acesso á pagina de denúncias. | ALTA |
|RF-008 Próxima Página| O sistema permite que o usuário navegue para a próxima página até a paginação alcançar o seu limite de denúncias. | ALTA |
|RF-009 Página Anterior| O sistema permite que o usuário retorne à página anterior até a paginação alcançar o seu limite de denúncias. | ALTA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
