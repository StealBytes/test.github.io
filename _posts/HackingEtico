---
layout: post
author: Hacking Etico
---

			Recopilacion de informacion de manera pasiva 
				
	• Osint
	• Google Dorks
	• Informacion almacenado en lugares publicos

La recopilacion de informacion pasiva se utiliza para evitar afectar a la infraestructura que ya esta en produccion, esta recopilacion se utiliza normalmente en conjunto con otros tipos de recopilacion, este tipo de recopilacion hay que aplciar criterio ya que pueede ser obsoleta o falsa directamente


					Google Hacking

	• Site:udemy.com (hace referencia que todas las busquedas sean del dominio o sitios de udemy.com)
	• Filetype: robots.txt
	• "index of " / "chat/logs"
	• Filetype: sql (base de datos sql)
	• Filetype: ext sql (base de datos sql)
	• "index of " /"chat/logs"  site:agunsa.com (donde quizas se puede encontrar alguna base de datos con algunas contraseñas)
	• "index of " /"chat/logs"  site:agunsa.com (password|pass|paswd|pwd) (que contengan las palabras password, pass o paswd)
	• Inurl:index.php?=id (con esto podriamos modificar la peticion y hacer solicitudes sql)
	• Inurl:index.php?=id site:cramerlatam.com
	• Site:gov filetype:PDF allintitle: restricted
	
	
	
https://www.exploit-db.com/google-hacking-database?category=12


Aquí podemos buscar distintos dorks para encontrar info filtrada de alguna institucion, cambiando simplemente el nombre de dominio etc



Google Hacking: Comandos y Operadores Booleanos
Comandos principales Google Hacking

A continuación se muestran los comandos principales que podemos utilizar con Google. Hay que tener en cuenta que todos ellos deben ir seguidos (sin espacios) de la consulta que quiere realizarse:

define:término - Se muestran definiciones procedentes de páginas web para el término buscado.

filetype:término - Las búsquedas se restringen a páginas cuyos nombres acaben en el término especificado. Sobretodo se utiliza para determinar la extensión de los ficheros requeridos. Nota: el comando ext:término se usa de manera equivalente.

site:sitio/dominio - Los resultados se restringen a los contenidos en el sitio o dominio especificado. Muy útil para realizar búsquedas en sitios que no tienen buscadores internos propios.

link:url - Muestra páginas que apuntan a la definida por dicha url. La cantidad (y calidad) de los enlaces a una página determina su relevancia para los buscadores. Nota: sólo presenta aquellas páginas con pagerank 5 o más.

cache:url - Se mostrará la versión de la página definida por url que Google tiene en su memoria, es decir, la copia que hizo el robot de Google la última vez que pasó por dicha página.

info:url - Google presentará información sobre la página web que corresponde con la url.

related:url - Google mostrará páginas similares a la que especifica la url.  Nota: Es difícil entender que tipo de relación tiene en cuenta Google para mostrar dichas páginas. Muchas veces carece de utilidad.

allinanchor:términos - Google restringe las búsquedas a aquellas páginas apuntadas por enlaces donde el texto contiene los términos buscados.

inanchor:término - Las búsquedas se restringen a aquellas apuntadas por enlaces donde el texto contiene el término especificado. A diferencia de allinanchor se puede combinar con la búsqueda habitual.

allintext:términos - Se restringen las búsquedas a los resultados que contienen los términos en el texto de la página.

intext:término - Restringe los resultados a aquellos textos que contienen término en el texto. A diferencia de allintext se puede combinar con la búsqueda habitual de términos.

allinurl:términos - Sólo se presentan los resultados que contienen los términos buscados en la url.

inurl:término - Los resultados se restringen a aquellos que contienen término en la url. A diferencia de allinurl se puede combinar con la búsqueda habitual de términos.

allintitle:términos - Restringe los resultados a aquellos que contienen los términos en el título.

intitle:término - Restringe los resultados a aquellos documentos que contienen término en el título. A diferencia de allintitle se puede combinar con la búsqueda habitual de términos.

Operadores Booleanos Google Hacking

Google hace uso de los operadores booleanos para realizar búsquedas combinadas de varios términos. Esos operadores son una serie de símbolos que Google reconoce y modifican la búsqueda realizada:

" " - Busca las palabras exactas.

- - Excluye una palabra de la búsqueda. (Ej: gmail -hotmail, busca páginas en las que aparezca la palabra gmail y no aparezca la palabra hotmail)

OR (ó |) - Busca páginas que contengan un término u otro.

+ - Permite incluir palabras que Google por defecto no tiene en cuenta al ser muy comunes (en español: "de", "el", "la".....). También se usa para que Google distinga acentos, diéresis y la letra ñ, que normalmente son elementos que no distingue.

* - Comodín. Utilizado para sustituir una palabra. Suele combinarse con el operador de literalidad (" ").



								SHODAN y CENSYS

https://www.shodan.io/

https://www.censys.io


Buscador de direcciones IPS y analizando los puertos y servicios, brindandonos informacion valiosa para el recopilar informacion 



https://github.com/jakejarvis/awesome-shodan-queries#webcams 

Aquí podemos ver  camaras webs expuestas 


			Shodan: Comandos principales


		Comandos relevantes para Shodan

A continuación se presentan algunos de los filtros más relevantes para el uso de Shodan:

after: Only show results after the given date (dd/mm/yyyy) string

asn: Autonomous system number string

before: Only show results before the given date (dd/mm/yyyy) string

category: Available categories: ics, malwarestring

city: Name of the city string

country: 2-letter country code string

geo: Accepts between 2 and 4 parameters. If 2 parameters: latitude, longitude. If 3 parameters: latitude, longitude, range. If 4 parameters: top left latitude, top left longitude, bottom right latitude, bottom right longitude.

hash: Hash of the data property integer

has_ipv6: True/False boolean

has_screenshot: True/False boolean

server: Devices or servers that contain a specific server header flag string

hostname: Full host name for the device string

ip: Alias for net filter string

isp: ISP managing the netblock string

net: Network range in CIDR notation (ex.199.4.1.0/24) string

org: Organization assigned the netblock string

os: Operating system string

port: Port number for the service integer

postal: Postal code (US-only) string

product: Name of the software/product providing the banner string

region: Name of the region/state string

state: Alias for region string

version: Version for the product string

vuln: CVE ID for a vulnerability string




						WHOIS
						
						
Esuna herramienta para hacer consultas a la base de datos que tienen los registradores de dominios o direccion IP, en kali o parrot al escribir el sgte comando: 
	
	
	• Whois *nombre de dominio*.cl

Sirve para recabar informacion de alguna pagina web.



				Archive: analisis de info historica
				

Es una herramienta para recuperar informacion de algun github por ejemplo que alguna organización haya publicado, la pagina web que realiza esto es:

Lo que nos debemos quedar de esta pagina web es que podemos recabar informacion que antiguamente estaba publicado y podemos tener acceso a ella ya que son snpashots desde los inicio de alguna pagina web, podriamos buscar fotologs de alguien 

Web.Archive.org 


							TheHarvester
							

Es una herramienta que viene pre instalada en kali y parrot, tambien tiene un github
http://github.com/laramies/theHarvester 

Esta herramienta nos sirve para buscar informacion desde la consola de nuestro linux, con los siguientes parametros podemos ver informacion de algun domino de interes con una que elijamos nosotros con el parametro -h podemos ver el panel de ayuda de la herramienta

	• Harvester -h
	• Harvester -d udemy.com -b google -l 100 -f resultados.html  (-d dominio  -b fuente y -l limite de busquedas -f se exporta los resultados a xml y html ) para ver los resultados podriamos poner
	• Firefox resultados.html (nos abre el navegador con los resultados)
	
	
	
	
						Maltego
						
Es una herramienta que viene a suplir las carencias de theharvester, esta aplicación se abre directamente ya que contiene interfaz gráffica, esta aplicación contiene distintos transformadores o hubs, los cuales realizan querys, por ejemplo a shodan, esto quiere decir que tiene varios transformadores donde realizara  las consultas respectivas a distintas base de datos, los recomendados para instalar son:

	1. Have i pawned?
	2. Virustotal (pide apikey)
	3. socialLinks
	4. waybackmachine

Luego debemos crear un GRAFO, esto se hace de la sgte manera
	1. Pinchar parte superior izq en nwe
	• Podemos arrastrar entidades, las cuales estan al costado izq de la pantalla luego de desplegar el grafo, son entidades los cuales contienen distintos tipos de info  sobre los cuales podemos hacer consultas con los distintos tipos de transformadores, podemos utilizar nombres recolectados con las herramientas anteriores

	1. Podemos arrastrar una persona
	2. Organización

Luego dentro de la persona podemos buscar info con los transformadores 

Tambien podemos exportar el grafo en modo reporte 
	• Guardar el archivo
	• Crear la export
	• Abrir una terminal
	• Ir a la ruta del reporte
	• Abrirlo en firefox
	• Firefox reportemaltego.pdf


						Recon-ng
						
	• Github.com/lanmaster53/recon-ng

Esta viene incorporada en kali 
Con help podemos ver las opciones
Par que funcione bien hay que cargar modulos (transformadores parecido a los de maltego)

		○ Con el comando modules search podemos ver los modulos ya cargados (en recon-ng)
	
Para instalar modulos: 
	• Marketplace search  (buscamos los distitnos tipos de transformadores, buscadores)
	• Marketplace info recon/domains-contacts/whois_pocs ( se utiliza para ver lo que hace cada transformador) 
	• Marketplace install recon/domains-contacts/whois_pocs  (con este instalamos el transformador)
Para utilizar el modulo descargado
	• Modules load recon/domains-contacts/whois_pocs 
	•  con la tecla tab dentro de este modulo podemos ver las opciones y parametros que debemos colocar para utilizar de manera optima este modulo
	• Options list  nos da las opciones que debemos poner para utilizar el modulo
	• Options set udemy.com (seria un ejemplo de busqueda) 
	• Options con este parametro podriamos revisar que no falte ningun parametro adicional
	• Run con este parametro se ejecutaria la busqueda
	• En el caso de que nos encuentre un contacto o algo adicional, podemos revisar esas tablas con el parametro show
	• Show contacts

Para utilizar shodan
	• Marketplace install recon/companies-multi/shodan_org
	• En el caso de que la busqueda requiera una api key
	• Keys add shodan_api  y la clave
	• Option list (para ver las opciones)
	• Option set SOURCE cramerlatam.com (setiamos el objetivo)
	• Run (corremos el reconocimiento)
	• Con back volvemos para atrás
	• Makertplace install reporting/html (isntalamos el tipo de archivo para el reporte)
	• Modules load reporting/html  (cargamos el tipo de archivo)
	• Options  (para ver las opciones que nos da este modulo)
	• Con set cambialos las opciones (podemos poner nombre de cliente, de creador, etc)
	• Firefox ruta del archivo.html (con este comando podemos ver el reporte representado en html
