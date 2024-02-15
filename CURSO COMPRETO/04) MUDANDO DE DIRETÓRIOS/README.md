# MUDANDO DE DIRETÓRIOS (COMANDO CD)
**Comando `cd` (Change Directory):**

O comando `cd` é usado para mudar de diretório no terminal do Linux. Aqui estão algumas maneiras de usá-lo:

**1. Mudar para o Diretório Pessoal:**
   - Você pode usar o comando `cd` sem argumentos para voltar ao seu diretório pessoal:
   ```
   cd
   ```

**2. Mudar para um Diretório Específico:**
   - Para mudar para um diretório específico, forneça o caminho completo ou relativo como argumento. Por exemplo, para mudar para um diretório chamado "documentos," use:
   ```
   cd documentos
   ```
   - Use `cd ..` para voltar um nível no diretório.

**3. Diretórios Relativos:**
   - Você pode usar diretórios relativos ao diretório atual. Por exemplo, para ir de "diretorio1" para "diretorio2," use:
   ```
   cd diretorio2
   ```
   Isso assume que "diretorio2" está dentro de "diretorio1."

**4. Diretórios Absolutos:**
   - Você também pode usar caminhos absolutos para navegar para qualquer diretório no sistema. Por exemplo:
   ```
   cd /caminho/para/o/seu/diretorio
   ```

**5. Atalhos:**
   - Existem alguns atalhos úteis que você pode usar com o `cd`:
     - `cd ~`: Vai para o diretório pessoal.
     - `cd -`: Volta para o diretório anterior.

**Dicas Adicionais:**

- Use o comando `pwd` para imprimir o diretório atual (trabalhando).
- Você pode usar a tecla "Tab" para completar nomes de diretório automaticamente. Por exemplo, digitar `cd doc` e pressionar "Tab" completará automaticamente para `cd documentos` se não houver ambiguidades.

- Lembre-se de que nomes de diretórios e arquivos são sensíveis a maiúsculas e minúsculas no Linux. Certifique-se de digitar corretamente os nomes.

Agora você deve estar pronto para navegar entre diretórios usando o comando `cd`. 