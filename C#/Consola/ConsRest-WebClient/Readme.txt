*/////////////////////////////////////////*********************

Agregado de Librerias(DLL)

1.System.Net: En este espacio de nombre se encuentran las clases "HttpWebRequest-HttpWebResponse" que se usan para Petici�n-Respuesta respectivamente del Recurso Rest expuesto en el servidor de SunApiPeru.

2.Newtonsoft.Json: En este espacio de nombre se encuentra la clase "JsonConvert" que es la encargada de deserializar la cadena Json que devuelve el servicio a Objetos "Json".Esta libreria hay que descagarla


Realizando Petici�n del Servicio

1.WebClient
-client.DownloadString("https://sunapiperu.com/api/contribuyente?nombre=bar restaurant");

Deserializar Respuesta Json
-JsonConvert.DeserializeObject(body); // convertimos la cadena json en objetos json


Luego de Obtener los resultados de la deserializacion del json a objetos C#, mostramos el resultado en la consola.Esperamos que les sirva el ejemplo

Equipo:SunApiPeru*******************//////////////////////////////

