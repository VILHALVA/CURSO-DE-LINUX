# COMO DELETAR USUÁRIOS NO LINUX
Para deletar um usuário no Linux, você pode usar o comando `userdel`. Vou explicar como fazer isso passo a passo:

**Deletando um Usuário no Linux (Ubuntu):**

1. **Abra o Terminal:**

   - Abra o terminal no Ubuntu. Você pode pressionar `Ctrl + Alt + T` como atalho de teclado para abrir o terminal.

2. **Use o Comando `userdel`:**

   - Para deletar um usuário, use o comando `sudo userdel` seguido do nome do usuário que você deseja remover. Por exemplo, se você deseja deletar um usuário chamado "usuariodeletar," execute o seguinte comando:

   ```
   sudo userdel usuariodeletar
   ```

   - O comando `userdel` irá deletar o usuário, mas não removerá automaticamente o diretório pessoal do usuário ou seus arquivos.

3. **Remover o Diretório Pessoal (Opcional):**

   - Se você deseja remover o diretório pessoal do usuário e todos os seus arquivos, você pode usar o comando `sudo rm -r` seguido do caminho para o diretório pessoal do usuário. Por exemplo:

   ```
   sudo rm -r /home/usuariodeletar
   ```

   - Tenha muito cuidado ao usar o comando `rm -r`, pois ele excluirá permanentemente todos os arquivos no diretório especificado.

4. **Remover as Configurações do Grupo (Opcional):**

   - Se o usuário estiver em um grupo exclusivo, você pode querer remover o grupo correspondente usando o comando `sudo groupdel`. Por exemplo:

   ```
   sudo groupdel grupodousuario
   ```

   - Isso é opcional e depende das configurações específicas do seu sistema.

Lembre-se de que você deve ter privilégios de superusuário (`sudo`) para deletar um usuário. Além disso, tome cuidado ao usar comandos que envolvem a remoção de arquivos ou diretórios, pois eles são irreversíveis.

Após seguir essas etapas, o usuário selecionado será removido do sistema Linux (Ubuntu).

