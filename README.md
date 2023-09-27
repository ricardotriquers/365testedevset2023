# Objetivo

  

## Criar um portal web para consulta de clima 

  

	- Deverá ser utilizado:  

		Backend Java. 

		Frontend HTML/CSS/JS 

		obs: Podendo utilizar qualquer framework para back ou front nesta construção. 

  
	- Input: 

		Haverá um único campo para input de informações - CNPJ. 


	- Output: 
 

		Informações de clima 

			Temperatua no momento 

			Condição do tempo com texto e ícone referente 

			Temperatura Mínima e Máxima Prevista para o dia. 

  

				 

  

## Web Services de exemplo. 

  

	GET: https://brasilapi.com.br/api/cnpj/v1/45039237000114 

	GET: https://cep.awesomeapi.com.br/json/05424020 

	GET: https://weather.contrateumdev.com.br/api/weather?lat=-19.8218131&lon=-44.0094874 

		Exemplo icon: https://openweathermap.org/img/wn/11n@2x.png 

			Referencia: https://openweathermap.org/weather-conditions#Weather-Condition-Codes-2 

  

  

## Pré-Requisitos: 

- Java 8 

- applications.properties deverá estar disponível para alteração no diretório $CATALINA_HOME/webapps/$projeto/data/ do projeto 

- Os BaseURLs das requisições deverão estar declaradas na applications.properties (exemplo: consultaCep = https://cep.awesomeapi.com.br/json/) 

- Deverá ser implementado log4j2 relatando os seguintes itens: 

  trace 

		host solicitado 

		ip do solicitante 

		url das requisições 

		retorno das requisições 


	error 

		todas as exceptions geradas 

  

- Os arquivos de log deverão estar no diretório $CATALINA_HOME/webapps/$projeto/data/log/ 

  

- Deverá estar disponível para compilação utilizando o Maven para rodar no container Tomcat (.war) e o nome do projeto deverá ser (seu primeiro nome)(primeira letra do seu último sobrenome).war" exemplo: ricardot.war 

  

- Publicar o projeto em seu GitHub pessoal, disponibilizar um link e encaminhar para ricardotriques@365ti.com.br até o dia combinado no contato.
