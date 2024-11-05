# Aplicativo lista de tarefas (*em desenvolvimento*)

Aplicativo TO-DO list, com integração com Firebase realtime. Para aplicar os conhecimentos  adquiridos em Android.

### Utilizados:
KOTLIN &#8594; Linguagem de programação\
COMPOSE &#8594; Desenvolvimento das telas\
MVVM &#8594; Arquitetura do aplicativo\
ROOM &#8594; Banco de dados local\
HILT &#8594; Injeção de dependência


Tabelas do banco de dados ROOM

| **TABELA USUÁRIO**  (user)																			|  TABELA TAREFAS (task)																			    | TABELA CATEGORIAS (categories)																	|
|:---------------------------------------------------------------:|:---------------------------------------------------------------:|:---------------------------------------------------------------:|
| ID : long (pk)																									| ID : long (pk)																									| ID : long (pk)																									|
| NAME : string																										| NAME : string																										| CATEGORY : string																								|
| EMAIL : string																									| CATEGORY : long (fk categories)																	|                                                                 |
| PASSWORD	: string                                              | USERID : long (fk user)                                         |                                                                 |
|                   																							| TASKPARENT	: long																							|
| 																								                | CREATEDATE	: long																							|
|                                                                 | DUEDATE	: long	  																						  |
|                                                                 | DONE	: long																										|
