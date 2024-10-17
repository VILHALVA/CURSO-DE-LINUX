# INSTALANDO O SUBLIME TEXT PELO TERMINAL NO LINUX
Você pode instalar o Sublime Text no Linux, incluindo o Ubuntu, usando o terminal. Vou explicar como fazer isso passo a passo:

**Instalando o Sublime Text no Ubuntu pelo Terminal:**

1. **Adicionar o Repositório do Sublime Text:**

   - Abra o terminal no Ubuntu.

   - Adicione o repositório oficial do Sublime Text ao seu sistema com o seguinte comando:

   ```
   wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
   ```

   Isso importará a chave de assinatura do Sublime Text.

   - Em seguida, adicione o repositório ao seu sistema:

   ```
   sudo apt-add-repository "deb https://download.sublimetext.com/ apt/stable/"
   ```

2. **Atualizar a Lista de Repositórios:**

   - Atualize a lista de repositórios para incluir o repositório recém-adicionado:

   ```
   sudo apt update
   ```

3. **Instalar o Sublime Text:**

   - Agora você pode instalar o Sublime Text usando o seguinte comando:

   ```
   sudo apt install sublime-text
   ```

   O sistema solicitará sua confirmação. Digite "Y" e pressione "Enter" para confirmar a instalação.

4. **Iniciar o Sublime Text:**

   - Após a conclusão da instalação, você pode iniciar o Sublime Text digitando `subl` no terminal ou procurando por "Sublime Text" no menu de aplicativos.

   ```
   subl
   ```

   O Sublime Text estará pronto para uso.

Isso é tudo! Você instalou o Sublime Text no seu sistema Ubuntu usando o terminal. Agora você pode usá-lo como seu editor de texto preferido.

