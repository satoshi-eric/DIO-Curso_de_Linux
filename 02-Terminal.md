# Conhecendo o terminal linux e seus atalhos

## Conhecendo o terminal e primeiros comandos

O terminal, shell ou console é uma linha de comando onde podemos executar programas específicos. Boa parte desses comandos é igual m todas as distros. Usaremos o Ubuntu para demonstrar.

Podemos usar o atalho CTRL+ALT+T para abrir o terminal.

Assim que entramos no terminal, entraremos na pasta pessoal por padrão, a pasta

~~~~bash
/home/<usuário>
~~~~

Podemos usar o comando 

~~~~bash
$ pwd
~~~~

para visualizar em qual diretório estamos.

Para listar o conteúdo de uma pasta, podemos usar o comando ls (list) 

~~~~bash
$ ls
~~~~

Para entrar em uma pasta, usamos o comando cd (change directory)

~~~~bash
$ cd <diretório>
~~~~

Podemos perceber que o cominho do diretório atual na linha de comando muda.

Para criar pastas, usamos o comando mkdir (make directory)

~~~~bash
$ mkdir <novo diretório>
~~~~

Podemos retroceder na hierarquia de diretório pelo diretório ..

~~~~bash
$ cd ..
~~~~

Também podemos acessar qualquer pasta do sistema pelo caminho absoluto usando o diretório raiz

~~~~bash
$ cd /
~~~~

Podemos usar variações de todos esses comandos que vimos anteriormente. Por exemplo, podemos usar variações do comando ls adicionando argumentos ao comando. 

~~~~bash
$ ls -l
~~~~

O comando acima lista os arquivos e pastas do diretório atual com informações adicionais.

Caso não saibamos utilizar um comando, podemos acessar o manual do comando usar o comando man (manual):

~~~~bash
$ man <comando>
~~~~

também podemos utilizar a opção help para mostrar como utilizar o comando

~~~~bash
$ <comando> --help
~~~~

Podemos sempre voltar para o diretório home utilizando o diretório ~

~~~~bash
$ cd ~
~~~~

Também podemos ver o histórico de todos os comandos utilizados no terminal usando o comando history

~~~~bash
$ history
~~~~

Podemos navegar entre os comandos do histórico usando as setas direcionais

Podemos utilizar o último comando do terminal pelo comando !!

~~~~bash
$ !!
~~~~



## Atalhos do terminal

Lista de atalhos :

* CTRL+C: Cancela o comando atual em funcionamento
* CTRL+Z: Pausa o comando atual, em primeiro ou segundo plano
* CTRL+D: Faz logout da sessão atual
* CTRL+W: Apaga uma palavra da linha atual
* CTRL+U: Apaga a linha inteira
* CTRL+R: Busca um comando recente
* !!: Repete o último comando
* exit: Sai do terminal

Continuando os comandos:

Temos o comando mv (move) que move ou renomeia um diretório ou arquivo:

~~~~~~bash
$ mv <nome antigo> <novo nome>
$ mv <antigo caminho> <novo caminho>
~~~~~~

Para criarmos arquivos vazios, usamos o comando touch

~~~~bash
$ touch <novo arquivo>
~~~~

Também podemos usar o comando cp (copy) para copiar um arquivo para outra pasta

~~~~bash
$ cp <arquivo> <caminho novo>
~~~~

Podemos usar o comando rm (remove) para remover arquivos

~~~~bash
$ rm <arquivo>
~~~~

Para remover um diretório, usamos os argumentos r

~~~~bash
$ rm -r <diretório>
~~~~



Para não precisarmos digitar um comando inteiro, podemos usar o TAB para autocompletar.

Podemos usar o comando clear para limpar a tela

~~~~bash
$ clear
~~~~

Podemos remover o diretório com o comando rmdir

~~~~bash
$ rmdir <diretório>
~~~~



