# Documentação do Projeto - Elvis Tech

O Sr. Elvis fez um curso de manutenção de celulares e smartphones e decidiu abrir um negócio,
onde ele é responsável pelos consertos e sua esposa Joan os atendimentos aos clientes. 

Com sua visão empreendedora, ele sentiu a necessidade de um sistema que auxilie sua esposa nas tarefas de
gestão da empresa. Para isso, ele deseja um sistema que gerencie os clientes, orçamentos, serviços
de manutenção, peças, e entrada/retirada dos equipamentos. 

Aproveitando o mercado e clientela eles também vendem as peças usadas no conserto, também capinhas e películas para os celulares e
smartphones. 

Sendo um negócio pequeno, é muito importante que ele consiga ter relatórios que lhe
ajudem na gestão da empresa, como dos status dos serviços, conversão de orçamento em serviços,
estoque de peças utilizadas no conserto. 

Também desejam que de forma inteligente o sistema ajude a identificar os principais clientes, principais serviços realizados e margens de faturamento por
serviço, e tempo para realização de serviço. 

O sistema também deve incluir gerenciamento de faturamento, ou seja, entradas e saídas de recursos financeiros no caixa da empresa. 

Assim, vão poder ter o controle das movimentações financeiras de entrada em função dos serviços, bem como
as peças usadas e acessórios vendidos e também os pagamentos realizados aos fornecedores das
peças e acessórios.

### Requisitos Funcionais e Regras de Negócio:

* RF001 -> O sistema deve manter Clientes;
* RN001 -> Dados do cliente (nome, CPF, endereço, telefone, Data de nascimento);
<hr>

* RF002 -> O sistema deve manter Orçamentos;
* RN002 -> Dados do orçamento (cliente, peças, quantidade de cada peça, serviços, valor total);
<hr>

* RF003 -> O sistema deve manter Serviços;
* RN003 -> Dados do Serviço (Nome, descrição, valor, tempo médio);
<hr>

* RF004 -> O sistema deve manter Peças;
* RN004 -> Dados da peça(Nome, quantidade, valor);
<hr>

* RF005 -> O sistema deve manter Entradas;
* RN005 -> Dados da entrada (código da peça, data de entrada, quantidade de peças);
<hr>

* RF006 -> O sistema deve manter Retiradas;
* RN006 -> Dados da retirada(código da peça, data de retirada, quantidade de peças);
<hr>

* RF007 -> O sistema deve mostrar status dos serviços;
<hr>

* RF008 -> O sistema deve mostrar conversão de orçamento em serviços;
<hr>

* RF009 -> O sistema deve mostrar peças utilizadas no conserto;
<hr>

* RF010 -> O Sistema deve identificar os principais clientes;
<hr>

* RF011 -> O sistema deve identificar principais serviços realizados;
<hr>

* RF012 -> O sistema deve identificar margens de faturamento por serviço
<hr>

* RF013 -> O sistema deve identificar tempo para realização de serviços;
<hr>

* RF014 -> O sistema deve gerenciar o faturamento;
* RN007 -> Dados do faturamento (gastos, pagamentos, total faturado);
<hr>

* RF015 -> O sistema deve gerenciar as entradas de recursos da empresa;
<hr>

* RF016 -> O sistema deve gerenciar as saidas de recursos da empresa;

## Requisitos Não Funcionais:

* RNF001 -> O sistema deve ser responsivo;
<hr>

* RNF002 -> O sistema deve ter um backend feito em Python Django;
<hr>

* RNF003 -> O sistema deve ter um frontend em Vue.js;
<hr>

* RNF005 -> O sistema deve utilizar o Postgres como database;

## Modelagem do Banco de Dados

