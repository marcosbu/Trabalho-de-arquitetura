# Diagrama de Caso de Uso
![Caso de Uso - principal](./img/diagramacasodeuso.png)

- **Seleção de Casos de Uso:** Liste os Diagramas de Casos de Uso que são considerados arquiteturalmente significativos para o sistema (No mínimo 5).  
![Caso de Uso - Cadastrar-se](./img/Cadastrar-se.png)
![Caso de Uso - Fazer Login](./img/FazerLogin.png)
![Caso de Uso - Acessar Curso](./img/acessarCurso.png)
![Caso de Uso - Assistir Aula](./img/AssistirAula.png)
![Caso de Uso - Comprar Curso](./img/ComprarCurso.png)
- **Critérios de Seleção:** Explique os critérios que levaram à seleção desses casos de uso.
	- **Importância: Os casos de usos listados tem uma grande importância na estrutura para o uso devido site.**
	- **Complexidade: Cada caso de uso tem sua complexidade dentro do diagrama, fazendo com que cada tenha uma função a ser seguida dentro do diagrama.**

- **Descrição de Casos de Uso:** Forneça uma breve descrição de cada caso de uso, destacando sua importância arquitetural.
	- **Cadastra-se:** Permite que o aluno se cadastre para receber informações do site, e novos cursos cadastrados, Além de poder acessar os cursos, avaliações e  valores de cada curso.<br>
	- **Fazer Login:** Permite que os alunos loguem no site para se tornar aluno, e ter acesso a para a compra dos cursos, visualização de aulas e avalições. <br>
	- **Acessar Curso:** Permite que o aluno possa acessar os cursos para assistir aula, fazer avaliações e comprar o curso.<br>
	- **Assistir Aula:** Permite que o aluno possa assistir a vídeo aula, que será o conteúdo do capitulo do curso.<br>
	- **Comprar Curso:** Permite que o aluno compre cursos, a forma de pagamento é boletos, pix, cartões de créditos de todas as bandeiras.<br>

- **Pontos Complexos da Arquitetura:** Identifique quais pontos complexos e específicos da arquitetura são enfatizados ou ilustrados por cada caso de uso.

# Cenários
- **Crie o Cenário:** Crie o cenário completo de ao menos 5 casos de uso.

|Nome do Caso de Uso | Cadastrar-se |
| -------------------| ------------------ |
|Finalidade/Objetivo |Permite que o aluno se cadastre para receber informações do site, e novos cursos cadastrados, Além de poder acessar os cursos, avaliações e  valores de cada curso.|
|Ator Principal    |    Aluno     |
|Pré-Condições     |   Os dados do cliente devem ser inseridos confome solicitado  |
|Fluxo Principal   | 1. Aluno escolhe a opção de se cadastrar;<br>2. Aluno confirma o cadastro no email; [A1].<br>3. Caso de Uso encerrado;|
|Fluxo Alternativo | A1. Aluno deseja cancelar operação;<br> - Aluno não confirma o cadastro;<br> - O sistema volta para o passo 1 Fluxo principal;|


|Nome do Caso de Uso | Fazer Login |
| -------------------| ------------------ |
|Finalidade/Objetivo |Permite que os alunos loguem no site para se tornar aluno, e ter acesso a para a compra dos cursos, visualização de aulas e avaliações.|
|Ator Principal    |    Aluno     |
|Pré-Condições     |   O aluno deve está cadastrado no site  |
|Fluxo Principal   | 1. Aluno escolhe a opção de logar;<br>2.Preenche formulário com os dados necessários; [A1], [A2].<br>3. Confirma os dados; [A1], [E1].<br>4. Caso de Uso encerrado;|
|Fluxo Alternativo | A1. Deseja cancelar operação;<br> - Aluno não confirma os dados para login;<br> - Aluno volta para a página inicial;<br> A2. Deseja alterar algum dado do formulário;<br> - Aluno altera dados de algum campo para login;<br> - O sistema retorna no passo 2 Fluxo principal; |
|Fluxo de Exceção | E1. Os dados estão incorretos;<br> - Sistema mostra mensagem de algum campo incorreto;<br> - O sistema volta para o passo 2 Fluxo Principal;|

|Nome do Caso de Uso | Acessar Curso |
| -------------------| ------------------ |
|Finalidade/Objetivo |Permite que o aluno possa acessar os cursos para assistir aula, fazer avaliações e comprar o curso.|
|Ator Principal    |    Aluno     |
|Pré-Condições     |   O aluno deve está logado no site  |
|Fluxo Principal   | 1.Aluno clica na aba “Cursos”; <br> 2. Aluno seleciona qual curso deseja acessar; [A1].<br> 3. Caso de Uso encerrado;|
|Fluxo Alternativo | A1. Deseja cancelar operação;<br>- Aluno volta para a página inicial; |

|Nome do Caso de Uso | Assistir Aulas |
| -------------------| ------------------ |
|Finalidade/Objetivo |Permite que o aluno possa assistir a vídeo aula, que será o conteúdo do capitulo do curso.|
|Ator Principal    |    Aluno     |
|Pré-Condições     |   O aluno deve está logado no site  |
|Fluxo Principal   |1. Aluno escolhe a opção de curso; [A2], [A3].<br> 2. Aluno seleciona o capítulo; [A1].<br>3. Aluno reproduz vídeo; [A4].<br>4. Caso de Uso encerrado;|
|Fluxo Alternativo | A1. Aluno deseja fazer exercícios do capítulo;<br>- Aluno clica “Responder exercícios”;<br> - Aluno seleciona alternativa;<br> - Aluno confirma a resposta;<br> - O sistema volta para o passo 2 Fluxo principal;<br>A2. Aluno deseja realizar avaliação do Curso;<br> - Aluno clica “Fazer Avaliação”;<br> - Aluno responde as questões da avaliação;<br>- Aluno confirma as respostas;<br> - O sistema volta para o passo 1 Fluxo principal; <br>A3. Aluno deseja comentar Curso;<br>- Aluno clica “comentar curso”;<br>- Aluno preenche um pequeno texto;<br>- Aluno confirma o comentário;<br>- O sistema volta para o passo 1 Fluxo principal;<br>A4. Aluno deseja cancelar operação;<br>- Aluno volta ao painel do curso;<br>- O sistema volta para passo Fluxo 1 principal; |

|Nome do Caso de Uso | Comprar Curso |
| -------------------| ------------------ |
|Finalidade/Objetivo |Permite que o aluno compre cursos, a forma de pagamento é boletos, pix, cartões de créditos de todas as bandeiras.|
|Ator Principal    |    Aluno     |
|Pré-Condições     |   O aluno deve está logado no site  |
|Fluxo Principal   | 1. Aluno clica “comprar curso”;<br>2. Aluno seleciona os cursos que deseja comprar;[A1].<br>3. Aluno escolhe a forma de pagamento. [A1], [A2].<br>4. Aluno confirma os cursos selecionados; [A1].<br>5. Aluno preenche o formulário com seus dados; [A1].<br>6. Aluno confirma os dados; [A1], [E1].<br>7. Caso de Uso encerrado;|
|Fluxo Alternativo | A1. Deseja cancelar a compra;<br> - O aluno fecha a operação de compra;<br> - O sistema volta para o passo 1 Fluxo Principal;<br>A2. Deseja remover ou adicionar algum curso do carrinho de compras;<br> - O aluno remove ou adiciona os itens de compra;<br>- O sistema volta para o passo 2 Fluxo principal;|
|Fluxo de Exceção | E1. Os dados informados do cartão estão incorretos;<br>- Sistema mostra mensagem de erro de validação do cartão;<br> - Sistema volta para o passo 5 Fluxo Principal;|
