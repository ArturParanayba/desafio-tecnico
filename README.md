# Desafio Técnico - Backend
Desafio técnico para entrada no time de desenvolvimento

Você deverá criar uma aplicação que tem como principal objetivo cadastrar professores, materias e aulas.

Este projeto deverá utilizar NodeJS e NestJs como frameworks backend, TypeORM para comunicação com o banco e deverá ser escrito em typescript.

Sinta-se livre para utilizar qualquer banco de dados relacional. Recomendo que use o Postgres.

Tanto o banco quanto a aplicação, deverão estar dockerizados e rodando containerizados.

A aplicação deverá ter o CRUD completo dos 3 objetivos principais citados e também deverá contar com autenticação completa (Login com senha retornando token para autenticação das rotas)

Faça um clone do repositorio na sua máquina e monte a aplicação.

Suba o código feito em um novo reposítorio no seu github e envie o link do repo  ao término do desafio.

Você tem 7 dias para entregar o desafio!


Detalhamento:

Professor: 
 Deverá ter nome e a materia na qual ele dá aula
 
 Matéria:
 Nome e conteúdo (string)

Aula:

Professor que ministrará a aula, materia e dia/horário da aula

 OBS: Não se preocupe com questão de agendamento de aula, ou de choque de horário. O Campo de horario poderá ser uma string. 
 
O sistema deverá fornecer os dados das aulas por diam por semana e por mes. 
