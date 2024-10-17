# ADICIONANDO UM USUÁRIO A UM GRUPO (USERMOD)
Adicionar um usuário a um grupo existente no Linux/Ubuntu é uma tarefa relativamente simples que pode ser realizada usando o comando `usermod`. Vou explicar como fazer isso passo a passo:

**Adicionando um Usuário a um Grupo no Linux (Ubuntu) com `usermod`:**

1. **Abra o Terminal:**

   - Abra o terminal no Ubuntu. Você pode pressionar `Ctrl + Alt + T` como atalho de teclado para abrir o terminal.

2. **Use o Comando `usermod`:**

   - Para adicionar um usuário a um grupo, use o comando `sudo usermod -aG` seguido do nome do grupo e do nome do usuário. Por exemplo, para adicionar o usuário "novousuario" ao grupo "meugrupo," execute o seguinte comando:

   ```
   sudo usermod -aG meugrupo novousuario
   ```

   - O comando `usermod` com a opção `-aG` adiciona o usuário ao grupo especificado.

3. **Verifique a Adição ao Grupo (Opcional):**

   - Para verificar se o usuário foi adicionado com sucesso ao grupo, você pode listar os grupos do usuário usando o seguinte comando:

   ```
   groups novousuario
   ```

   - Isso exibirá uma lista dos grupos dos quais o usuário faz parte. Certifique-se de que o grupo desejado esteja listado.

**Nota Importante:**

- Após adicionar um usuário a um grupo, você deve solicitar ao usuário que faça logout e login novamente para que as alterações tenham efeito. Isso ocorre porque as associações de grupos são carregadas quando o usuário inicia a sessão.

- Certifique-se de que o grupo ao qual está adicionando o usuário já exista no sistema. Caso contrário, você pode criar o grupo usando o comando `groupadd` (como mencionado anteriormente) antes de adicionar o usuário a ele.

Lembre-se de que você deve ter privilégios de superusuário (`sudo`) para adicionar um usuário a um grupo. Certifique-se de usar os nomes de usuário e grupos corretos ao executar os comandos.

Após seguir essas etapas, o usuário selecionado estará associado ao grupo especificado e terá acesso às permissões e recursos desse grupo.

