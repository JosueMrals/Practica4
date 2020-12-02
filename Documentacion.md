# Practica 4 - Construye tu primera aplicacion Android

## I. Android Studio y Mi primer Hola Mundo
<img src="medios\1.PNG"/>

## 1.1: Instalación de Android Studio

> *Verifique que ya cuente con el JDK de Java en cualquier versión*
<img src="medios\2.png"/>

> *Verifique la ubicación de la instalación del SDK en Android Studio*
<img src="medios\2.PNG"/>

> *Verifique que en Android Studio este seleccionada la versión del JDK instalada en su máquina.*
<img src=""/>

## 1.2: Crear la aplicación Hello World

> *Estando en la ventana principal de Bienvenido a Android Studio, haga clic en Iniciar un proyecto de Android Studio.*
<img src="medios\4.jpg"/>

> *Según la versión, es posible que primero seleccione la plantilla, entonces seleccione una plantilla Empty Activity en el panel correspondiente a Phone y Tablet.*
<img src="medios\5.jpg"/>

> *En la ventana de Configurar su proyecto, escriba Hello World para el nombre de la aplicación*
<img src="medios\6.jpg"/>

> *Compruebe la ubicación predeterminada del proyecto en donde desea almacenar su aplicación, en el caso de que esa no sea su ubicación preferida, puede cambiarla.*
<img src="medios\7.jpg"/>

> *Si no tiene pensado publicar la aplicación, puede dejar el nombre del paquete predeterminado.*

> *En las nuevas versiones se elige Kotlin como el lenguaje de programación predeterminado, en el caso de que no le aparezca seleccionado, establezca Kotlin.*
<img src="medios\8.jpg"/>

> *Indique que porcentaje de dispositivos usan la API nivel 19 y cuales son sus características que incluye según el apartado Help me choose.*
<img src="medios\9.jpg"/>

Esta api corre en aproximadamente el 98,1% de los dispositivos. Tiene caracteristicas como:

+ Framework de impresión
  + Impresión de contenido genérico
  + Impresión de imágenes
  + Compilación de servicios de impresión
+ Proveedor de SMS
+ Redes inalámbricas y conectividad
  + Emulación de tarjeta de host
  + Modo de lector NFC
  + Transmisores infrarrojos
+ Contenido multimedia
  + Reproducción adaptable
  + Marcas de tiempo de audio a pedido
  + Lector de imágenes de superficie
  + Medición de picos y RMS
  + Amplificador de volumen
  + Controladores remotos
  + Calificaciones desde controladores remotos
  + Subtítulos opcionales
+ Animación y gráficos
+ Escenas y transiciones
  + Pausa del animador
  + Mapas de bits reutilizables
+ Contenido del usuario
  + Framework de acceso a almacenamiento
  + Acceso a almacenamiento externo
  + Adaptadores de sincronización
+ Entrada del usuario
  + Eventos de sensores por lotes
  + Identidades de los controladores
+ Interfaz de usuario
  + Barras de sistema translúcidas
  + Duplicación de elementos de diseño para diseños RTL
  + Accesibilidad
+ Permisos para apps
+ Funciones del dispositivo

> *De clic en finish, y espere que gradle sincronice todas las librerías necesarias para su aplicación, esto puede tardar un momento, sea paciente.*

> *Cada vez que inicia un proyecto le lanza un consejo del día, tome una captura del consejo que le salió* 

## Aparece el editor de Android Studio

> *Haga clic en la pestaña activity_main.xml para ver el editor de diseño*
<img src="medios\10.jpg"/>

> *Haga clic en la pestaña Diseño del editor de diseño, si aun no está seleccionada, para mostrar una representación gráfica del diseño como se muestra a continuación.*
<img src="medios\11.jpg"/>

> *Haga clic en la pestaña MainActivity.kt o MainActivity.java*
<img src="medios\12.jpg"/>

## Explore el proyecto en el panel Android

> *Si aún no está seleccionado, haga clic en la pestaña Proyecto en la columna de la pestaña vertical en el lado izquierdo de la ventana de Android Studio. Aparece el panel Proyecto. Explore todos sus directorios.*
<img src="medios\13.jpg"/>

## Explore la carpeta Gradle Scripts

> *La primera vez que se crea un proyecto de aplicación, el panel Proyecto > Android aparece con la carpeta Scripts de Gradle*
<img src="medios\14.jpg"/>

> *Si la carpeta Scripts de Gradle no está expandida, haga clic en el triángulo para expandirla.*
<img src="medios\15.jpg"/>

> *Busque el archivo build.gradle **(Project: Hello_World)**.*
<img src="medios\16.jpg"/>

> *Busque el archivo **build.gradle(Module:app)**.*
![Imagen](/medios/16.jpg)