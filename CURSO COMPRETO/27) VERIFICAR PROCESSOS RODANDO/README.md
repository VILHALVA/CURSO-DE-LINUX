# VERIFICAR PROCESSOS RODANDO NO LINUX (TOP E HTOP)
Verificar os processos em execução no Linux é uma tarefa importante para monitorar o sistema e solucionar problemas. Existem várias ferramentas disponíveis para essa finalidade, incluindo o `top` e o `htop`. Vou explicar como usá-los:

**Usando o comando `top` para Verificar Processos:**

1. **Abra o Terminal:**

   - Abra o terminal no Ubuntu. Você pode pressionar `Ctrl + Alt + T` como atalho de teclado para abrir o terminal.

2. **Execute o Comando `top`:**

   - Para verificar os processos em execução, basta digitar o seguinte comando no terminal:

   ```
   top
   ```

   - Isso abrirá uma visualização em tempo real dos processos em execução no sistema. Você verá informações como uso da CPU, uso da memória, PID (identificador de processo), nome do processo, usuário e muito mais.

3. **Interagindo com o `top`:**

   - No `top`, você pode usar várias teclas de atalho para interagir com a exibição. Alguns comandos comuns incluem:
   
     - `q`: Para sair do `top`.
     - `k`: Para enviar um sinal de término a um processo específico (será solicitado o PID).
     - `r`: Para renice (alterar a prioridade) de um processo (será solicitado o PID).
     - `Space`: Para atualizar a exibição em tempo real.
   
**Usando o `htop` para Verificar Processos:**

1. **Instale o `htop` (se necessário):**

   - O `htop` pode não estar instalado por padrão em todas as distribuições Linux. Você pode instalá-lo usando o seguinte comando:

   ```
   sudo apt install htop
   ```

2. **Execute o Comando `htop`:**

   - Após a instalação, execute o comando `htop` no terminal:

   ```
   htop
   ```

   - O `htop` é semelhante ao `top`, mas oferece uma interface mais amigável e interativa para visualizar os processos em execução.

3. **Interagindo com o `htop`:**

   - Assim como no `top`, você pode usar várias teclas de atalho para interagir com o `htop`. Algumas teclas comuns incluem:
   
     - `q`: Para sair do `htop`.
     - `F2`: Para acessar o menu de configuração.
     - `F9`: Para enviar um sinal de término a um processo específico (será solicitado o PID).
     - `F7` e `F8`: Para navegar pelas opções do menu de configuração.

O `htop` oferece uma interface gráfica interativa e é uma opção mais amigável para verificar os processos em execução.

Escolha o comando `top` ou `htop` com base em sua preferência pessoal e necessidades de monitoramento do sistema. Ambos fornecem informações valiosas sobre os processos em execução no Linux.

