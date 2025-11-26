**descrição do projeto, funcionalidades, etc..**

<h1>Task Flow</h1>

Task Flow é um projeto de gerenciamento de tarefas fullstack, com objetivo de que o usuário administrador consiga fazer o CRUD completo de maneira intuitiva permitindo criar, editar, listar e deletar tarefas por categoria de prioridade.


**A1 = foto do login e da parte de criação de tarefas**

<h2>Funcionalidades</h2>

- Criar tarefas com título e prioridade/categorias (High, Medium, Low)
- Editar tarefas que foram criadas
- Listar tarefas por título
- Deletar tarefas
- Autenticação com JWT

**A2 = foto do CRUD completo pelo swagger**

<h2>Informações necessárias</h2>

Assim que logar no usuário admin e executar as tarefas, pode acabar deixando passar uma hora e quando tentar voltar para acrescentar uma nova tarefa na lista, muito provavelmente a listagem não irá aparecer porque o token vai ser expirado. Para resolver essa questão você só irá precisar apagar o token e logar novamente usando este comando no console do navegador: **localStorage.removeItem("token")**

**A3 = foto disso**

E qualquer outra questão se não conseguir mais alterar na execussão, apenas dando um reload na página que tudo voltará a funcionar como antes.

-----------------------------------------------------------------------

**As fotos estão em outro documento! Estarei enviando separadamente.**
