SignalR y Reactive Extensions
=========

Este ejemplo tiene dos proyectos:

Un proyecto de consola que hace de servidor y usa una configuraci�n est�ndar de SignalR. Esta aplicaci�n recibe los mensajes a ser enviados.

Un proyecto de Windows Forms que se conecta al server y filtrar� los mensajes que vengan, haciendo uso del `IObservable` entregado por el m�todo [Observe] y los Reactive Extensions, y mostrar� solo aquellos que sean = "Hola".

[Observe]:https://msdn.microsoft.com/en-us/library/microsoft.aspnet.signalr.client.hubs.hubproxyextensions.observe%28v=vs.111%29.aspx