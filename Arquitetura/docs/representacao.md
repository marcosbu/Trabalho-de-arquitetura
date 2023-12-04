# Representação Arquitetural

O modelo de arquitetura adotado foi o de Microsserviços, ele divide o sistema em pequenos serviços independentes que se comunicam entre si. Tem sua representação garantida nos componentes do projeto que são independentes, porém se comunicam entre si.

### Visão de casos de uso:
- Explicação: Com a visão de casos de uso foi possível capturar, clarificar e comunicar os requisitos funcionais do sistema do ponto de vista dos usuários finais.
- Elementos de Modelo: Diagramas de Casos de Uso.

### Visão lógica:
- Na visão lógica está contido o elemento de microsserviços Individuais: Cada funcionalidade específica do projeto é encapsulada em um subsistema independente. Por exemplo, um subsistema para gerenciamento de usuários, outro para processamento de pagamentos, etc;  
- Comunicação Segura é mais um elemento que contém a visão lógica, pois há o uso de HTTPS, autenticação de serviços e gerenciamento de chaves para garantir a segurança nas comunicações.
Elementos de Modelo: Diagramas de sequência e diagrama de classes

### Visão de processos:
- Com a visão de processos foi possivel ter uma representação abstrata do fluxo de trabalho ou atividades que ocorrem no sistema. Foi possível descrever como diferentes partes do sistema interagem para realizar tarefas específicas.

- Elementos de Modelo: Diagrama de atividades.

### Visão de implementação
- A visão de implementação trouxe a forma de como o projeto é traduzido em código real, considerando detalhes de implementação, linguagens de programação, frameworks e bibliotecas que foram utilizados.
Elementos de Modelo: Diagramas de pacotes.
### Visão de implantação:
- A visão de implantação fez com oque o sistema fosse preparado e lançado para uso em um ambiente operacional. Envolveu toda a configuração de ambientes e a transferência de código para servidores de produção.

- Elementos de Modelo: Diagramas implantação.