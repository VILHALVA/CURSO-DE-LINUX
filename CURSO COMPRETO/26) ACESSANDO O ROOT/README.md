# ACESSANDO O ROOT (SUDO SU)
Acessar a conta de superusuário (root) no Linux usando o comando `sudo su` é uma tarefa importante, mas deve ser realizada com cuidado, pois o superusuário possui privilégios elevados e pode alterar ou danificar o sistema. Vou explicar como acessar o root usando o `sudo su` no terminal:

**Acessando a Conta de Superusuário (root) no Linux:**

1. **Abra o Terminal:**

   - Abra o terminal no Ubuntu. Você pode pressionar `Ctrl + Alt + T` como atalho de teclado para abrir o terminal.

2. **Use o Comando `sudo su`:**

   - Para acessar a conta de superusuário (root), execute o seguinte comando:

   ```
   sudo su
   ```

   - O sistema solicitará sua senha de administrador (sudo). Digite a senha e pressione "Enter."

   - Após inserir a senha correta, você estará logado como root e terá privilégios elevados.

3. **Cuidado com Privilégios de Superusuário:**

   - Ao acessar a conta de superusuário, você terá acesso total ao sistema, o que significa que poderá fazer alterações críticas. Tome cuidado ao executar comandos como root e verifique duas vezes antes de prosseguir.

4. **Encerrando a Sessão do Superusuário:**

   - Para encerrar a sessão como root e retornar ao seu usuário normal, você pode simplesmente fechar o terminal ou usar o comando `exit`:

   ```
   exit
   ```

   - Isso encerrará a sessão do superusuário e você voltará ao seu usuário normal.

**Nota Importante:**

- É altamente recomendável usar a conta de superusuário apenas quando necessário para tarefas administrativas específicas. Sempre que possível, é preferível usar `sudo` para executar comandos com privilégios elevados, pois isso permite que você execute ações privilegiadas temporariamente, em vez de estar sempre conectado como root.

- O uso inadequado da conta de superusuário pode resultar em problemas graves no sistema, portanto, use-a com responsabilidade.

Lembre-se de que você deve ter permissões de administrador (sudo) para acessar a conta de superusuário (root) no Linux.

