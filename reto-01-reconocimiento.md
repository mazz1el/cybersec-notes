# Exercise 1: ¿Cómo documetnar el reconocimiento de un dominio?  

Con el fin de poseer una documentación de los pasos ejecutados durante este procedimiento, es importante ir registrando cada uno de ellos. Por ello, he creado el siguiente documento con las informaciones básicas que podemos recolectar.

---

# Ejemplo de las herramientas y señalizaciones que podemos usar o documentar:

**Objetivo del reconocimiento:** Obtener información pública relevante sobre el dominio para identificar posibles vectores de ataque y realizar un análisis preliminar.

**Dominio analizado:** example.com

## Herramientas:
- whois
- nslookup
- dig
- theHarvester

**Realizar procedimiento correspondiente en la terminal de S.O. que esté utilizando y si es posible documentar los comandos utilizados. Por ejemplo:**
- whois example.com
- nslookup example.com
- dig example.com any
- theHarvester -d example.com -l 10 -b google

## Resultados por herramienta (ejemplo):

**whois example.com:**
- Registrado por: IANA
- Fecha de creación: 14 de agosto de 2020

**nslookup example.com:**
- Dirección IP: 93.184.216.34

**dig example.com any:**
- Respuestas DNS:
  - a.iana-servers.net
  - b.iana-servers.net

**theHarvester -d example.com -l 10 -b google:**
- Resultados encontrados: [Número de correos electrónicos, subdominios, etc.]

## Análisis:
Este dominio es de ejemplo y está reservado por IANA para ser usado en pruebas y documentación. No tiene servicios activos reales. Aun así, sirve para practicar comandos de reconocimiento básico.

## Análisis avanzado o conclusión:
Aunque el dominio analizado está registrado por IANA y es un dominio de prueba, los servidores DNS son públicos, lo que podría indicar la exposición de recursos importantes si fuera un dominio real.

## Notas de seguridad:
Realiza este tipo de ejercicios solo en dominios donde tengas permiso explícito para llevar a cabo las pruebas.


📅 Fecha: 28 de marzo de 2025

# Informaciones de que se pueden documentar (adicional):
- ¿Quién registró el dominio?
- ¿Qué servidores DNS usa?
- ¿Qué direcciones IP aparecen?
- ¿Qué información interesante viste?
