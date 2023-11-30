# Visão Lógica
**Dentro do nosso projeto indentifica-se 4 subsistemas indispensaveis, são eles:**  
- Subsistema de Autenticação e Gerenciamento de Usuários;  
- Subsistema de Conteúdo;  
- Subsistema de Interação;  
- Subsistema de Avaliação e Progresso.

**No subsistema de *Autenticação e Gerenciamento de Usuários* temos alguns pacotes e classes significativas**
Pacotes:
- Autenticacao: Lidar com autenticação de usuários.
- GerenciamentoUsuario: Gerenciamento de perfis e informações do usuário.
Classes Significativas:
- GerenciadorAutenticacao: Responsável pela autenticação.
- GerenciadorUsuario: Gerencia informações do usuário.

**No subsistema de *Conteúdo* temos alguns pacotes e classes significativas:**  
Pacotes:
- Cursos: Lida com cursos, aulas e conteúdo educacional;    
- Recursos: Gerencia materiais de aprendizagem.  
Classes Significativas:
- Curso: Representa um curso com informações e aulas associadas;    
- Aula: Descreve uma aula específica dentro de um curso;  
- Recurso: Modelo para materiais de aprendizagem.  

**No subsistema de *Interação* temos alguns pacotes e classes significativas:**  
Pacotes:
- Foruns: Gerencia discussões e fóruns;  
- Menssagens: Suporte a mensagens entre usuários.  
Classes Significativas:
- PostagemForum: Representa uma postagem em um fórum;  
- Menssagem: Modelo para mensagens entre usuários.  

**No subsistema de *Avaliação e progresso* temos alguns pacotes e classes significativas:**
Pacotes:
- GerenciamentoAvaliacao: Lidar com avaliações e testes;  
- GerenciamentoProgresso: Monitoramento do progresso do aluno.  
Classes Significativas:
- Avaliacao: Modelo para avaliações e testes;  
- Progresso: Acompanha o progresso do aluno.  


**Relacionamentos, Operações e Atributos Significativos:**  

Relacionamentos:
- *Curso* pode conter várias *Aulas*;  
- *Usuario* pode estar associado a múltiplos *Cursos* e *Foruns*;  
- *Avaliacao* está associado a um *Curso* específico.  
  
Operações Significativas:
- *GerenciamentoAutenticacao* realiza operações de autenticação, como login e logout;  
- *Curso* pode ter operações para adicionar/remover Aulas;  
- *Avaliacao* inclui operações para avaliar o desempenho do aluno.  
  
Atributos Importantes:
- *Usuario* possui atributos como nome, e-mail e nível de acesso;  
- *Curso* possui atributos como título, descrição e instrutor;  
- *Aula* contém atributos como título, conteúdo e data de criação.
















- [Esta seção descreve as partes significativas do ponto de vista da arquitetura do modelo de design, como sua divisão em subsistemas e pacotes. Além disso, para cada pacote significativo, ela mostra sua divisão em classes e  utilitários declasse. Apresente as classes significativas do ponto de vista da arquitetura e descreva suas responsabilidades, bem como alguns relacionamentos, operações e atributos de grande importância.]
