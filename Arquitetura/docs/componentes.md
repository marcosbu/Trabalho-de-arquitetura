# Componentes
**Temos alguns componentes em nosso sistema, tais como:**  
- Módulo de Autenticação  
- Módulo de Gerenciamento de Usuários  
- Módulo de Banco de Dados    
- Módulo de Processamento de Pagamentos  
- Módulo de Segurança  
- Módulo de Notificações  
  
A comunição entre eles é garantida através de chamadas diretas, Os componentes se comunicam diretamente uns com os outros chamando funções ou métodos expostos pelas interfaces dos outros componentes.

# Protocolos e APIs

Os protocólos que pretendemos usar são o **HTTP e TCP/IP**, pois:  
- O TCP/IP fornece uma base sólida para a comunicação em redes, garantindo a entrega ordenada e confiável de dados. Já o HTTP, construído sobre o TCP, herda essas propriedades, garantindo uma comunicação eficiente e robusta. Utilizar o TCP/IP como base para o HTTP permite o compartilhamento eficiente de recursos web, como documentos HTML, imagens, folhas de estilo CSS, scripts JavaScript, etc.  
  
A API que pretendemos usar é a **API RESTful**, pois:
- É fácil de entender e usar, pois ela segui princípios simples e padrões da web, tornando-a intuitiva para os desenvolvedores.  
- Ela é projetada para ser escalável, suportando um grande número de usuários e operações. Isso envolve a eficiente manipulação de solicitações e respostas.    