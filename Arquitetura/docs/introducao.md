# Introdução
- Este documento oferece uma visão geral arquitetural abrangente do sistema, usando diversas visões arquiteturais para representar diferentes aspectos do sistema. O objetivo deste documento é capturar e comunicar as decisões arquiteturais significativas que foram tomadas em relação ao sistema".

#### Finalidade do Documento:
- O documento foi criado com intuito do acompanhamento do projeto Educa P2 da equipe DevTrom.  
- Apresentar o planejamento e a forma que foi feita o projeto, incluindo tudo sobre os sistema.  
 
#### Escopo do Documento:
- Está incluido no documento informações importantes sobre o sistema, como os métodos adotados para a sua realização, questões de seguranças tabém foram abordadas no presente documento. De modo geral foi visto de tudo sobre o sistema, desde informações de cronogramas e atas de reunião até questões de riscos corridos com a realização do projeto.  
- Não está incluido no documento informações cruciáis para o seu funcionamento, como questões de alta segurança e afins. Dados de atualizações futuras não foram exposto no documento, uma vez que esse documento está sendo feito para fins estudantes e não temos a certeza de continuar com o projeto.  

#### Definições, Acrônimos e Abreviações:
- Desenvolvedor back-and - desenvolverdor que busca desenvolver a parte lógica do sistema "processo atrás das cortinas";
- Desenvolvedor front-and - desenvolverdor que busca desenvolver a visual do sistema, parte em que o usuário interage com o sistema.;
- APIs - Interface de Programação de Aplicação;
- TCP - Protocólo de controle de transmissão/protocólo da internet;
- HTTP - Protocólo de Transferência de Hipertexto.

#### Referências:  
- **[Referências](referencias.md).**

#### Visão Geral do Documento:
- Resumo das seções ou capítulos.

- Introdução: Parte introdutória do documento.
- Identificação do projeto: Descrição de algumas informações do projeto, como brainstormings, e listagem de requisitos funcionais e não funcionais.
- Representação Arquitetural: Apresentação das visões arquiteturais.
- Guia de Estilo: Detalhes do design do projeto, como Logo, tipografia, identidade visual, etc.
- Padrões e Práticas Recomendadas: Padrões e práticas recomendadas para garantir a qualidade da arquitetura.
- Comunicação e Integração:mecanismos de comunicação entre os componentes e APIs.
- Segurança: Estratégias de segurança adotadas.
- Desempenho e Escalabilidade: Detalhes que garantem o desempenho e a escalabilidade. 
- Realizações de Casos de Uso: Representações de casos de uso do sistema.
- Plano de Risco: Avaliação dos possivéis riscos para o sistema.
- Estimativas de Custo: Avaliação de estimativas de custo para a criação do sistema. 
- Prototipação: Prototipos das telas do sistema.
- Metodologia: Descreve a metodologia utilizada para o desenvolvimento do sistema.
- Visão Geral: Apresenta uma visão resumida do sistema.
- Visão Lógica: Detalhes da lógica do sistema.
- Visão de Implantação: Descreve a distribuição física do sistema.
- Visão de Dados: Aborda a estrutura e gerenciamneto do banco de dados.
- Qualidade: Descreve a qualidade do sistema.
- Anexos: Anexos de reuniões e cronogramas.
- Referências: Referências importantes para o desenvolvimento desse projeto.

#### Público-Alvo:
**Quem deve usar o documento:**  
- Este documento é voltado para os programadores, arquiteto de software, gerentes de qualidade e os outros envolvidos nesse projeto.

**Identificação do público específico**
- O público que pode ser afetado por esse projeto são estudantes, pessoas buscando conhecimento.

#### Uso do Documento:
- O documento deve ser utilizado para expor o presente projeto de uma forma geral, abortando vários aspectos sobre o sistema.  
- Os propósitos dependem do ponto de vista de cada expectador, para a equipe desenvolvedora o documento serve para guardar todas as informações especificações e para ajudar a densenvolver o projeto. Já para o requisitante o documento serve para tirar todas as dúvidas sobre o projeto solicitado e ter uma  base de como feito. Expectadores leigos sobre o projeto tem acesso a uma gama de informações relevantes sobre o sistema, facilitando assim o entendimento do mesmo.
#### Resumo da Arquitetura:
- A arquitetura geral do projeto foi embasada no método de microserviços, onde o sistema é dividido em microserviços independentes que se comunicam entre si.
