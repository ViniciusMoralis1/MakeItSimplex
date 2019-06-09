MakeItSimplex

Repositório para a implementação do algoritmo Simplex e Mochila.

Projeto de Pesquisa Operacional
5º Semestre BCC UNIVEM

O Simplex permite que se encontre valores ideais em situações em que diversos aspectos precisam ser respeitados. Diante de um problema, são estabelecidas inequações que representam restrições para as variáveis. A partir daí, testa-se possibilidades de maneira a otimizar, isto é, maximizar ou minimizar o resultado da forma mais rápida possível.

O algoritmo da mochila consiste em preencher a mochila com objetos diferentes de pesos e valores. O objetivo é que preencha a mochila com o maior valor possível, não ultrapassando o peso máximo.


## Ferramentas

- Javascript
- JQuery
- Bootstrap
- GitHub para hospedagem e versionamento

## Nota de realease a ser publicado

###Simplex

- Algoritmo Simplex para problemas de maximização.
- Algoritmo Simplex para problemas de minimização.
- É exibido o passo a passo das tabelas geradas pelo método Simplex.
- Tabela de Sensibilidade.
- Tabela com os valores Finais.

###Mochila

- Apresentação do valor final da mochila e os atributos dos itens para aquela capacidade.

##Entradas personalizadas para:

###Simplex

- Limite máximo de iterações
- Tipo de Simplex (MAX ou MIN)
- Quantidade de variáveis e restrições

###Mochila
- Capacidade da mochila
- Peso e valor dos itens

##Limitações

###Simplex

- Em cada variável da função objetivo e das restrições deve conter apenas o número, sem a adição do 'x', separando os números por ';' e caso tenha alguma variável nula, é necessário inserir o 0.


###Mochila

- Não utilizar itens com pesos iguais
- Serão permitidos somente valores inteiros


##Datas Importantes

###Simplex

Datas | Eventos
----------- | ------
16/03/19    | Início do Planejamento
16/03/19    | Criação da Estrutura Principal
16/03/19    | Criação do Cabeçalho da Matriz Principal
25/03/19    | Cálculo
25/03/19    | Geração da Matriz Principal
05/04/19    | Criação das Funções de Parada
16/04/19    | Inserindo o Minimizar
16/04/19    | Criação do Layout
16/04/19    | Inserindo a Análise de Sensibilidade
26/04/19    | Criando o passo a passo
02/05/19    | Tabela de Sensibilidade
01/05/19    | Ajustes nos inputs das restrições
15/05/19    | Ajustando tabelas simplex
15/05/19    | Análise de sensibilidade
06/05/19    | Correção de um erro na geração de tabelas
09/06/19    | Atualizando README


###Mochila

Datas | Eventos
---------- | ------
21/05/19   | Início do Planejamento
21/05/19   | Refatorando a tela inicial da aplicação
21/05/19   | Inserindo inputs 
27/05/19   | Finalização do projeto da mochila
01/06/19   | Refatoração do layout da Mochila e index
04/06/19   | Correção de alguns erros no layout
09/06/19   | Atualizando README

##Compatibilidade

Requisitos | Ferramentas
--------- | ------
Navegadores     | Mozilla Firefox, Chrome, Internet Explorer
Sistema Operacional    | Ubuntu, Windows, Mac, RedHat

##Tecnologias

Tecnologias | Ferramentas
--------- | ------
Front-End     | HTML, Javascript, JQuery, BootStrap
Back-End    | Javascript
Editor de Texto  | VSCode
Servidor Web    | https://github.io/

##Atividades Realizadas no Período

###Simplex

Código | Título | Tarefa | Situação | Observação
--------- | ------ | -------| -------| -------
1 | Maximizar | Montar a Tabela Simplex, e possibilitar o usuário a maximizar modelos de simplex com sistemas lineares. | Concluído | Apenas restrições de “<=”
2 | Minimizar | Montar a Tabela Simplex, e possibilitar o usuário a minimizar modelos de simplex com sistemas lineares. | Concluído | Apenas restrições de “<=”
3 | Adição de restrições | Possibilitar o usuário a adicionar inputs para maiores números de restrições. | Concluído |
4 | Tabela Final | Possibilitar o usuário de ver apenas o resultado final sem a necessidade de um passo a passo | Concluído |
5 | Demonstrar passo a passo | Demonstrar ao usuário as alterações na tabela causada pelas iterações do método simplex. | Concluído|
6  | Tabela de sensibilidade | Demonstrar ao usuário a tabela de sensibilidade. |Concluído|

###Mochila

Código | Título | Tarefa | Situação | Observação
--------- | ------ | -------| -------| -------
1 | Teste de maior valor | Testar todos os itens possíveis na capacidade desejada e mostrar os que ficarão na mochila | Concluído |
2 | Solução do problema | Mostrar ao usuário os itens selecionados pelo algoritmo como qualificados tal qual seus atributos (valor e peso) | Concluído |
