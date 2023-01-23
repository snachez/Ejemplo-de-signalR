# Ejemplo-de-signalR

Este es un proyecto dividido en dos el api y un frontend

# ApiSignalR

Se le implemento el Hub, modelo, controller. En program se inicio el servicio de signalr y la configuracion del cors y hub. 
Se descargo el nuget de microsoft.aspnetcore.signalr.

# FrontendSignalR

Se implemento las librerias de signalr client que estan ubicadas en wwwroot\lib\microsoft. Se implemento el mismo modelo. 
Se creo un component y su vista parcial llamada _Respuesta. Se creo un metodo en el controller llamado AgregarEmpleado. Se creo unos javascript en wwwroot\js.

# Gateway

Se descargo el nuget de MMLib.Ocelot.Provider.AppConfiguration, MMLib.SwaggerForOcelot, Ocelot. Se creo el archivo ocelot.json. Se modificio el appsettings con los host de la api de signal y el host del gateway. Se implemento una clase llamada MyDocumentFilter para eliminar de swagger una documentacion extra que sale por el swagger de ocelot. Se inicializo los servicios en el program

