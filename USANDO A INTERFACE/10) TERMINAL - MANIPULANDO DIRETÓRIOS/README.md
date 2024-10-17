# TERMINAL NO LINUX - MANIPULANDO DIRETÓRIOS
**Pastas e Diretórios em Linux:**
Pastas e diretórios são termos usados de forma intercambiável no contexto do sistema de arquivos do Linux. Em um sistema Linux, um diretório é uma estrutura que pode conter arquivos e subdiretórios, e é frequentemente referido como uma "pasta" em interfaces gráficas de usuário.

**Comando cd no Linux:**
O comando `cd` é usado para mudar de diretório no terminal. Aqui estão alguns exemplos de uso:

- `cd diretorio`: Muda para o diretório especificado.
- `cd ..`: Volta um nível no diretório.
- `cd ~`: Vai para o diretório pessoal do usuário.
- `cd /`: Vai para o diretório raiz do sistema.

**Comando mkdir no Linux:**
O comando `mkdir` é usado para criar diretórios. Para criar um diretório simples, você pode usar:
```
mkdir nome-do-diretorio
```

**Criando um Caminho com Várias Pastas ao Mesmo Tempo:**
Você pode usar a opção `-p` com o comando `mkdir` para criar um caminho com várias pastas ao mesmo tempo, incluindo diretórios intermediários ausentes. Por exemplo:
```
mkdir -p pasta1/pasta2/pasta3
```
Isso criará a estrutura de diretórios `pasta1/pasta2/pasta3`, mesmo se `pasta1` e `pasta2` ainda não existirem.

**Apagando Diretórios com o Comando rm:**
O comando `rm` é usado para remover arquivos e diretórios. Use o parâmetro `-r` (ou `-R`) para remover diretórios e seu conteúdo de forma recursiva. Tenha cuidado ao usar este comando, pois ele não move os arquivos para a Lixeira, eles são excluídos permanentemente. Por exemplo:
```
rm -r diretorio
```

**Usando --help e Comando man:**
- Para obter ajuda sobre a maioria dos comandos no terminal, você pode usar o parâmetro `--help`. Por exemplo, `comando --help` fornecerá informações sobre como usar esse comando.
- O comando `man` é usado para acessar as páginas de manual do Linux. Por exemplo, `man comando` abrirá um manual detalhado do comando especificado, incluindo descrições, opções e exemplos de uso.

**Comando history no Linux:**
O comando `history` exibe o histórico de comandos executados no terminal. Ele lista os números dos comandos para que você possa repeti-los usando `!n`, onde "n" é o número do comando listado no histórico.

Essas são algumas das operações básicas relacionadas a diretórios e comandos no terminal do Linux. Manipular diretórios é uma parte essencial do uso do sistema de arquivos do Linux e do trabalho no ambiente de linha de comando.