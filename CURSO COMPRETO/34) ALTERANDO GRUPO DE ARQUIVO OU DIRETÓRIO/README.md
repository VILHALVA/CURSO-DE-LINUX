# ALTERANDO GRUPO DE ARQUIVO OU DIRETÓRIO
Para alterar o grupo de um arquivo ou diretório no Linux, você pode usar o comando `chown` com a opção `-c` para alterar o grupo. Lembre-se de que você geralmente precisa de privilégios de superusuário (root) ou pertencer ao grupo atual do arquivo para realizar essa operação. Aqui está a sintaxe básica:

```bash
sudo chown :novo_grupo arquivo_ou_diretorio
```

Substitua `novo_grupo` pelo nome do novo grupo que você deseja atribuir ao arquivo ou diretório e `arquivo_ou_diretorio` pelo nome do arquivo ou diretório que você deseja modificar. Por exemplo:

```bash
sudo chown :novo_grupo arquivo.txt
```

Isso alterará o grupo do arquivo "arquivo.txt" para "novo_grupo".

Lembre-se de que você pode precisar usar o `sudo` para executar o comando com permissões de superusuário, especialmente se você não for o proprietário do arquivo ou diretório ou não pertencer ao grupo atual. Certifique-se de que a alteração de grupo seja feita com responsabilidade e de acordo com as políticas de segurança do seu sistema.