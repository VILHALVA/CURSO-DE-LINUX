# PERMISSÕES NO LINUX (TEORIA)
As permissões no Linux são uma parte fundamental da segurança e gerenciamento de arquivos no sistema operacional. Elas determinam quem pode acessar, modificar ou executar arquivos e diretórios no sistema. Aqui está uma visão geral das permissões no Linux:

1. **Tipos de Permissões:**

   Existem três tipos principais de permissões no Linux:

   - **Permissões de Leitura (Read - r):** Permite visualizar o conteúdo de um arquivo ou listar o conteúdo de um diretório.
   
   - **Permissões de Gravação (Write - w):** Permite modificar o conteúdo de um arquivo ou criar, modificar e excluir arquivos em um diretório.
   
   - **Permissões de Execução (Execute - x):** Permite executar um arquivo ou acessar um diretório e listar seu conteúdo.

2. **Proprietário, Grupo e Outros:**

   No Linux, as permissões são definidas para três grupos diferentes:

   - **Proprietário (Owner):** O usuário que possui o arquivo ou diretório.
   
   - **Grupo (Group):** Um grupo de usuários com permissões comuns, definido pelo sistema ou pelo administrador.
   
   - **Outros (Others):** Todos os outros usuários que não são o proprietário e não estão no grupo especificado.

3. **Notação de Permissões:**

   As permissões são representadas em uma notação de três caracteres (rwx) para cada um dos três grupos (proprietário, grupo e outros). Por exemplo, `rw-r--r--` indica que o proprietário tem permissão de leitura e gravação, enquanto o grupo e outros têm apenas permissão de leitura.

4. **Comandos para Definir Permissões:**

   - `chmod`: O comando `chmod` é usado para alterar as permissões de um arquivo ou diretório. Você pode especificar as permissões em formato octal (exemplo: `chmod 644 arquivo.txt`) ou usando a notação de três caracteres (exemplo: `chmod u+rwx arquivo.txt`).

5. **Permissões Especiais:**

   Além das permissões padrão, existem permissões especiais, como o bit SUID, o bit SGID e o bit sticky. Esses bits permitem que os executáveis sejam executados com os privilégios do proprietário ou do grupo, ou garantem que os arquivos só possam ser modificados pelo proprietário.

6. **Diretórios e Permissões:**

   As permissões em diretórios têm algumas peculiaridades. A permissão de leitura em um diretório permite listar seu conteúdo, a permissão de gravação permite criar, modificar ou excluir arquivos dentro do diretório, e a permissão de execução permite acessar o diretório e seus arquivos.

7. **Uso Avançado de Permissões:**

   Além das permissões básicas, o Linux também suporta controle de acesso obrigatório (MAC) e controle de acesso baseado em atributos (ACLs) para oferecer um controle mais granular sobre as permissões de arquivo.

8. **Verificação de Permissões:**

   Você pode verificar as permissões de um arquivo ou diretório usando o comando `ls -l`. Ele exibirá informações detalhadas, incluindo o proprietário, o grupo e as permissões.

Entender e gerenciar permissões no Linux é essencial para manter a segurança do sistema e garantir o acesso adequado aos arquivos e diretórios. Certifique-se de usar permissões com responsabilidade e atribuir as permissões apropriadas aos arquivos e diretórios de acordo com as necessidades do sistema e dos usuários.