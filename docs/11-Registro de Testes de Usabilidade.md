[Planilha_Avaliação_Usabilidade-para o git.xlsx](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2021-1-e1-proj-web-t3-denuncias-ambientais-e-urbanas/files/6766995/Planilha_Avaliacao_Usabilidade-para.o.git.xlsx)
# Registro de Testes de Software

<span style="color:red">Pré-requisitos: <a href="7-Programação de Funcionalidades.md"> Programação de Funcionalidades</a></span>, <a href="10-Plano de Testes de Usabilidade.md"> Plano de Testes de Usabilidade</a>

Relatório com evidências dos testes e relatos dos usuários participantes, baseado em um plano de testes pré-definido.

> **Links Úteis**:
> - [Ferramentas deTestes de Usabilidade](https://www.usability.gov/how-to-and-tools/resources/templates.html)[Planilha_Avaliação_Usabilidade-para o git.xlsx](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2021-1-e1-proj-web-t3-denuncias-ambientais-e-urbanas/files/6766926/Planilha_Avaliacao_Usabilidade-para.o.git.xlsx)

Teste de Usabilidade							
							
Tarefa	Descrição						
1- Suely	Teste de do login inválido						
2-Romulo	Teste de alteração de senha						
3-Gabriela	Teste de denúncia anônima						
4- Henry	Teste de responsividade						
							
							
Teste de 1							
Caso de teste	Descrição: Testar login inválido						
Pré -condição	Acessar a tela de cadastro						
Procedimento	1. O ator entra na tela de login atraves da aba cadastro                                                            2.O sistema pede o nome do usuário                                                                                              3. O ator digita o nome do usuário inválido                                                                                                   4. O sistema pede que o usuário digite a senha                                                                              5. O usuário digita a senha inválida e clica em enter                                                                                                                 						
Resultado esperado	O sistema deverá buscar a informação no registro e enviar mensagem de erro. A mensagem retornada será: "usuário ou senha inválido"						
Dados de entrada	Login de seis dígitos. Apenas números						
Prioridade	Alta						
Ambiente	Microsoft Windows 7, Google, Chrome						
Tecnica	Manual						
Iteração	Primeira						
							
							
Teste de 2							
Caso de teste	Descrição: Alterar senha						
Pré -condição	Acessar a tela de cadastro						
Procedimento	1. O ator entra na tela de cadastro após digitar login e senha;                                                         2.O ator deverá clicar em minha página e em alterar senha;                                                                                              3. O ator digita o nome do usuário;                                                                                                   4. O sistema pede que o usuário digite uma nova senha;                                                                     5. O usuário digita a uma nova senha e clica em salvar senha                                                                                                     						
Resultado esperado	O sistema deverá buscar a informação no registro e enviar mensagem de retorno. A mensagem retornada será: "senha alterada com sucesso"						
Dados de entrada	Digitar nova senha de seis dígitos						
Prioridade	Alta						
Ambiente	Microsoft Windows 7, Google, Chrome						
Tecnica	Manual						
							
Iteração	Primeira						
							
							
Teste de 3							
Caso de teste	Descrição: Fazer nova denúncia anônima						
Pré -condição	Acessar a tela "faça sua denúncia"						
Procedimento	1. O ator entra na tela de denúncia após fazer o login;                                                          2.O sistema pede os dados obrigátorios que estão em asterisco;                                                                                            3. O ator digita os campos mínimos como data e anexa a foto  se houver;                                                                                                                                                                                                                  4. Ousuário clica em salvar e denuncia;                                                                                           5. O usuário visualiza sua denúncia feita anonimamente						
Resultado esperado	O sistema salva a denúncia e envia uma mensagem: "denúncia enviada com sucesso      						
Dados de entrada	Data do dia da denúncia e foto anexa em formato jpg.						
Prioridade	Alta						
Ambiente	Microsoft Windows 7, Google, Chrome						
Tecnica	Manual						
Iteração	Primeira						
							
Teste de 4							
Caso de teste	Descrição: Responsividade						
Pré -condição	Acessar todas as interfaces						
Procedimento	1. O ator entra em cada tela, uma por vez;                                                                                   2.O ator deverá minimizar a tela e quando diminuir ao maxima a tela deverá ficar responsiva, ou seja toda a tela deverá se adequar ao tamanho mínimo para melhor visualização;                                                                                                                                                 3. O ator volta a tela ao tamonho original e a tela volta ao normal;                                                                                                   						
Resultado esperado	Todas as telas testados deverão ser responsivas						
Dados de entrada							
Prioridade	Média						
Ambiente	Microsoft Windows 7, Google, Chrome						
Tecnica	Manual						
Iteração	Primeira						
							
							
Relatório de Defeitos- Teste 1 login inválido.   							
							
							
Reprodução passo a passo	O ator digitou o login inválido eo sistema entrou em minha página normalmente sem enciar a mensagem de login inválido.						
Evidência	Print da tela de erro. 						
Proposta de Correção							
							
Relatório de Defeitos- Teste 2 alteração de senha							
							
							
Reprodução passo a passo	O ator entrou natela " minha página" e clicou na opção alterar senha e o sistema entrou nesta págine e enviou esta mensagem de erro						
Evidência	Print da tela de erro. 						
Proposta de Correção							
							
Relatório de Defeitos- Teste 3 - denúncia anônima							
							
							
Reprodução passo a passo	O ator entrou nat ela " nova denuncia"digitou somente os campos obrigatórios sem se identificar e o sistema mandou uma pediu que preenchesse também o campo nome						
Evidência	Print da tela de erro. 						
Proposta de Correção							
							
Relatório de Defeitos- Teste 4 - telas responsivas							
							
							
Reprodução passo a passo	O ator diminuiu a tela ao máximo e o layout ficou somente em partes adequada a tela, faltou o menu suspenso ficar alinhado verticalmente						
Evidência	Print da tela de erro. 						
Proposta de Correção							
![image](https://user-images.githubusercontent.com/81451748/124534978-bc3b7b80-ddeb-11eb-8f95-dcb54d4bf7b7.png)
