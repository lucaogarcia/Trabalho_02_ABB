# Trabalho_02_ABB
UNIVERSIDADE ESTADUAL DE MARINGÁ *![](Aspose.Words.e83deac9-2464-46f3-834b-46cc8acd9d8d.001.png)*Centro de Tecnologia - CTC  

Departamento de Informática - DIN

**9893-32 – ESTRUTURA DE DADOS                 BACHARELADO EM INFORMÁTICA – 2° sem /2021 Prof. Rodrigo Calvo** 

**TRABALHO 2 - VOTAÇÃO** 

**Objetivo:** 

Implementar um sistema de votação usando TAD de árvores binárias de busca (ABB). 

**Descrição:** 

Suponha que todos os brasileiros participam das eleições e que, para votar, uma pessoa precisa ter um número de título de eleitor válido (o número de título pode ser um inteiro simples). Qualquer pessoa pode ser eleita para a função. Nesta votação, uma pessoa pode votar em alguém (ou seja, indicar o nome da pessoa) ou, a qualquer momento, decidir retirar seu voto por qualquer que seja o motivo. Contudo, apenas um voto por pessoa pode estar armazenado no sistema num dado momento. Essas verificações podem ser feitas da seguinte forma:  

- armazenando em uma ABB os números de todos os títulos válidos; 
- armazenando em uma outra ABB os números de todos os títulos que já votaram até o    momento e o nome da pessoa votada associada a cada título. 

**Funcionalidades mínimas esperadas:** 

- Cadastramento de títulos de eleitor: 
  - Cadastrar um título: insere o título na árvore de títulos válidos (se não estiver lá); 
  - Descadastrar um título: retira o título da árvore de títulos válidos (se estiver lá). 
- Votações: 
- Iniciar  nova  votação:  inicializa/esvazia  a  ABB  que  guarda  os  títulos  que  já votaram; 
- Votar: lê o número do título e o voto 
- se o número é válido e se ainda não votou, atualiza a ABB que armazena os títulos de quem já votou; 
- se o número não é válido ou já votou, emite mensagem de erro. 
- Retirar voto: lê o número do título e verifica se já votou 
- se já votou, retira o título e o voto; 
- caso contrário, emite mensagem de erro. 
- Geral 
- Mostrar resultado parcial das eleições (nomes dos votados e número de votos); 
- Mostrar o maior número de título que já votou; 
- Mostrar o menor número de título que já votou; 
- Listar todos os números de títulos que já votaram; 
- Liberar todas as estruturas e encerrar o programa. 

**Considerações**  

1) O trabalho deverá ser feito individualmente ou em dupla; 
1) O programa e do TAD devem fazer o que foi especificado; 
1) Não será permitido trabalhos nos quais haja quaisquer tipos de cópia ou plágio. 
1) O programa deve ser implementado em C e em qualquer ambiente/compilador; 

**Modo de entrega:** Fazer upload no Classroom. A primeira linha do código de cada arquivo, deve conter o nome completo e RA do(s) aluno(s) em comentário.  

**Prazo de entrega**: 27/04/2021 
