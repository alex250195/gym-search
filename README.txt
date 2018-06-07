Objetivo:
	- Desenvolver um aplicativo que busque a localiza��o atual do usu�rio e exiba/liste as academias pr�ximas a ele,
	em um raio, m�ximo, de 50km. E, por fim, quando selecionar uma das academias listadas, exibir a rota entre a
	localiza��o do usu�rio e a localiza��o da academia.

Aplicativo feito em Xamarin.Forms
	. Permite que eu gere assemblies nativos para Android, iOS e Windows (UWP)

Projeto criado em .Net Standard
	. Compilado e a unidade de reutiliza��o � o assembly

Padr�o de projeto MVVM
	. Estabelecer uma separa��o de responsabilidades e tornar o aplicativo mais f�cil de dar manuten��o.
	  Baseado em UI, � uma aplica��o do MVP, que � uma varia��o do MVC.
	  (http://netcoders.com.br/introducao-ao-mvvm)

Pacotes utilizados
	- Acr.UserDialogs = Mensagens em di�logos (popups)
	- Newtonsoft.Json = Serializa��o de deserializa��o de objetos
	- Plugin.Share = Compartilhar informa��o em canais de comunica��o
	- Xam.Plugin.Geolocator = Capturar localiza��o atual do usu�rio
	- Xam.Plugins.Forms.ImageCircle = Arredondar imagens
	- Xam.Plugins.Settings = Salvar configura��es em mem�ria
	- Xamarin.FFImageLoading = Carregar imagens da nuvem de maneira mais r�pida
	- Xamarin.FFImageLoading.Transformations = Estilos/efeitos em imagens
	- Xamarin.RangeSlider = Utilizar o componente slider

	Obs.: Todos os pacotes devem ser instalados em todos os projetos, para que funcione
		  perfeitamente em todas as plataformas.

==============================================================================

O que faria se tivesse mais tempo?
	. Implementa��o de testes automatizados e, consequentemente, utiliza��o
	  de CI (Continuos Integration) e CD (Continuos Delivery)
		- Utiliza��o do Visual Studio App Center para realizar tal tarefa
	. Finalizar os testes e implementa��es na plataforma iOS
		- Teoricamente j� est� tudo implementado, bastando realizar mais testes e implementar funcionalidades espec�ficas da plataforma
	. Acrescentar um cadastro e login de usu�rios mais detalhado e seguro
	. Fun��o de "Visitar Academia"
		- Envio de email para o usu�rio com todos os dados da academia
		- Notifica��o para o respons�vel pela academia, relatando interesse de usu�rios em visit�-la
	. Fun��o de "Academias favoritas"
		- Salvando as academias preferenciais do usu�rio
	. Fun��o de "Detalhar academia"
		- Exibindo mais informa��es sobre a academia, tais como:
			_ Valores da mensalidade
			_ Formas de pagamento
			_ Possui personal trainer?
			_ Se possiu personal trainer, qual o valor agregado?
			_ Melhor hor�rio para o usu�rio realizar atividades (de acordo com um perfil)
			_ Equipamentos disponibilizados pela academia

==============================================================================

Style Guide
	. Cor prim�ria: #22a8ff
	. Cor Secund�ria: #1d93e0
	. Cor de textos:
		- #000000
		- #FFFFFF
		- #22a8ff
	. Cor transparente: #dbecf7