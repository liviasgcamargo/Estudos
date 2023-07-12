# Roteiro de Estudos sobre SQL Server

## Objetivo
Esse roteiro tem como objetivo expor os conhecimentos estudados sobre SQL Server, descrevendo o processo de sua instalação na máquina e apresentando os comandos básicos utilizados pela plataforma.
## Tópicos

### 1. Introdução
#
- 
### 2. Baixando SQL Server
#
1° - Entrar no site da Microsoft :
 ```
https://www.microsoft.com/pt-br/sql-server/sql-server-downloads    
 ```

2° - Escolher a opção EXPRESS para baixar (link de download): 
```
https://go.microsoft.com/fwlink/p/?linkid=2216019&clcid=0x416&culture=pt-br&country=br
```
3° - Escolher a versão “Básica” após a conclusão do download e aceitar os Termos de Uso.

4° - Assim, concluímos a instalação e alocação do servidor na máquina atual. Agora é necessário instalar o SSMS, que é a plataforma na qual iremos realizar as atividades. Através do link a seguir, você entrará no site da Microsoft para obter as instruções de como baixar o SSMS: 
```
https://learn.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16&redirectedfrom=MSDN
````
5° - O download do SSMS pode ser feito através do link a seguir (link do download):
```
https://aka.ms/ssmsfullsetup
```
6° - Feita a instalação, será necessário reiniciar o computador para que o SSMS possa funcionar.

7° - Após reiniciá-lo, procure pelo SSMS no iniciar e continue a instalação como sugerido pelo aplicativo. Para isso é necessário aceitar os Termos de Uso.

8° - Aguarde a instalação completa de todos os Pacotes.

### 3. Iniciando o SQL Server

1° - Após logar no servidor, criamos um novo banco de dados na pasta “Baco de Dados”, clicando no botão direito do mouse e escolhemos a opção “Novo Banco de Dados”.

```
        Banco de Dados => Novo Banco de Dados
```
2° - 

  
### 4. Comandos Básicos
- CREATE TABLE sintaxe
    ```
    CREATE TABLE nomeTabela (  
        nomeColuna1 int
        ,nomeColuna2 varchar(50) NOT NULL 
        ,nomeColuna3 int NOT NULL 
    );
    ```

- INSERT INTO sintaxe 
    ```
    INSERT INTO [tabela] (
        [nomeColuna1]
        ,[nomeColuna2]
        ,[nomeColuna3]
    )
    VALUES (
        “valorParaColuna1”
        ,“valorParaColuna2”
        ,“valorParaColuna3”
    ) 
    ```
- SELECT FROM sintaxe
    ```
    SELECT * FROM dbo.nomeTabela;
    ```

- Como deletar uma tabela
  ```
  ```

- Como usar o ROLLBACK
  ```
  ```


### 5. Referências

- [Comandos Básicos SQL.](https://www.alura.com.br/artigos/como-utilizar-os-comandos-insert-select-update-e-delete-em-sql#:~:text=Para%20mudar%20dados%20de%20uma,sejam%20alteradas%20todas%20as%20linhas.)
  
- [Exemplos práticos SQL.](https://www.sqlshack.com/learn-sql-sql-script/)

- [INNER JOIN e LEFT JOIN.](https://www.sqlshack.com/learn-sql-inner-join-vs-left-join/)

- [Como criar uma Tabela Temporária SQL.](https://www.freecodecamp.org/news/sql-temp-table-how-to-create-a-temporary-sql-table/) 