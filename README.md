# Aplicativo lista de tarefas (*em desenvolvimento*)

Aplicativo TO-DO list, com integração com Firebase realtime. Para aplicar os conhecimentos  adquiridos em Android.

### Utilizados:
KOTLIN &#8594; Linguagem de programação\
COMPOSE &#8594; Desenvolvimento das telas\
MVVM &#8594; Arquitetura do aplicativo\
ROOM &#8594; Banco de dados local\
HILT &#8594; Injeção de dependência\


Tabelas do banco de dados ROOM

| **TABELA USUÁRIO**	(user)																			|
|:-----------------------------------------------------------------------------------------------------:|
| ID : long (pk)																										|
| NAME : string																										|
| EMAIL : string																										|
| PASSWORD	: string																								|
| 																								                            |

| TABELA TAREFAS (task)																			        |
|:-----------------------------------------------------------------------------------------------------:|
| ID : long (pk)																										|
| NAME : string																										|
| CATEGORY : long (fk)																							|
| TASKPARENT	: long																							|
| CREATEDATE	: long																							|
| DUEDATE	: long																								|
| DONE	: long																										|

| TABELA CATEGORIAS (categories)																	|
|:----------------------------------------------------------------------------------------------------:|
| ID : long (pk)																										|
| NAME : string																										|
| CATEGORY : long																								|