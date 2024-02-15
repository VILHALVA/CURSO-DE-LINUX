# COMO CRIAR USUÁRIO NO LINUX
No Linux, você pode criar usuários usando o comando `useradd` e listar os usuários existentes usando o comando `cat /etc/passwd` ou `getent passwd`. Vou explicar como fazer isso passo a passo:

**Criando um Usuário no Linux (Ubuntu):**

Para criar um novo usuário, você pode seguir estas etapas:

1. **Abra o Terminal:**

   - Abra o terminal no Ubuntu. Você pode pressionar `Ctrl + Alt + T` como atalho de teclado para abrir o terminal.

2. **Use o Comando `useradd`:**

   - Para criar um novo usuário, use o comando `sudo useradd` seguido do nome do usuário. Por exemplo, para criar um usuário chamado "novousuario," execute o seguinte comando:

   ```
   sudo useradd novousuario
   ```

   - Isso criará o usuário, mas ele não terá uma senha definida.

3. **Defina uma Senha para o Novo Usuário:**

   - Para definir uma senha para o novo usuário, use o comando `sudo passwd` seguido do nome do usuário. Por exemplo, para definir uma senha para "novousuario," execute o seguinte comando:

   ```
   sudo passwd novousuario
   ```

   - O sistema solicitará que você insira a nova senha duas vezes para confirmar.

4. **Adicionar o Usuário a Grupos (Opcional):**

   - Você pode adicionar o novo usuário a grupos específicos, se necessário. Use o comando `sudo usermod -aG` para adicionar o usuário a grupos. Por exemplo, para adicionar "novousuario" ao grupo "sudo," execute o seguinte comando:

   ```
   sudo usermod -aG sudo novousuario
   ```

   - Isso concede ao novo usuário permissões de superusuário.

**Listando Usuários no Linux (Ubuntu):**

Para listar os usuários existentes, você pode usar os seguintes comandos:

- **Usando `cat /etc/passwd`:**

   ```
   cat /etc/passwd
   ```

   - Isso exibirá uma lista de todos os usuários no sistema, incluindo informações sobre cada um, como nome de usuário, UID (identificador de usuário), GID (identificador de grupo), diretório inicial e shell padrão.

- **Usando `getent passwd`:**

   ```
   getent passwd
   ```

   - Este comando também exibirá uma lista de todos os usuários no sistema, obtendo as informações do arquivo `/etc/passwd`.

Lembrando que você deve ter privilégios de superusuário (`sudo`) para criar novos usuários ou visualizar informações sobre todos os usuários no sistema.

