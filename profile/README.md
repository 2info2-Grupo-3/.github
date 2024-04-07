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

1. RF001 -> O sistema deve manter Clientes;
2. RF002 -> O sistema deve manter Orçamentos;
3. RF003 -> O sistema deve manter Serviços;
4. RF004 -> O sistema deve manter Peças;
5. RF005 -> O sistema deve manter Entradas;
6. RF006 -> O sistema deve manter Retiradas;
7. RF007 -> O sistema deve mostrar status dos serviços;
8. RF008 -> O sistema deve mostrar conversão de orçamento em serviços;
9. RF009 -> O sistema deve mostrar peças utilizadas no conserto;
10. RF010 -> O Sistema deve identificar os principais clientes;
11. RF011 -> O sistema deve identificar principais serviços realizados;
12. RF012 -> O sistema deve identificar margens de faturamento por serviço
13. RF013 -> O sistema deve identificar tempo para realização de serviços;
14. RF014 -> O sistema deve gerenciar o faturamento;
15. RF015 -> O sistema deve gerenciar as entradas de recursos da empresa;
16. RF016 -> O sistema deve gerenciar as saidas de recursos da empresa;

## Requisitos Não Funcionais:

1. RNF001 -> O sistema deve ser responsivo;
2. RNF002 -> O sistema deve ter um backend feito em Node.js
3. RNF003 -> O sistema deve ter um frontend em Vue.js
4. RNF005 -> O sistema deve utilizar o Postgres como database;

## Modelagem do Banco de Dados

<div align="center">
<img src="profile/modelagem_versao1" alt="modelagem 1" width="50%">
</div>

## Link do Database Neon Postgree:
- Link [https://console.neon.tech/app/projects/summer-tooth-60549787]

## Descrição das Tabelas no Neon Postgree: 

-Tabela Clientes:

<div align="center">
<img src="profile/descricao_clientes.png" alt="descricao clientes" width="100%">
</div>
