# PERMISSÕES NO LINUX PRÁTICA (MODO NUMÉRICO)
Vamos praticar a configuração de permissões no Linux usando a notação numérica. Vou criar alguns exemplos de cenários comuns e mostrar como você pode usar a notação numérica para definir as permissões apropriadas.

**Exemplo 1: Arquivo de Texto**

Suponha que você tenha um arquivo de texto chamado "documento.txt" e deseje configurar as seguintes permissões:

- Proprietário (você) tem permissão de leitura e gravação.
- Grupo tem permissão de leitura.
- Outros não têm permissões.

Para alcançar isso, você pode usar o seguinte comando `chmod` com notação numérica:

```bash
chmod 640 documento.txt
```

Aqui está a explicação:

- O primeiro dígito "6" representa as permissões do proprietário (rw).
- O segundo dígito "4" representa as permissões do grupo (r).
- O terceiro dígito "0" representa as permissões para outros (nenhuma).

**Exemplo 2: Diretório Público**

Suponha que você tenha um diretório chamado "compartilhado" e deseje configurar as seguintes permissões:

- Proprietário (você) tem permissão de leitura, gravação e execução.
- Grupo tem permissão de leitura e execução.
- Outros têm permissão de leitura e execução.

Para alcançar isso, você pode usar o seguinte comando `chmod` com notação numérica:

```bash
chmod 755 compartilhado
```

Aqui está a explicação:

- O primeiro dígito "7" representa as permissões do proprietário (rwx).
- O segundo dígito "5" representa as permissões do grupo (r-x).
- O terceiro dígito "5" representa as permissões para outros (r-x).

**Exemplo 3: Script Executável**

Suponha que você tenha um script chamado "meuscript.sh" e deseje configurar as seguintes permissões:

- Proprietário (você) tem permissão de leitura, gravação e execução.
- Grupo tem permissão de leitura e execução.
- Outros têm permissão de execução.

Para alcançar isso, você pode usar o seguinte comando `chmod` com notação numérica:

```bash
chmod 751 meuscript.sh
```

Aqui está a explicação:

- O primeiro dígito "7" representa as permissões do proprietário (rwx).
- O segundo dígito "5" representa as permissões do grupo (r-x).
- O terceiro dígito "1" representa as permissões para outros (x).

Esses são apenas alguns exemplos de como você pode usar a notação numérica para definir permissões no Linux. Lembre-se de que as permissões numéricas são uma forma eficaz de configurar rapidamente as permissões, mas é importante entender o sistema de permissões e usá-lo com responsabilidade para garantir a segurança do sistema e dos arquivos.