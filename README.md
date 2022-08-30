# WIKI_Publica
WIKI repo publico


Listado de Grandes Clientes  Regimen MiPYME

https://servicioscf.afip.gob.ar/facturadecreditoelectronica/Listado-RFCE-Mi-PyMe.asp


![Imagen ejemplo de AFIP Regimen Grandes CLientes](/images/GrandesClientes.JPG "Ejemplo de Filtrado")

http://www.afip.gov.ar/afip/resol170204.html

ANEXO I RESOLUCION GENERAL N°1702
DATOS Y CARACTERISTICAS DEL SISTEMA DE IDENTIFICACION DE DATOS DENOMINADO "CODIGO DE BARRAS"
A) DATOS
Datos que deberá contener el sistema de identificación de datos denominado "Código de Barras":
- C.U.I.T. (Clave Unica de Identificación Tributaria) del emisor (11 caracteres).
- Código de tipo de comprobante (2 caracteres).
- Punto de venta (4 caracteres).
- Código de Autorización de Impresión (14 caracteres).
- Fecha de vencimiento (8 caracteres).
- Dígito verificador (1 carácter).
 RUTINA PARA EL CALCULO DEL DIGITO VERIFICADOR

Se considera para efectuar el cálculo el siguiente ejemplo:
01234567890

Etapa 1: Comenzar desde la izquierda, sumar todos los caracteres ubicados en las posiciones impares.
0 + 2 + 4 + 6 + 8 + 0 = 20

Etapa 2: Multiplicar la suma obtenida en la etapa 1 por el número 3.
20 x 3 = 60

Etapa 3: Comenzar desde la izquierda, sumar todos los caracteres que están ubicados en las posiciones pares.
1 + 3 + 5+ 7 + 9 = 25

Etapa 4: Sumar los resultados obtenidos en las etapas 2 y 3.
60 + 25 = 85

Etapa 5: Buscar el menor número que sumado al resultado obtenido en la etapa 4 dé un número múltiplo de 10. Este será el valor del dígito verificador del módulo 10.
85 + 5 = 90

De esta manera se llega a que el número 5 es el dígito verificador módulo 10 para el código 01234567890

Siendo el resultado final:
012345678905

