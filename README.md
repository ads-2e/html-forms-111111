# LMS - Learning Management System - Frontend

Frontend da aplicação padrão do LMS da Faculdade Impacta

## Sobre

Esse repositório possui apenas o frontend da aplicação LMS da Faculdade Impacta de Tecnologia. Esse site estático é utilizado nas aulas da primeira parte da disciplina de Tecnologias Web dos cursos de tecnologia da faculdade.

## Atividade contínua 1

Para a atividade contínua 1, existem arquivos html com formulários para serem construídos. 

Os itens abaixo serão avaliados. Existem testes automatizados que são executados a cada push no repositório do Github. O resultado da execução pode ser visto na aba actions, clicando no workflow gerado pelo último commit. É possível ver a especificação dos testes que falharam em 'autograding'.

Os testes estão dividos por arquivos:

### contato.html

Neste arquivo será montado um formulário de contato com campos para nome completo, email, assunto, mensagem e onde conheceu. Verifique o tipo de campo exigido, o id e name utilizado para o campo e não deixe a sintaxe html incorreta.

- contato.html tem sintaxe html correta
- [contato.html] Campo nome-completo é do tipo text, tem comprimento máximo 120 e é obrigatório
- [contato.html] campo email é do tipo "email" e é obrigatório
- [contato.html] campo assunto é um select box e é obrigatório
- [contato.html] Campo mensagem é obrigatório, tem comprimento máximo 500 e é um textarea
- [contato.html] Campo conheceu é um select box
- [contato.html] Há um button associado ao form contato
- [contato.html] O form contato tem action agradecimento.html

### entrar.html

Neste arquivo será montado um formulário de acesso com campos para nome de usuário, senha e uma check para marcar que deseja salvar as informações de acesso. Verifique o tipo de campo exigido, o id e name utilizado para o campo e não deixe a sintaxe html incorreta.

- entrar.html tem sintaxe html correta
- [entrar.html] O form entrar tem action index.html
- [entrar.html] Há um button associado ao form entrar
- [entrar.html] Campo usuario tem comprimento máximo 50 e é obrigatório
- [entrar.html] Campo senha tem comprimento máximo 15, é obrigatório e é do tipo password
- [entrar.html] Campo lembrar é um checkbox

### inscrever.html

Neste arquivo será montado um formulário de inscrição com campos para nome de usuário, nome completo email e celular. Verifique o tipo de campo exigido, o id e name utilizado para o campo e não deixe a sintaxe html incorreta.

- inscrever.html tem sintaxe html correta
- [inscrever.html] Campo usuário é obrigatório e tem comprimento máximo 50
- [inscrever.html] Campo nome é obrigatório e tem comprimento máximo 120
- [inscrever.html] Campo email é obrigatório e tem tipo "email"
- [inscrever.html] Campo celular é do tipo "text"
- [inscrever.html] O form inscrever tem action index.html
- [inscrever.html] Há um button associado ao form inscrever

### recuperar.html

Neste arquivo será montado um formulário de definição de senha com campos para definir a nova senha. Verifique o tipo de campo exigido, o id e name utilizado para o campo e não deixe a sintaxe html incorreta.

- recuperar.html tem sintaxe html correta
- [recuperar.html] O form recuperar tem action index.html
- [recuperar.html] Há um button associado ao form recuperar

### esqueci.html

Neste arquivo será montado um formulário de recuperação de senha com campo para email. Verifique o tipo de campo exigido, o id e name utilizado para o campo e não deixe a sintaxe html incorreta.

- esqueci.html tem sintaxe html correta
