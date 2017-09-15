## API Proxy Pseudo Code ##

_Inicializa a classe api_proxy_
> Initialize class api_proxy
	
	_Define o endpoint de conexão e alguns parâmetros iniciais_
	Set protected endpoint = "Link";
	Set protected ratelimit = 3600;
	Set protected rateremaining = 3587;

	_chama o método conectar informando o endpoint e os dois demais parâmetros_
	call method connect(endpoint, ratelimit, rateremaining);


_finaliza a classe api_proxy_
> End class api_proxy


_Inicializa o método connect_
_Defineo valor inicial dos parâmetros_
> Initialize class connect(string _endpoint = '', int _ratelimit = 3600, int _rateremaining = 3587)


_finaliza a classe connect_
> End class connect