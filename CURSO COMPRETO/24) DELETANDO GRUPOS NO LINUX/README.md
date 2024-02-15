# DELETANDO GRUPOS NO LINUX
Para deletar um grupo no Linux, você pode usar o comando `groupdel`. Vou explicar como fazer isso passo a passo:

**Deletando um Grupo no Linux (Ubuntu):**

Para deletar um grupo, siga estas etapas:

1. **Abra o Terminal:**

   - Abra o terminal no Ubuntu. Você pode pressionar `Ctrl + Alt + T` como atalho de teclado para abrir o terminal.

2. **Use o Comando `groupdel`:**

   - Para deletar um grupo, use o comando `sudo groupdel` seguido do nome do grupo que você deseja remover. Por exemplo, se você deseja deletar um grupo chamado "meugrupo," execute o seguinte comando:

   ```
   sudo groupdel meugrupo
   ```

   - O comando `groupdel` irá remover o grupo especificado.

**Nota Importante:**

- Ao deletar um grupo, os usuários que eram membros desse grupo não são automaticamente removidos. Se esses usuários não forem adicionados a outro grupo, eles ficarão sem grupo principal. Você deve tomar medidas adicionais para gerenciar os membros do grupo antes de excluí-lo, se necessário.

Lembre-se de que você deve ter privilégios de superusuário (`sudo`) para deletar grupos. Certifique-se de que o grupo que você deseja excluir não tenha mais membros ou que os membros tenham sido movidos para outros grupos, conforme necessário.

Após seguir essas etapas, o grupo selecionado será removido do sistema Linux (Ubuntu).

