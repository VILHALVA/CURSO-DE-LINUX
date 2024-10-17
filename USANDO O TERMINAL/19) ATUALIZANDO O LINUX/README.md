# ATUALIZANDO O LINUX (COMANDO DISTUPGRADE)
A atualização do sistema Linux, incluindo o Ubuntu, é um processo importante para garantir que você tenha as versões mais recentes do sistema operacional e das aplicações. No entanto, o comando correto para atualizar o sistema não é `distupgrade`, mas sim `dist-upgrade`. Vou explicar como usar o comando `dist-upgrade` para atualizar o Ubuntu:

**Atualizando o Ubuntu com `dist-upgrade`:**

1. **Abra o Terminal:**

   - Para iniciar o processo de atualização, abra o terminal no Ubuntu. Você pode pressionar `Ctrl + Alt + T` como atalho de teclado para abrir o terminal.

2. **Atualize a Lista de Repositórios:**

   - Primeiro, é uma boa prática atualizar a lista de repositórios para obter as informações mais recentes sobre os pacotes disponíveis. Execute o seguinte comando:

   ```
   sudo apt update
   ```

3. **Atualize o Sistema:**

   - Após atualizar a lista de repositórios, você pode usar o comando `dist-upgrade` para atualizar o sistema. Execute o seguinte comando:

   ```
   sudo apt dist-upgrade
   ```

   - O sistema verificará as atualizações disponíveis e perguntará se você deseja continuar. Digite "Y" e pressione "Enter" para confirmar.

4. **Digite sua Senha (se solicitado):**

   - O sistema pode solicitar sua senha de administrador (root) para continuar com a atualização. Digite sua senha e pressione "Enter."

5. **Aguarde a Atualização:**

   - O sistema baixará e instalará as atualizações disponíveis. O processo pode levar algum tempo, dependendo da quantidade de atualizações e do desempenho do seu sistema.

6. **Reinicie o Sistema (Opcional):**

   - Após a conclusão da atualização, você pode reiniciar o sistema para aplicar todas as alterações. Execute o seguinte comando para reiniciar:

   ```
   sudo reboot
   ```

Isso é um exemplo de como usar o `dist-upgrade` para atualizar o Ubuntu. Lembre-se de que é importante manter seu sistema atualizado para garantir a segurança e o desempenho adequado.

