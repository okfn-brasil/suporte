# Infraestrutura da OKBr

No presente documento o termo  *infraestrutura* pode ser referente a:

* **infraestrutura de comunicação**: ambientes de comunicação da OKBr, tais como  [blog e site](https://br.okfn.org/), [DiscussOKBr](https://discuss.okfn.org/c/local-groups/okbr), [mail-admin](http://admin.google.com/), e outros.

* **infraestrutura básica**: vinculada à manutenção e preservação do patrimônio. Exemplo: gestão técnica dos [nomes de domínio](https://en.wikipedia.org/wiki/Domain_name), gestão das contas de e-mail `fulano@ok.org.br`, gestão dos [servidores-web](https://en.wikipedia.org/wiki/Web_server) e dos bancos de dados de uso comum (institucionais ou sendo reutilizados para mais de um projeto).

* **infraestrutura de desenvolvimento**: infra dos projetos... [repositórios](https://github.com/orgs/okfn-brasil) de desenvolvimento, servidores-web de teste, bancos de dados temporários, etc.

Quando o termo *infraestrutura* não vier especificado, refere-se ao "caso geral", dado pela união dos casos listados acima.

Abaixo os elementos estruturais da infraestrutura da OKBr.

## Máquinas servidoras
Atualmente todas Digital Ocean, exceto servidor de email _G Suite_.

* Maquina-1
* Maquina-2

... reconstruir tabelas e citar CSV.


## Serviços instalados nas máquinas
* Web server
* SQL server
* etc. server
* Mail server sob _G Suite_.

## Arquitetura do acesso aos serviços

Organização das pastas online, API-gateways, microservicos, acessos GraphQL, SQL, e cia.
