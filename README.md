\# Máquina de Rube Goldberg — Simulación en Unity



\## Descripción del proyecto



Este proyecto consiste en el diseño y la simulación de una máquina de Rube Goldberg mediante el motor de videojuegos Unity 6.6.



La máquina utiliza una secuencia de elementos tridimensionales que interactúan mediante la gravedad, el movimiento sobre planos inclinados y las colisiones entre cuerpos rígidos, hasta completar una acción final: derribar un conjunto de pinos de bolos.



El propósito de la actividad es explorar el comportamiento de las leyes de la física dentro de un entorno virtual y comprender cómo un movimiento inicial puede desencadenar una serie de acciones interdependientes.



\## Objetivo



Diseñar e implementar una máquina de Rube Goldberg que permita observar y analizar fenómenos físicos mediante una simulación tridimensional desarrollada en Unity.



\## Secuencia de funcionamiento



\*\*Etapa 1. Movimiento inicial\*\*



Una esfera desciende por una rampa inclinada debido a la acción de la gravedad.



\*\*Etapa 2. Reacción en cadena\*\*



La esfera entra en contacto con el primer dominó, provocando su caída. El impacto se transmite sucesivamente entre cuatro fichas.



\*\*Etapa 3. Activación del siguiente mecanismo\*\*



El último dominó interactúa con un bloque activador, dando continuidad al mecanismo que involucra una segunda esfera.



\*\*Etapa 4. Segundo desplazamiento\*\*



La segunda esfera se desplaza por otra rampa inclinada hacia la zona final de la máquina.



\*\*Etapa 5. Acción final\*\*



La esfera entra en contacto con los pinos de bolos y provoca su caída mediante colisiones físicas.



\## Principios físicos aplicados



| Principio | Aplicación en la simulación |

|---|---|

| Gravedad | Provoca el descenso de las esferas y la caída de los elementos que pierden estabilidad. |

| Energía potencial gravitatoria | Está asociada con la altura inicial de las esferas. |

| Energía cinética | Se manifiesta durante el movimiento de los cuerpos. |

| Colisiones | Permiten transmitir movimiento entre esferas, dominós, bloques y pinos. |

| Fricción | Influye en el deslizamiento y el movimiento de los objetos sobre las superficies. |

| Rotación y equilibrio | Explican el comportamiento de los dominós y los pinos durante su caída. |



La simulación permite observar transformaciones y transferencias de energía, aunque no representa un sistema ideal sin pérdidas.



\## Componentes utilizados en Unity



\- \*\*Transform:\*\* define la posición, orientación y escala de los elementos.

\- \*\*Rigidbody:\*\* incorpora el comportamiento de los cuerpos rígidos bajo la acción de fuerzas y colisiones.

\- \*\*Collider:\*\* define las superficies utilizadas para detectar y resolver contactos físicos.

\- \*\*Physics Material:\*\* permite ajustar propiedades como la fricción y el rebote.

\- \*\*Mesh Renderer:\*\* permite visualizar los objetos y sus materiales.



\## Herramientas y tecnologías



\- Unity 6.6 (6000.6.6f1)

\- Motor de física 3D de Unity

\- Modelos tridimensionales y materiales

\- Git y GitHub para control de versiones



\## Cómo abrir el proyecto



1\. Clonar o descargar el repositorio.

2\. Abrir Unity Hub.

3\. Seleccionar \*\*Add project from disk\*\*.

4\. Elegir la carpeta raíz del proyecto descargado.

5\. Abrirlo con la versión de Unity correspondiente.

6\. Abrir la escena principal desde `Assets/Scenes`.

7\. Presionar \*\*Play\*\* para ejecutar la simulación.



La primera apertura puede tardar mientras Unity importa recursos y restaura los paquetes necesarios.



\## Resultados



Se desarrolló una simulación tridimensional que integra rampas, esferas, dominós, un bloque activador y pinos de bolos.



Durante las pruebas se realizaron ajustes de posición, dimensiones, colisionadores y propiedades físicas para lograr una secuencia de funcionamiento en la que los movimientos de unos elementos provocan la activación de los siguientes.



El resultado permite observar una reacción en cadena que culmina con la caída de los pinos.



\## Demostración



El funcionamiento de la máquina se documentó mediante una grabación de la simulación realizada en Unity.



El video de demostración puede incorporarse a la entrega académica o enlazarse desde este repositorio.



\## Conclusión



El desarrollo de la máquina permitió comprender la importancia de la gravedad, la energía, las colisiones y la configuración de los cuerpos rígidos dentro de una simulación tridimensional.



La actividad también evidenció que el funcionamiento de una reacción en cadena depende de la correcta disposición espacial de los elementos y de sus propiedades físicas.



Unity constituye un entorno útil para experimentar con estos fenómenos, observar sus efectos y realizar ajustes mediante pruebas sucesivas.

