# REMOVENDO DIRETÓRIOS LINUX (COMANDO RMDIR)
O comando `rmdir` é usado para remover diretórios (pastas) vazios no Linux. Ele é uma ferramenta simples e útil quando você precisa excluir diretórios que não contêm arquivos ou subdiretórios. Vamos explorar como usar o `rmdir` para remover diretórios vazios:

**Comando `rmdir` (Remove Directory):**

1. **Remover um Diretório Vazio:**

   - Para remover um diretório vazio, basta usar o comando `rmdir` seguido do nome do diretório que você deseja excluir. Por exemplo, para excluir um diretório vazio chamado "meudiretorio," use:

   ```
   rmdir meudiretorio
   ```

   - Isso excluirá o diretório vazio permanentemente.

2. **Remover Vários Diretórios Vazios de Uma Vez:**

   - Você pode remover vários diretórios vazios de uma vez, fornecendo uma lista de nomes de diretórios separados por espaços. Por exemplo, para excluir três diretórios vazios chamados "dir1," "dir2" e "dir3," use:

   ```
   rmdir dir1 dir2 dir3
   ```

   - Todos os diretórios vazios listados serão excluídos permanentemente.

3. **Remover Diretórios Interativamente (Opção `-i`):**

   - Para remover diretórios de forma mais segura e interativa, você pode usar a opção `-i` com o `rmdir`. Isso solicitará confirmação antes de excluir cada diretório. Por exemplo:

   ```
   rmdir -i dir1 dir2 dir3
   ```

   - Isso permitirá que você confirme cada remoção.

Lembre-se de que o `rmdir` só pode ser usado para excluir diretórios vazios. Se um diretório contiver arquivos ou subdiretórios, você precisará usar o comando `rm` com a opção `-r` (recursiva) para excluir todo o conteúdo do diretório e o próprio diretório.

Certifique-se de ter cuidado ao usar o `rmdir` e verifique se os diretórios que você deseja excluir estão realmente vazios, pois ele não removerá diretórios com conteúdo. 