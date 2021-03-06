# Relatório: Prática com o Protoloco TOR

Para seguir o tutorial e realizar a atividade proposta, foi necessário fazer a instalação do tor e tor-browser, através dos comandos:

> sudo add-apt-repository ppa:webupd8team/tor-browser

> sudo apt-get install tor-browser

>sudo apt-get install tor

![](https://github.com/davicedraz/security/blob/master/atividades_praticas/tor/screenshots/instalacao.JPG?raw=true)

Após isso, com o tor devidamente instalado na máquina Linux, foi possível acessar os sites da "Deep Web" através do Tor Browser.

![](https://github.com/davicedraz/security/blob/master/atividades_praticas/tor/screenshots/buscador.JPG?raw=true)

Como solicitado, o arquivo 'torrc' foi modificado para inserir as restrições de países que não serão considerados  como relays, ou seja, que serão ignorados como rota.

> ExitNodes {br},{ug},{kp},{ie}

Resultando em um novo circuito, por exemplo, de acesso até o site duckduckgo.com:

![](https://github.com/davicedraz/security/blob/master/atividades_praticas/tor/screenshots/exclude_result.JPG?raw=true)

Por fim, para confirmar o anonimato, um site de tracking de IP foi acessado para indicar a localização aproximada a partir do IP fornecido.

![](https://github.com/davicedraz/security/blob/master/atividades_praticas/tor/screenshots/anonimo.JPG?raw=true)


Em linhas gerais, o tutorial é bem simples, acredito que poderia ter mais comandos para facilitar segui-lo passo-a-passo. Tive que pesquisar e tirar dúvidas cruciais em relação ao protocolo, processo de instalação e modificação do arquivo 'torrc'. Essas informações poderiam estar presentes no tutorial. Não tive dificuldades em cumprir com as atividades propostas e achei muito interessante todo o background que envolve o Tor Project. Aprendi bastante (antes eu achava erroneamente que o Tor era um navegador).
