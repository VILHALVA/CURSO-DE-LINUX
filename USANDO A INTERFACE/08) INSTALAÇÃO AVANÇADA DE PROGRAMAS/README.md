# INSTALAÇÃO AVANÇADA DE PROGRAMAS
**Instalação de Aplicativos no Linux:**

No Linux, você tem várias opções para instalar aplicativos, incluindo o uso de gerenciadores de pacotes, comandos no terminal e download direto de pacotes. Aqui estão algumas abordagens:

1. **Gerenciador de Pacotes Gráfico (Synaptic)**:
   - O Synaptic é uma interface gráfica para gerenciar pacotes no Linux.
   - Abra o Synaptic, pesquise o aplicativo que deseja instalar e selecione-o para instalação.

2. **Instalação pelo Terminal (apt/apt-get)**:
   - O `apt` e o `apt-get` são comandos para gerenciamento de pacotes no Linux.
   - Para instalar um aplicativo usando o `apt`, você pode usar o seguinte comando no terminal:
     ```
     sudo apt install nome-do-pacote
     ```
   - Por exemplo, para instalar o Chromium, você pode executar:
     ```
     sudo apt install chromium-browser
     ```

3. **Download Direto de Pacotes**:
   - Em alguns casos, você pode baixar pacotes diretamente dos sites oficiais dos aplicativos e instalá-los usando ferramentas como o GDebi ou dpkg.
   - Por exemplo, para o Visual Studio Code, você pode baixar o pacote .DEB no site da Microsoft e instalar com o GDebi ou `dpkg`.

**Diferença entre apt e apt-get:**
- Tanto o `apt` quanto o `apt-get` são comandos para gerenciamento de pacotes no Linux.
- O `apt` é uma interface mais amigável e possui recursos adicionais, como sugestões de pacotes relacionados e progresso de download.
- O `apt-get` é uma ferramenta mais antiga e amplamente usada.

**Instalação do htop:**

O `htop` é uma ferramenta de monitoramento do sistema que exibe informações sobre o uso da CPU, memória e processos. Você pode instalá-lo usando o seguinte comando:

```
sudo apt install htop
```

Após a instalação, basta digitar `htop` no terminal para executar o utilitário e monitorar os recursos do sistema.

**Instalação do Visual Studio Code:**

Para instalar o Visual Studio Code no Linux, siga estas etapas:

1. Vá para o site oficial do Visual Studio Code: https://code.visualstudio.com/
2. Clique no botão "Download for Linux" para baixar o pacote .DEB.
3. Após o download, abra o terminal e navegue até o diretório onde o pacote foi baixado.
4. Instale o pacote usando o comando `sudo dpkg -i nome-do-pacote.deb`.

Depois de instalado, você pode iniciar o Visual Studio Code a partir do menu ou usando o comando `code` no terminal.

Essas são algumas maneiras de instalar aplicativos no Linux e realizar tarefas avançadas de gerenciamento de pacotes. Lembre-se de que a disponibilidade de pacotes e os comandos específicos podem variar dependendo da distribuição Linux que você está usando.