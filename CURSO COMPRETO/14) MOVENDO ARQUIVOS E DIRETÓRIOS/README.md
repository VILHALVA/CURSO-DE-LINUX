# MOVENDO ARQUIVOS E DIRETÓRIOS (COMANDO MV)
O comando `mv` é usado para mover arquivos e diretórios no Ubuntu e em outros sistemas Linux. Ele é semelhante ao comando "Ctrl + X" no Windows, pois permite que você mova arquivos e diretórios de um local para outro. Vamos explorar como usar o `mv` para mover arquivos e diretórios:

**Comando `mv` (Move):**

**1. Mover um Arquivo:**

- Para mover um arquivo específico, use o comando `mv` seguido do nome do arquivo que você deseja mover e, em seguida, o destino para onde deseja movê-lo. Por exemplo, para mover um arquivo chamado "arquivo.txt" para um diretório chamado "destino," use:

   ```
   mv arquivo.txt destino/
   ```

- Isso moverá o arquivo "arquivo.txt" para o diretório "destino."

**2. Mover Múltiplos Arquivos:**

- Você pode mover vários arquivos de uma vez, fornecendo uma lista de nomes de arquivos separados por espaços, seguidos pelo destino. Por exemplo, para mover três arquivos ("arquivo1.txt," "arquivo2.txt" e "arquivo3.txt") para o diretório "destino," use:

   ```
   mv arquivo1.txt arquivo2.txt arquivo3.txt destino/
   ```

**3. Mover um Diretório com todo o Conteúdo:**

- Para mover um diretório e todo o seu conteúdo, incluindo subdiretórios e arquivos, use o comando `mv` com a opção `-r` (recursiva). Por exemplo, para mover um diretório chamado "meudiretorio" para um diretório "destino," use:

   ```
   mv -r meudiretorio destino/
   ```

- Isso moverá "meudiretorio" e todo o seu conteúdo para o diretório "destino."

**4. Renomear Arquivos ou Diretórios:**

- Você também pode usar o `mv` para renomear arquivos ou diretórios, movendo-os para o mesmo local com um novo nome. Por exemplo, para renomear um arquivo "antigo.txt" para "novo.txt," use:

   ```
   mv antigo.txt novo.txt
   ```

Isso renomeará o arquivo "antigo.txt" para "novo.txt" no mesmo diretório.

O comando `mv` é uma ferramenta versátil que permite mover e renomear arquivos e diretórios no Linux. Certifique-se de fornecer os caminhos corretos para o arquivo ou diretório que você deseja mover e o destino desejado. Verifique duas vezes antes de executar o comando para evitar erros. 