# IoTools Bluemix
App Mobile que enlaza los datos del acelerómetro del dispositivo móvil con el servico IoT Watson de bluemix a través de una App Node RED

### Esquema Node-RED

![](https://github.com/vicboma1/IoToolsBluemix/blob/master/assets/_ioToolsBlumix.png)

La solución se basa en un esquema de nodos que representa el binding del Acelerómetro del dispositivo en una sola gráfica a traves de Node RED.

La aplicación Mobile se llama [Internet of Things(IoT) Dashboard/Gateway - IoTool](https://play.google.com/store/apps/details?id=io.senlab.iotoolapp).

Las extensiones son las siguientes :
  * [Sensors](https://play.google.com/store/apps/details?id=io.senlab.iotool.serviceandroid)
  * [Watson cloud](https://play.google.com/store/apps/details?id=io.senlab.iotool.extension.ibmwatsoncloud)

### Dispositivo móvil
#### (Click en gif para ver video con la App Mobile + Dashboard NodeRED)

[![](https://github.com/vicboma1/IoToolsBluemix/blob/master/assets/_ioToolsBluemix.gif)](https://www.youtube.com/watch?v=wiuQ1-Mhpn8 "IoTools Mobile")

### Pasos a seguir 

1.   Copiar la ![Plantilla txt](https://raw.githubusercontent.com/vicboma1/IoToolsBluemix/master/assets/_ioToolsBluemix.txt) con "Control A" + "Control C"

2.   Ir al menú contextual de nuestra aplicación Node-RED

3.   Importar

4.   Clipboard

5.   Import Nodes -> "Control V" para pegar la template

6.   Aceptar pulsando el botón de "Import"

7.   Configura el nodo IBM IoT Input con la Api Key de tu Universidad.

8.   Para renderizar los componentes del dashboard necesitas instalar la dependencia "node-red-dashboard"

9.   Ir al menú contextual de nuestra aplicación Node-Red -> "Manage Palette" -> Install

10.  Escribimos -> "node-red-dashboard" para Web | "node-red-dashboard-es" para mobile


@Author: [Victor Bolinches Marin](https://github.com/vicboma1)  

@Documento Principal  [CoEValencia - Hackathon 2017](https://github.com/CoEValencia/Hackathon_2017)

