# Termo de Referência dos Serviços da Equipe de Suporte da OKBr

Regras, datasets e tickets de suporte, para a gestão e transparência da Equipe de Suporte da OKBr. Repositório oficial.

A equipe de suporte realiza uma série de pequenos atendimentos e pequenos serviços,  que precisam ser registrados de forma transparente, tanto para a prestação de contas, como para tirar dúvidas e permitir o acompanhamento da comunidade.
Neste repositório são registrados os tickets, as horas de suporte consumidas em cada ticket, as horas de atendimento consumidas com a triagem de solicitações, com e-mails, etc.

## Infraestrutura

No presente documento o termo  *infraestrutura* pode ser referente a: 

* **infraestrutura de comunicação**: ambientes de comunicação da OKBr, tais como  [blog e site](https://br.okfn.org/), [DiscussOKBr](https://discuss.okfn.org/c/local-groups/okbr), [mail-admin](http://admin.google.com/), e outros.

* **infraestrutura básica**: vinculada à manutenção e preservação do patrimônio. Exemplo: gestão técnica dos [nomes de domínio](https://en.wikipedia.org/wiki/Domain_name), gestão das contas de e-mail `fulano@ok.org.br`, gestão dos [servidores-web](https://en.wikipedia.org/wiki/Web_server) e dos bancos de dados de uso comum (institucionais ou sendo reutilizados para mais de um projeto).

* **infraestrutura de desenvolvimento**: infra dos projetos... [repositórios](https://github.com/orgs/okfn-brasil) de desenvolvimento, servidores-web de teste, bancos de dados temporários, etc.

Quando o termo *infraestrutura* não vier especificado, refere-se ao "caso geral", dado pela união dos casos listados acima.

## Equipe de suporte e papeis

A Equipe de Suporte da OKBr requer uma ou mais pessoas autorizadas pela Diretoria da OKBr a desempenharem diferentes tarefas. Alguns serviços são remunerados outros são voluntários, conforme fixado pelo Regimento Interno. A remuceração é realizada por empreitada, após a comprovação da realização dos serviços. Os comprovantes primários  ficam registrados neste repositório. 

Papeis gerais e categoriais de serviços de suporte previstos:

* usuários **administradores** (da infraestrutura): são usuários com acesso completo à interface da infraestrutura, incluindo a capacidade de alterar privilégios de usuário e grupos. Eles são responsáveis por implementar qualquer decisão técnica de acordo com o consenso da comunidade, e podem lidar com situações de emergência, tais como vandalismos. 

* usuários **moderadores**: usuários dos ambientes de comunicação, com privilégios menores que os usuários-administradores, para apoiar no acolhimento de novos usuários, resolução de conflitos, e encaminhamento (triagem) de solicitações de suporte. 

Os serviços são detalhados [nesta Wiki](https://github.com/okfn-brasil/suporte/wiki).

## Tarefas com ticket

A princípio todas as tarefas requerem um ticket e sua contabilização como serviço de suporte requer a conclusão dos tickets. As poucas excesões são tratadas na seção "tarefas sem ticket" abaixo. As tarefas com ticket recebem rótulo ([label](https://github.com/okfn-brasil/suporte/labels))  conforme finalidade:

* infra-comunic: solicitação de manutenção da infraestrutura de comunicação.
* infra-basica:  solicitação de manutenção da infraestrutura básica.
* infra-desenv:  solicitação de manutenção da infraestrutura de desenvolvimento.
* vandalismo: aviso de ocorrência de "vandalismo" (ex. spam no DiscussOKBR ou nas git/issues) 
* acolhimento: pedido de apoio para acolher ou orientar novos usuários.
* dominio: solicitação de manutenção do DNS ou domínio.
* caixa-mail: ...
* ...

### Registros dos  tikets

Estamos usando o [recurso do *Github/issues*](https://help.github.com/articles/about-issues/) para o registro dos tikcets, disponível em  [github.com/okfn-brasil/**suporte/issues**](https://github.com/okfn-brasil/suporte/issues).

Depois que o ticket é registrado pelo usuário ou pelo gerente do suporte, um dos membros da equipe assume o ticket até o seu fechamento. O histórico dos tickets da OKBr é público, fica armazenado no presente repositório.

Foi convencionado que o **tempo mínimo por resolução de ticket é de 10 minutos**, e que ao gastar mais tempo o suporte deve informá-lo em uma linha separada (não-agregada) na planilha.

## Tarefas sem ticket

Uma série de atividades, principalmente vinculadas à comunicação, tomam tempo e não podem ser registradas como "solução de um  ticket". Por isso além da planilha de sumarização das horas-ticket (abaixo), a *equipe de suporte* deve prestar contas preenchendo linhas da planilha de [planilha de horas-atendimento](data/horas-atendimento.csv) desvinculada dos tickets, relativas a:

* triagem de e-mails: horas gastas abrindo, lendo e avaliando chamados postados por e-mail ou DiscussOKBr. <br/>O registro do valor de horas complementa-se pelo registro do número de e-mails/posts de suporte.

* triagem de tickets: quando o próprio usuário redige a sua solicitação, é necessário que a equipe do suporte classifique e  revise. Alguns podem ser classificados como dúvidas, não sendo registrados como tickets de suporte. <br/>Complementa-se pelo registro do número de atendimentos sem demanda por resolução.

**Nenhuma outra forma de atendimento sem ticket é prevista**. 

## Dúvidas

* COMO ENVIAR UM TICKET DE SUPORTE?<br/> É preciso apenas estar logado no Github. Ver ... com o passo-a-passo.

* COMO LER E RESPONDER O TICKET DE SUPORTE?<br/> Da mesma forma, interagindo pela interface Github, que também permite o uso de e-mail.

* QUAL O PRAZO DE RESPOSTA?<br/> 12hs a 90hs conforme o caso, em dias comerciais.  ... Quando for necessário um agendamento de tarefa, a agenda deve ser comunicada por escrito neste prazo, também na interface do Github.  

NOTA: Pedimos que não envie tickets de suporte com o mesmo assunto se já existem tickets em aberto. Se já existem tickets em aberto, basta respondê-lo.

-----

## Licença
Todos os conteúdos deste repositório *git*, incluindo conteúdos postados por terceiros nas *issues*, estão sob licença "Creative Commons Atribuição 3.0 Brasil".<br/>
[
&nbsp;&nbsp;![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/16/CC-BY_icon.svg/88px-CC-BY_icon.svg.png)<br/>
&nbsp;&nbsp;&nbsp;**CC-BY-3.0**](https://creativecommons.org/licenses/by/3.0/br/)


