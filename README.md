# Amarula IRC Botnet v1.0
<h4> Abacatch Version </h4>

Botnet client feito **Python 2.7** *(written in Python 2.7)* <br>
Testado em: **Windows XP, 8, 10**, *(tested on)*<br>
Escrito por: **Carlos Néri Correia** *(coded by)* <br>
Versão: **1.0** *(version)*

## Funções *(features)*
- Executar comandos shell *(shell command execution)* <br>
- Keylogger - Captura de teclas digitadas pelo cliente em tempo real *(real-time keylogging)* <br>
- Listar diretório atual do bot *(list current working directory)* <br>
- Listar todos os arquivos de um *diretorio (list all directory files)* <br>
- Obter ip local e externo do bot *(get local and WAN bot IP)* <br>
- Download de arquivos da web via HTTP *(HTTP web downloading)* <br>
- Upload de arquivos para servidor web via HTTP *(upload bot files to web server)* <br>
- Envio de logs para servidor remoto *(send logs to remote server)* <br>
- Deletar arquivos no BOT *(delete files)* <br>
- Executar arquivos no BOT *(run files)*
- Persistência *(persistence)*<br>

## Instalação *(install)*
    $ pip install requests
    $ pip install pypiwin32

**Download pyHook**
https://sourceforge.net/projects/pyhook/

## Configuração *(setup)*
Algumas variáveis precisarão ser definidas ou alteradas, para que a conexão com o IRC seja feita corretamente: 

**VARIÁVEIS:***(variables)* <br>

***ircServer*** *(sets IRC server address)*
Endereço do servidor IRC ao qual o BOT irá se conectar. <br>

***ircPwdCha*** *(sets IRC channel password)*
Define o password do canal IRC ao qual o bot irá se conectar. <br>
Caso o canal não possua password, deixar em branco ("") <br>
Importante setar um password no canal para que outras pessoas não entrem e possam controlar os seus bots.

***ircChanne*** *(sets IRC channel)*
Canal do IRC ao qual o bot irá se conectar. <br>
É interpretando as mensagens enviadas para o canal que o BOT irá executar os comandos internamente no cliente.

***botPass*** *(sets password to activate and connect to the BOTS)*
Define um passord para se ativar, conectar e controlar os bots no canal <br>

***botAdmi=*** *(Admin Name - NOT OBLIGATORY)*
Define um nome pelo qual os zumbis te chamarão
Não é obrigatório.

***urlUpload*** *(Upload page on remote server)*<br>
Página de upload no servidor remoto, para a função de envio remoto. <br>
Será criado um arquivo *capt-(nome do PC).txt* na mesma pasta de upload.php, no servidor.  

***ldir*** *(sets local directory, dropping directory)*<br>
Diretório local, onde será salvo o arquivo de log. <br>
Diretório para o qual o .exe se copia para ser executado em persistência quando a máquina reiniciar.



**COMPILAR** *(compile)*

    $ pyinstaller -w WinService.py --onefile
    

mail me: hackerama@protonmail.com

