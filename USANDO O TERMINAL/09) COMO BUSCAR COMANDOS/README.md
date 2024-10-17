# COMO BUSCAR COMANDOS NO LINUX (COMANDO HISTORY)
Vamos explorar como buscar comandos previamente executados no Linux usando o comando `history`. O `history` é uma ferramenta útil para visualizar e reexecutar comandos anteriores no terminal.

**Comando `history` (Histórico de Comandos):**

- O comando `history` é usado para exibir uma lista dos comandos executados anteriormente no terminal, juntamente com seus números de identificação.

**1. Exibir o Histórico Completo de Comandos:**

   - Para exibir o histórico completo de comandos, basta digitar:
   
   ```
   history
   ```

   - Isso listará todos os comandos anteriores, numerados sequencialmente.

**2. Buscar por Comandos Específicos:**

   - Para buscar comandos específicos no histórico, você pode usar o comando `grep`. Por exemplo, se você deseja encontrar todos os comandos relacionados a "arquivos," você pode usar o seguinte comando:

   ```
   history | grep arquivos
   ```

   - Isso exibirá uma lista de todos os comandos que contêm a palavra "arquivos" em seu histórico.

**3. Reexecutar Comandos pelo Número de Identificação:**

   - Para reexecutar um comando específico a partir do histórico, use o número de identificação associado ao comando na lista do `history`. Por exemplo, se o comando que você deseja reexecutar tem o número de identificação 42, digite:

   ```
   !42
   ```

   - Isso reexecutará o comando com o número 42.

**4. Pesquisar Comandos Anteriores com CTRL+R:**

   - Além do `history`, você pode usar uma função conveniente no terminal pressionando `CTRL+R`. Isso abrirá um prompt de pesquisa reversa interativa que permite pesquisar e reexecutar comandos anteriores. Digite uma palavra-chave ou uma parte do comando que você deseja encontrar e pressione `ENTER` para executá-lo.

**5. Limitar o Número de Comandos Exibidos:**

   - Por padrão, o `history` exibe todos os comandos, o que pode ser muitos. Para limitar o número de comandos exibidos, você pode usar a opção `-n` seguida pelo número de comandos a serem exibidos. Por exemplo, para exibir os últimos 10 comandos:

   ```
   history -n 10
   ```

   - Isso exibirá apenas os 10 comandos mais recentes.

O `history` é uma ferramenta poderosa para revisar e reexecutar comandos anteriores no Linux, tornando-o mais eficiente ao trabalhar com o terminal. Experimente essas técnicas para encontrar e reutilizar comandos com facilidade. 