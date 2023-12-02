# Visão de Implantação
## Configuração local
### Nós Físicos:

**Servidor Web:**

- *Hardware*: Servidor dedicado local com CPU multicore, RAM adequada e armazenamento SSD.
Conectividade: Conectado à rede local (LAN).

**Servidor de Aplicação:**

- *Hardware*: Outro servidor local dedicado para executar a lógica de aplicação.
Conectividade: Conectado à LAN.

**Banco de Dados:**

- *Hardware*: Servidor de banco de dados separado.
Conectividade: Conectado à LAN.

**Interconexões:**

- Conexões entre o servidor web, servidor de aplicação e servidor de banco de dados via LAN.

### Mapeamento de Processos nos Nós Físicos:

**Processos:**

- Servidor Web
- Servidor de Aplicação
- Banco de Dados

**Mapeamento:**

- O servidor web interage com o servidor de aplicação, que, por sua vez, interage com o banco de dados.