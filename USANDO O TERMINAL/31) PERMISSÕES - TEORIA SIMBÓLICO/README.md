# PERMISSÕES NO LINUX TEORIA (MODO SIMBÓLICO)
As permissões no Linux também podem ser configuradas usando a notação simbólica, que é uma maneira mais descritiva de definir quem tem acesso a um arquivo ou diretório. A notação simbólica usa letras e símbolos para representar permissões e atributos. Aqui está como funciona:

1. **Notação Simbólica Básica:**

   - A notação simbólica usa três grupos de letras/símbolos para representar as permissões dos proprietários, grupos e outros. A ordem é a seguinte: proprietário, grupo, outros.

   - Os principais símbolos utilizados são:

     - `r` para permissão de leitura (read).
     - `w` para permissão de gravação (write).
     - `x` para permissão de execução (execute).
     - `-` para indicar que uma permissão está ausente.

2. **Sintaxe da Notação Simbólica:**

   - A sintaxe geral da notação simbólica é a seguinte:

     ```
     ugo +/- rwx
     ```

     - `u` representa o proprietário.
     - `g` representa o grupo.
     - `o` representa outros.
     - `+` adiciona permissões.
     - `-` remove permissões.
     - `r`, `w` e `x` representam as permissões de leitura, gravação e execução, respectivamente.

3. **Exemplos de Notação Simbólica:**

   - Para dar permissão de leitura e gravação ao proprietário em um arquivo chamado "arquivo.txt," você pode usar:

     ```
     chmod u+rw arquivo.txt
     ```

   - Para remover permissão de execução para outros em um script chamado "script.sh," você pode usar:

     ```
     chmod o-x script.sh
     ```

   - Para dar permissão de execução para todos em um diretório chamado "meudir," você pode usar:

     ```
     chmod a+x meudir
     ```

4. **Combinando Permissões:**

   - Você pode combinar várias permissões em uma única operação. Por exemplo, para dar permissões de leitura e gravação ao proprietário e ao grupo em um arquivo:

     ```
     chmod ug+rw arquivo.txt
     ```

   - Para dar permissão de execução a todos:

     ```
     chmod a+x arquivo.txt
     ```

5. **Definindo Atributos Especiais:**

   - Além das permissões padrão, você pode usar atributos especiais como `s` (setuid/setgid) e `t` (sticky bit) na notação simbólica para configurar permissões especiais.

     - `chmod +s arquivo` - Define o bit setuid ou setgid.
     - `chmod +t diretório` - Define o bit sticky em um diretório.

A notação simbólica é mais legível e descritiva do que a notação numérica, tornando-a útil para entender rapidamente as permissões de um arquivo ou diretório. Ela oferece flexibilidade para adicionar ou remover permissões e atributos de forma mais intuitiva.