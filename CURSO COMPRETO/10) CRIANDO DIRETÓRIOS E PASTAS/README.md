# CRIANDO DIRETÓRIOS/PASTAS NO LINUX (COMANDO MKDIR)
O comando `mkdir` é usado para criar diretórios (também conhecidos como pastas) no Linux. Vamos explorar várias maneiras de usar o `mkdir` para criar diretórios:

**Comando `mkdir` (Make Directory):**

**1. Criar um Diretório Simples:**

   - Para criar um diretório simples, basta usar o comando `mkdir` seguido do nome do diretório que você deseja criar. Por exemplo, para criar um diretório chamado "meudiretorio," use:
   
   ```
   mkdir meudiretorio
   ```

   - Isso criará um diretório com o nome especificado no diretório atual.

**2. Criar Diretórios Aninhados:**

   - Você pode criar diretórios aninhados (subdiretórios) fornecendo o caminho completo do diretório que deseja criar. Por exemplo, para criar um diretório chamado "diretorio1" dentro de um diretório chamado "diretorio2," use:

   ```
   mkdir diretorio2/diretorio1
   ```

   - Isso criará "diretorio1" dentro de "diretorio2."

**3. Criar Vários Diretórios de Uma Vez:**

   - Você pode criar vários diretórios de uma vez, fornecendo uma lista de nomes de diretórios separados por espaços. Por exemplo, para criar três diretórios chamados "dir1," "dir2" e "dir3," use:

   ```
   mkdir dir1 dir2 dir3
   ```

   - Isso criará os três diretórios no diretório atual.

**4. Criar Diretórios com Permissões Específicas:**

   - Você também pode criar diretórios com permissões específicas usando a opção `-m`. Por exemplo, para criar um diretório chamado "meudir" com permissões de leitura, gravação e execução para o proprietário e somente leitura para outros, use:

   ```
   mkdir -m 755 meudir
   ```

   - Isso definirá as permissões para "meudir" como 755.

**5. Criar Diretórios Intermediários Automaticamente:**

   - Se você deseja criar um diretório e seus diretórios pai (intermediários) automaticamente, use a opção `-p`. Por exemplo, para criar o diretório "dir4" e seus diretórios pai, use:

   ```
   mkdir -p dir4/diretorio5/diretorio6
   ```

   - Isso criará os diretórios "dir4," "diretorio5" e "diretorio6," conforme necessário.

O comando `mkdir` é uma ferramenta fundamental para criar diretórios no Linux, permitindo que você organize e gerencie seus arquivos e pastas. Experimente essas técnicas para criar diretórios da maneira que melhor atenda às suas necessidades. 