---
label: IRC
author:  
  name: "Duck"
  link: https://github.com/anotherduckling
  avatar: https://avatars.githubusercontent.com/u/57977673?v=4
---

# IRC E XDCC

>IRC é a sigla de Internet Relay Chat. É um protocolo de bate-papo em tempo real que permite que as pessoas se comuniquem umas com as outras em salas de bate-papo on-line. O IRC existe desde o final da década de 1980 e ainda é usado atualmente, embora tenha sido substituído em grande parte por tecnologias de bate-papo mais recentes, como o Discord.

>O XDCC é um protocolo de compartilhamento de arquivos usado com frequência no IRC. XDCC significa "eXtended DCC" e permite que os usuários enviem e recebam arquivos por meio de transferências diretas de cliente para cliente (DCC). Normalmente, isso é feito usando um bot, que atua como servidor de arquivos e gerencia as transferências de arquivos. O XDCC tem sido usado há muitos anos como uma forma de compartilhar arquivos, mas tornou-se menos popular ao longo do tempo devido ao surgimento de outras tecnologias de compartilhamento de arquivos.


# Primeiros passos
1. Instale um [**IRC Client**] (#irc-client) em seu dispositivo.
2. Acesse uma [**XDCC Packlists**](#xdcc-packlists) e pesquise seu conteúdo
3. Clique no resultado da pesquisa para ver a mensagem de comando 
!!!info
Comando padrão do XDCC `/msg [nome do bot] xdcc send #[número do pacote]`
!!!
4. Entre no servidor e no canal do bot e envie a mensagem de comando
5. Será exibida uma janela pop-up para o download.


## IRC Client
- [Revolution IRC](https://play.google.com/store/apps/details?id=io.mrarm.irc)		[!badge variant="ghost" text="Android"]
- [AndroIRC](https://play.google.com/store/apps/details?id=com.androirc&hl=en&gl=US)		[!badge variant="ghost" text="Android"]
- [hexchat](https://hexchat.github.io/)		[!badge variant="ghost" text="Windows"]
- [mIRC](https://www.mirc.com/)		[!badge variant="ghost" text="Windows"]
- [AdiIRC](https://adiirc.com/)	[!badge variant="ghost" text="Windows"]
- [KVIrc](https://github.com/kvirc/KVIrc/releases) [!badge variant="ghost" text="Windows"] [!badge variant="ghost" text="Linux"] [!badge variant="ghost" text="macOS"]
- [Irssi](https://irssi.org/)	[!badge variant="ghost" text="Linux"]
- [WeeChat](https://weechat.org/)	[!badge variant="ghost" text="Linux"] [!badge variant="ghost" text="macOS"]
- [LimeChat](https://apps.apple.com/us/app/limechat/id414030210) [!badge variant="ghost" text="macOS"]


## XDCC Packlists
- [**nibl**](https://nibl.co.uk/search)	[!badge variant="ghost" text="Anime"]
	- Server: `irc.rizon.net`
	- Porta: `6697`
	- Canal: `#nibl`
- [**subsplease**](https://subsplease.org/xdcc/) [!badge variant="ghost" text="Anime"]
	- Server: `irc.rizon.net`
	- Port: `6697`
	- Canal: `#subsplease`
- [**animk**](https://animk.info/xdcc/) [!badge variant="ghost" text="Anime"]
	- Server: `irc.xertion.org`
	- Port: `6697`
	- Canal: `#MK` or `XDCCLeech`
- [**XDCC EU**](https://www.xdcc.eu/)	[!badge variant="ghost" text="Geral"]
- [**SunXDCC**](https://sunxdcc.com/)	[!badge variant="ghost" text="General"]

!!!light Tanto o **XDCC EU** quanto o **SunXDCC** não têm um único canal de bot. Eles mencionam o servidor e o endereço do canal no resultado da pesquisa.
!!!

!!!info XDCC EU
1. Clique no botão ℹ️
2. Entre no servidor e no canal do bot
3. Copie e envie o comando do bot no canal
    ![XDCC EU](/static/ss/irc/xdcceu.png)
!!!
!!!info SunXDCC
1. Entre no servidor e no canal do bot. 
2. Faça o comando do bot de acordo com o formulário padrão. Para esta captura de tela, o comando do bot será `/msg [FutureBot]-[C21] xdcc send #530`
	![SunXDCC](/static/ss/irc/sunxdcc.png)
!!!

## Download em lotes

- `/msg [botname] XDCC BATCH [a]-[b]` → Solicita pacotes com números de a a b, incluindo a e b, do bot.
- `/msg [botname] XDCC BATCH [a],[b],[c]` → Solicita pacotes com os números [a],[b] e [c] do bot.
- `/msg [botname] XDCC BATCH [a]-[b] [password]` → Solicita pacotes com senha com números de a a b, incluindo a e b, com a senha "password" do bot.
- `/msg [botname] XDCC BATCH [a],[b],[c] [password]` → Solicita pacotes com os números [a],[b] e [c], com a senha "password" do bot.
- `/msg [botname] XDCC BATCH [a],[b],[c]-[d]` → Solicita pacotes com os números a, b e c até d do bot. (ou seja, você pode combinar os dois métodos para dizer qual conjunto de pacotes você deseja)

!!!light Mais comandos estão [**aqui**] (https://wiki.xertion.org/w/XDCC_Commands).
!!!