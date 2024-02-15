# COPIANDO ARQUIVOS E DIRETÓRIOS NO LINUX (COMANDO CP)
O comando `cp` é usado para copiar arquivos e diretórios no Linux, incluindo a distribuição Ubuntu. Vamos explorar como usar o `cp` para copiar arquivos e diretórios:

**Comando `cp` (Copy):**

**1. Copiar um Arquivo:**

- Para copiar um arquivo específico, use o comando `cp` seguido do nome do arquivo que você deseja copiar e, em seguida, o destino para onde deseja copiá-lo. Por exemplo, para copiar um arquivo chamado "arquivo.txt" para um diretório chamado "destino," use:

   ```
   cp arquivo.txt destino/
   ```

- Isso copiará o arquivo "arquivo.txt" para o diretório "destino."

**2. Copiar Múltiplos Arquivos:**

- Você pode copiar vários arquivos de uma vez, fornecendo uma lista de nomes de arquivos separados por espaços, seguidos pelo destino. Por exemplo, para copiar três arquivos ("arquivo1.txt," "arquivo2.txt" e "arquivo3.txt") para o diretório "destino," use:

   ```
   cp arquivo1.txt arquivo2.txt arquivo3.txt destino/
   ```

**3. Copiar um Diretório com todo o Conteúdo:**

- Para copiar um diretório e todo o seu conteúdo, incluindo subdiretórios e arquivos, use o comando `cp` com a opção `-r` (recursiva). Por exemplo, para copiar um diretório chamado "meudiretorio" para um diretório "destino," use:

   ```
   cp -r meudiretorio destino/
   ```

- Isso copiará "meudiretorio" e todo o seu conteúdo para o diretório "destino."

**4. Copiar Diretórios Interativamente (Opção `-i`):**

- Você pode usar a opção `-i` com o `cp` para copiar diretórios de forma mais segura e interativa. Isso solicitará confirmação antes de substituir arquivos existentes no destino. Por exemplo:

   ```
   cp -ri origem/ destino/
   ```

- Isso permitirá que você confirme cada operação de cópia, o que é útil para evitar substituições acidentais.

Lembre-se de que o comando `cp` é uma ferramenta poderosa para copiar arquivos e diretórios, mas deve ser usado com cuidado para evitar a sobregravação de arquivos importantes. Certifique-se de fornecer o caminho correto para o destino e verifique duas vezes antes de copiar ou substituir arquivos. 