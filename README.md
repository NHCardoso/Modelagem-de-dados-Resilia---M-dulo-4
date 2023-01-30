<h1 align="center"> Modelagem de 🎲s para Sistema de Acompanhamento Resilia </h1>

![Screenshot](https://github.com/NHCardoso/Modelagem-de-dados-Resilia---M-dulo-4/blob/main/Modelagem%20Resilia.png?raw=true)

Projeto individual do Módulo 4 do curso de Devolvedor Web FullStack do projeto Programadores Carioca - SENAC RJ/Resilia.

### 👩‍💻descriçao

A proposta desse projeto é modelar um 🪑🎲(banco de dados) para ser implementado ao novo sistema de acompanhamento da empresa Resília e responder as seguintes queguntas:

### ⇨ Existem outras entidades além dessas três?
Sim, foi preciso criar mais quatro entidades além das Três pré definidas(cursos, turmas e alunos):

 <strong>FACILITADOR HARDSKILLS</strong>, <strong>FACILITADOR SOFTSKILLS</strong>, <strong>MONITOR</strong> e <strong>MATRICULA</strong>

### ⇨ Quais são os principais campos e tipos?
Os principais campos são os ID de cada entidade, que são encontrados como PK(chaves primárias) no tipo INT.
### ⇨ Como essas entidades estão relacionadas?

<p> FACILITADOR HARDSKILLS <strong> 1:n </strong> TURMAS</p>
<p> FACILITADOR SOFTSKILLS <strong>1:n</strong> TURMAS</p>
<p> MONITOR <strong>1:n</strong> TURMAS</p>
<p> TURMAS <strong>1:n</strong>ALUNOS</p>
<p> CURSOS <strong>1:n</strong> TURMAS</p>
<p> TURMAS <strong>1:n</strong>MATRICULA </p>
<p> ALUNOS <strong>1:1</strong> MATRICULA</p>
<p> CURSOS <strong>1:1</strong> MATRICULA</p>
