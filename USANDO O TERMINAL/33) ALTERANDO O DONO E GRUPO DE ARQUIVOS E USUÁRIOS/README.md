# ALTERANDO O DONO E GRUPO DE ARQUIVOS E USUÁRIOS (OWNER)
No Linux, você pode alterar o proprietário (owner) e o grupo de arquivos e diretórios usando o comando `chown`. Isso é útil quando você precisa atribuir a propriedade de um arquivo ou diretório a um usuário ou grupo específico. Aqui estão alguns exemplos de como usar o `chown`:

**Alterando o Proprietário de um Arquivo ou Diretório:**

```bash
sudo chown novo_proprietario arquivo_ou_diretorio
```

Substitua `novo_proprietario` pelo nome do novo proprietário (usuário) que você deseja atribuir ao arquivo ou diretório e `arquivo_ou_diretorio` pelo nome do arquivo ou diretório que deseja modificar. Por exemplo:

```bash
sudo chown usuario1 documento.txt
```

Isso alterará o proprietário do arquivo "documento.txt" para "usuario1".

**Alterando o Grupo de um Arquivo ou Diretório:**

```bash
sudo chown :novo_grupo arquivo_ou_diretorio
```

Substitua `novo_grupo` pelo nome do novo grupo que você deseja atribuir ao arquivo ou diretório. Por exemplo:

```bash
sudo chown :grupo2 pasta_compartilhada
```

Isso alterará o grupo do diretório "pasta_compartilhada" para "grupo2". Observe que o `:` antes do nome do grupo indica que você está alterando apenas o grupo, não o proprietário.

**Alterando Proprietário e Grupo Simultaneamente:**

Você também pode alterar o proprietário e o grupo simultaneamente usando a seguinte sintaxe:

```bash
sudo chown novo_proprietario:novo_grupo arquivo_ou_diretorio
```

Substitua `novo_proprietario` pelo nome do novo proprietário e `novo_grupo` pelo nome do novo grupo. Por exemplo:

```bash
sudo chown usuario3:grupo3 arquivo.txt
```

Isso alterará tanto o proprietário quanto o grupo do arquivo "arquivo.txt" para "usuario3" e "grupo3", respectivamente.

Tenha em mente que você geralmente precisa de privilégios de superusuário (sudo) para alterar o proprietário e o grupo de arquivos e diretórios, pois essa é uma operação sensível. Certifique-se de usar esses comandos com cuidado e responsabilidade.