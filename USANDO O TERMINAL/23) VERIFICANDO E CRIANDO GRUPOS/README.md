# VERIFICANDO E CRIANDO GRUPOS NO LINUX
No Linux, você pode criar grupos de usuários usando o comando `groupadd` e verificar os grupos existentes usando o arquivo `/etc/group` ou o comando `getent group`. Vou explicar como criar grupos e listar grupos existentes no Linux (Ubuntu) passo a passo:

**Criando um Grupo no Linux (Ubuntu):**

Para criar um novo grupo, siga estas etapas:

1. **Abra o Terminal:**

   - Abra o terminal no Ubuntu. Você pode pressionar `Ctrl + Alt + T` como atalho de teclado para abrir o terminal.

2. **Use o Comando `groupadd`:**

   - Para criar um novo grupo, use o comando `sudo groupadd` seguido do nome do grupo que você deseja criar. Por exemplo, para criar um grupo chamado "meugrupo," execute o seguinte comando:

   ```
   sudo groupadd meugrupo
   ```

   - O novo grupo será criado e estará disponível no sistema.

**Listando Grupos no Linux (Ubuntu):**

Para listar os grupos existentes, você pode usar os seguintes comandos:

- **Usando o Arquivo `/etc/group`:**

   - Você pode visualizar os grupos existentes lendo o arquivo `/etc/group`. Execute o seguinte comando:

   ```
   cat /etc/group
   ```

   - Isso exibirá uma lista de todos os grupos no sistema, incluindo informações sobre cada um, como nome do grupo, GID (identificador de grupo) e lista de membros.

- **Usando o Comando `getent group`:**

   - Outra maneira de listar grupos é usando o comando `getent group`. Execute o seguinte comando:

   ```
   getent group
   ```

   - Este comando também exibirá uma lista de todos os grupos no sistema, obtendo as informações do arquivo `/etc/group`.

Lembre-se de que você deve ter privilégios de superusuário (`sudo`) para criar grupos ou visualizar informações sobre grupos no sistema.

