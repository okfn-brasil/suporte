SPEC2 (passo-a-passo da instalação e configurações)

Certificar-se de [ter preparado adequadamente conforme SPEC1](SPEC1_requisitosGerais.md).

# step1 

Em seguida, a primeira coisa a fazer depois da troca de senha no `ssh`,  clonar o git deste projeto:
```sh
mkdir /tmp/sandbox
cd /tmp/sandbox
git clone http://git.ok.org.br/oficial.news.git
cd guia-config-servers
pwd
```
o resultado do `pwd`  deverá ser `/tmp/sandbox/guia-config-servers`.

rodar [step1](http://git.ok.org.br/oficial.news/blob/master/server/scripts/step1.sh)
ou seja `sh scripts/step1.sh`. **Atenção**:
* manter terminal em janela grande para não comprometer telas interativas
* usar espaço para selecionar/deselecionar o pt-BR na primeira tela interativa
* posicionar o cursor sobre C.en-UTF8 na segunda tela, relativa ao ambiente shel, que precisa ser ingles para as mensagens de erro serem mais facilmente rastreáveis em guias e fóruns bons.
* sair do shel com `exit`

Ao voltar com `ssh`,
```sh
cd /tmp/sandbox/guia-config-servers
sh scripts/step1_checks.sh | diff dumps/step1.txt -
```
se o diff acima não devolver nada (significa "arquivos identicos") então perfeito.

# step2
* http://git.ok.org.br/oficial.news/blob/master/server/scripts/step2.sh
pode pular se for só teste sem segurança.

# step3
é o mais demorado ... reservar pelo menos 10 minutos e cuidado com o ssh que pode perder conexão.

* http://git.ok.org.br/oficial.news/blob/master/server/scripts/step3.sh

Responder "Y" ou "yes" para tudo que terminar em "space will be used". Responder senha do MySQL duas vezes.

No final conferir com `sh scripts/step3_checks.sh | diff dumps/step3.txt -` para atestar que foi tudo ok.

# step4 - Postfix

... Descartado, estamos usando G Suite sem custo.

