## API Proxy Pseudo Code ##

* Inicializa a classe api_proxy
> Initialize class api_proxy
	
	* Define o endpoint de conexão e alguns parâmetros iniciais
	Set protected endpoint = "Link";
	Set protected ratelimit = 3600;
	Set protected rateremaining = 3587;

	* chama o método conectar informando o endpoint e os dois demais parâmetros
	call method connect(endpoint, ratelimit, rateremaining);


* finaliza a classe api_proxy
> End class api_proxy


* Inicializa o método connect
* Defineo valor inicial dos parâmetros
> Initialize class connect(string endpoint = '', int ratelimit = 3600, int rateremaining = 3587)


* finaliza a classe connect
> End class connect