# Roteiro de Estudos sobre Windows Subsystem for Linux

## Objetivo
Esse roteiro tem como objetivo expor os conhecimentos estudados sobre o WSL, descrevendo o processo de sua instalação e apresentando os comandos básicos mais usados nos sistemas operacionais baseados em Linux.
## Tópicos

### 1. Introdução
- O Windows Subsystem for Linux possibilita a execução de um ambiente GNU/Linux - incluindo a maioria das ferramentas de linha de comando, utilitários e aplicativos - diretamente no Windows, sem modificações, sem a sobrecarga de uma máquina virtual tradicional ou configuração de inicialização dupla.

### 2. Instalação do Windows Subsystem for Linux 
- É possível instalar tudo o que é preciso para executar o WSL utilizando apenas um comando. Basta abrir o PowerShell ou o Prompt de Comando do Windows em modo de administrador, clicando com o botão direito e selecionando "Executar como administrador", digite o seguinte comando:
    ```
    wsl --install
    ```
    Em seguida, o computador deve ser reiniciado. Este comando habilitará os recursos necessários para executar o WSL e instalar a distribuição Ubuntu do Linux.

- É possível que seja necessário instalar um pacote opcional do WSL para que seja possível começar a utilizá-lo. Caso apareça um aviso no prompt mencionando esse pacote, é possível resolver esse problema seguindo os passos mostrados nesse site:
    ```
    https://linuxhint.com/enable-wsl-optional-component/
    ```
### 3. Comandos Básicos Linux
- __Encontra o caminho completo do diretório atual__:
    ```
        pwd 
    ```
- __Permite navegar até determinada pasta__:
    ```
        cd 
    ```
- __Lista todos os arquivos e pastas dentro de um diretório__:
    ```
        ls
    ```
- __Lista os conteúdos de um arquivo de texto na saída padrão (sdout) ou pode criar um arquivo em branco__:
    ```
        cat
    ```
- __Copia arquivos do diretório atual para uma pasta diferente__:
    ```
        cp
    ```
- __Pode ser usado para mover ou renomear arquivos__:
    ```
        mv
    ```
- __Cria um novo diretório__:
    ```
        mkdir
    ```
- __Remove arquivos e diretórios__:
    ```
        rm 
    ```
- __Executa um comando como superusuário__:
    ```
        sudo
    ```
- __Busca arquivos em diretórios__:
    ```
        find
    ```

### 4. Referências
- [O que é WSL?](https://learn.microsoft.com/en-us/windows/wsl/install)
  
- [Pacote Opcional.](https://linuxhint.com/enable-wsl-optional-component/)

- [Configurar um ambiente de desenvolvimento do WSL.](https://learn.microsoft.com/pt-br/windows/wsl/setup/environment#set-up-your-linux-user-info)
  
- [Comandos Básicos Linux](https://www.hostinger.com.br/tutoriais/comandos-linux)