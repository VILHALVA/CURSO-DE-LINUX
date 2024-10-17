# TERMINAL LINUX - REFERÊNCIA GLOBAL
**Caracteres de Referência Global no Linux:**

1. **Asterisco (*)**: O asterisco é usado como um caractere curinga para representar zero ou mais caracteres em um nome de arquivo. Por exemplo:
   - `*.txt` corresponde a todos os arquivos com extensão ".txt" no diretório atual.
   - `doc*` corresponde a qualquer arquivo ou diretório que comece com "doc".

2. **Ponto de Interrogação (?)**: O ponto de interrogação é usado como um caractere curinga para representar um único caractere em um nome de arquivo. Por exemplo:
   - `file?.txt` corresponde a arquivos como "file1.txt", "fileA.txt", onde o "?" representa um único caractere.

3. **Colchetes ([ ])**: Os colchetes são usados para criar classes de caracteres e fazer correspondência com qualquer caractere dentro dessa classe. Por exemplo:
   - `[aeiou]` corresponde a qualquer vogal.
   - `[0-9]` corresponde a qualquer dígito de 0 a 9.
   - `[A-Za-z]` corresponde a qualquer letra maiúscula ou minúscula.

**Exemplos de Uso:**

- Se você deseja listar todos os arquivos que começam com "file" e têm qualquer caractere após "file", você pode usar o comando:
  ```
  ls file?
  ```

- Se você deseja listar todos os arquivos com extensão ".txt" ou ".pdf", pode usar o comando:
  ```
  ls *.txt *.pdf
  ```

- Se você deseja listar todos os arquivos que contêm um dígito no nome, pode usar o comando:
  ```
  ls *[0-9]*
  ```

Esses caracteres de referência global são extremamente úteis para fazer correspondências e executar operações em vários arquivos de uma só vez no terminal Linux. Eles facilitam a manipulação de arquivos quando você precisa trabalhar com muitos deles de uma só vez.