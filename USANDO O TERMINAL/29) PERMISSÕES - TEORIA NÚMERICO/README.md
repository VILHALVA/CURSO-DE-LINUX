# PERMISSÕES NO LINUX TEORIA MODO NÚMERICO
No Linux, as permissões de arquivos e diretórios também podem ser definidas e visualizadas usando um sistema de notação numérica. O sistema de notação numérica é uma maneira conveniente de representar as permissões usando valores numéricos. Aqui está como funciona:

1. **Permissões Numéricas:**

   As permissões são representadas por números e cada permissão tem um valor numérico associado:

   - Leitura (Read) = 4
   - Escrita (Write) = 2
   - Execução (Execute) = 1

   Você pode somar esses valores para criar um número que represente as permissões. Por exemplo:

   - Leitura + Escrita (rw) = 4 + 2 = 6
   - Leitura + Execução (r-x) = 4 + 1 = 5
   - Leitura + Escrita + Execução (rwx) = 4 + 2 + 1 = 7

2. **Notação de Três Dígitos:**

   Para representar as permissões numéricas de um arquivo ou diretório, você usa uma notação de três dígitos. Cada dígito representa um grupo de permissões: proprietário, grupo e outros (ou usuário, grupo e outros). A ordem é a seguinte: proprietário, grupo, outros.

   Por exemplo, a notação "644" significa:

   - Proprietário tem permissão de leitura e gravação (6).
   - Grupo tem permissão de leitura (4).
   - Outros têm permissão de leitura (4).

3. **Uso do Comando `chmod`:**

   Para aplicar permissões numéricas a um arquivo ou diretório, você pode usar o comando `chmod` seguido do número de permissões e o nome do arquivo ou diretório. Por exemplo:

   - Definir permissões "rw-r--r--" usando notação numérica:

     ```
     chmod 644 arquivo.txt
     ```

   - Definir permissões "rwxr-xr-x" usando notação numérica:

     ```
     chmod 755 diretório
     ```

   Lembre-se de que, ao usar a notação numérica, você está substituindo todas as permissões existentes. Portanto, esteja ciente de como as permissões atuais estão configuradas antes de aplicar as permissões numéricas.

4. **Interpretação das Permissões:**

   - O valor numérico "0" representa nenhuma permissão.
   - O valor numérico "7" representa permissão total (rwx).
   - O valor numérico "5" representa leitura e execução (r-x).
   - O valor numérico "4" representa apenas leitura (r).
   - O valor numérico "3" representa escrita e execução ( -wx).
   - O valor numérico "2" representa apenas escrita (-w).
   - O valor numérico "1" representa apenas execução (--x).

A notação numérica é útil quando você deseja definir permissões de forma rápida e precisa para arquivos ou diretórios. Certifique-se de entender a correspondência entre valores numéricos e permissões para usar esse sistema com eficácia.