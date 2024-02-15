# REMOVENDO PACOTES (COMANDO PURGE)
Para remover um pacote, programa ou dependência no Linux, você pode usar o comando `apt`. Especificamente, para remover um pacote e todas as suas configurações, você pode usar o comando `apt purge`. Aqui está como fazer isso:

**Removendo um Pacote no Linux com o `apt` (Ubuntu/Debian):**

1. **Identifique o Pacote a Ser Removido:**

   - Antes de remover um pacote, certifique-se de identificar o nome correto do pacote que você deseja desinstalar.

2. **Use o Comando `apt purge` para Remover o Pacote:**

   - Execute o seguinte comando, substituindo `nome-do-pacote` pelo nome do pacote que você deseja remover:

   ```
   sudo apt purge nome-do-pacote
   ```

   - O sistema solicitará sua confirmação antes de prosseguir. Digite "Y" e pressione "Enter" para confirmar.

3. **Digite sua Senha (se solicitado):**

   - O sistema pode solicitar sua senha de administrador (root) para confirmar a remoção. Digite sua senha e pressione "Enter."

4. **Aguarde a Remoção:**

   - O sistema removerá o pacote, incluindo todas as suas configurações e arquivos associados. Aguarde até que o processo de remoção seja concluído.

5. **Pacote Removido:**

   - Após a conclusão da remoção, o pacote estará completamente removido do sistema.

**Nota:** Tenha cuidado ao usar o comando `purge`, pois ele remove todas as configurações e arquivos associados ao pacote. Se você deseja manter as configurações e preferências do pacote, pode usar o comando `apt remove` em vez do `apt purge`. O `apt remove` remove apenas os arquivos do pacote, mantendo as configurações.

Lembre-se de que o nome do pacote pode variar dependendo do software que você deseja remover. Você pode verificar o nome correto do pacote usando a ferramenta de pesquisa de pacotes do seu sistema ou procurando informações na documentação oficial do software.

