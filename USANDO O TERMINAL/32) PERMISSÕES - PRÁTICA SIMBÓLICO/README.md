# PERMISSÕES NO LINUX PRÁTICA (MODO SIMBÓLICO)
Vamos praticar a configuração de permissões no Linux usando a notação simbólica. Vou criar alguns cenários comuns e mostrar como você pode usar a notação simbólica para definir as permissões apropriadas.

**Exemplo 1: Arquivo de Texto**

Suponha que você tenha um arquivo de texto chamado "documento.txt" e deseje configurar as seguintes permissões:

- Proprietário (você) tem permissão de leitura e gravação.
- Grupo tem permissão de leitura.
- Outros não têm permissões.

Para alcançar isso, você pode usar o seguinte comando `chmod` com notação simbólica:

```bash
chmod u=rw,g=r,o= documento.txt
```

Aqui está a explicação:

- `u=rw` define permissões para o proprietário (rw).
- `g=r` define permissões para o grupo (r).
- `o=` remove todas as permissões para outros (nenhuma).

**Exemplo 2: Diretório Público**

Suponha que você tenha um diretório chamado "compartilhado" e deseje configurar as seguintes permissões:

- Proprietário (você) tem permissão de leitura, gravação e execução.
- Grupo tem permissão de leitura e execução.
- Outros têm permissão de leitura e execução.

Para alcançar isso, você pode usar o seguinte comando `chmod` com notação simbólica:

```bash
chmod u=rwx,g=rx,o=rx compartilhado
```

Aqui está a explicação:

- `u=rwx` define permissões para o proprietário (rwx).
- `g=rx` define permissões para o grupo (rx).
- `o=rx` define permissões para outros (rx).

**Exemplo 3: Script Executável**

Suponha que você tenha um script chamado "meuscript.sh" e deseje configurar as seguintes permissões:

- Proprietário (você) tem permissão de leitura, gravação e execução.
- Grupo tem permissão de leitura e execução.
- Outros têm permissão de execução.

Para alcançar isso, você pode usar o seguinte comando `chmod` com notação simbólica:

```bash
chmod u=rwx,g=rx,o=x meuscript.sh
```

Aqui está a explicação:

- `u=rwx` define permissões para o proprietário (rwx).
- `g=rx` define permissões para o grupo (rx).
- `o=x` define permissões para outros (x).

Esses são apenas alguns exemplos de como você pode usar a notação simbólica para definir permissões no Linux. A notação simbólica é mais legível e descritiva do que a notação numérica, tornando-a útil para configurar permissões de forma intuitiva. Lembre-se de que é importante entender o sistema de permissões e usá-lo com responsabilidade para garantir a segurança dos seus arquivos e diretórios.