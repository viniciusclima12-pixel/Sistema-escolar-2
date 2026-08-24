# Sistema de Gestão Escolar

**Sistema para gerenciar administradores, coordenadores, professores, alunos, cursos e matrículas.**

## 1. Quem utilizará o sistema (usuários)?

R: funcionários

## 2. Quais os tipos de usuários e o que cada tipo consegue fazer?

R:


* **Colaboradores:** Cadastrar alunos, cadastrar cursos, editar dados
dos alunos, editar dados dos cursos, excluir alunos, excluir cursos,
listar alunos, listar cursos, matricular alunos nos cursos e desmatricular alunos dos cursos e atualizar os próprios dados.
* **ADM:** Todas as funcoes acima, mais: cadastrar outros funcionários, listar outros funcionários, editar dados dos outros funcionários e excluir outros funcionários.



## 3. Quais informações iremos armazenar?

R:

* **funcionários:** Nome, e-mail, telefone, senha e cargo, data de nascimento, CPF, telefone, endereço
* **Alunos:** Nome, idade, matrícula, e-mail, telefone, data de nascimento, CPF, telefone, endereço. 
* **Cursos:** Nome, descrição, carga horária.
* **Matrículas:** Quais alunos estão cadastrados em quais cursos.



## 4. Quais regras ou restrições são necessárias?

R: 
* Apenas funcioários adimin podem criar/deletar outros funcionários.
* Funcionários colaboradores não podem editar dados de outros funcionários.
* CPF não pode repetir, email não pode repetir
* Nome, email, cargo, cpf, senha, cargahoraria, matricula são obrigatórios.
* Um aluno não pode ser matriculado duas ou mais vezes em um mesmo curso.
* O sistema deve validar as informações.

## PROBLEMA: 
 * Esses sistema é direcionado a funcionários de escolas
 * Permitir o cadastrar, editar, listar e deletar alunos, cursos, maticulas e funcionários
