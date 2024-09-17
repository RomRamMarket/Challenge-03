# Challenge-03 ¡Viva México!



<h2>Reflexión </h2>
<p>ESTA ES LA REFLEXION.</p>



<h2>LORE</h2>4


<h2>Preparando Herramientas de trabajo.</h2>

<h3>Comenzamos Instalando el Paquete ProBuilder que nos facilitará la creación de la pirámide.</h3>

<image
  src="CHALLENGEO3/PKmanager.png"
  width = 90%
  height = 90%>

  <p>Nos aseguramos de buscar bajo Unity Registry e instalamos ProBuilder</p>

<image
  src="CHALLENGEO3/ProBuilder.png"
  width = 90%
  height = 90%>



<h2>Abriendo ProBuilder Window</h2>
<p>Una vez instalado ProBuilder abrimos el "probuilder window". Seleccionamos Tools>Probuilder>Probuilder Window </p>

<image
src="CHALLENGEO3/PBwindow.png"
width = 90%
height = 90%>



<h2>Creando un nuevo plano</h2>
<p> Para crear un nuevo plano que luego modificaremos en una pirámide seleccionamos new shape y elegimos plane. Los height cuts y width cuts hacen referencia a en cuantos "pedazos" va a estar dividido el plano. Nosotros instamos por decidir los cuts entre 10 o 12, ambos numeros podian ser favorables. Luego para decidir en donde iba a estar situado el plano deslizamos el click por el campo.  </p>



  <image
  src="CHALLENGEO3/PLANO.png"
  width = 90%
  height = 90%>



<h2>Vamos seleccionando las áreas del plano que queremos levantar para ir dandole la forma de pirámide.</h2>
<p> Para escoger las caras que queremos levantar seleccionamos el botón circulado en azul. Luego junto con click + shift nos permite seleccionar varias caras a la vez.</p>

  <image
  src="CHALLENGEO3/SelectCenter.png"
  width = 90%
  height = 90%>



<h2> Agrandar parte del plano </h2>

<p> Una vez seleccionada el área en cuestión con el paso anterior, utilizando la herramienta de escalar, levantamos el área. </p>

  <image
  src="CHALLENGEO3/expandirPlano.png"
  width = 90%
  height = 90%>


<h2> Continuar agrandando otras partes de la pirámide  </h2>

<p> Seguimos la misma metodología para seleccionar las aristas que queremos seguir levantando</p> 

  <image
  src="CHALLENGEO3/SeleccionarAristas.png"
  width = 90%
  height = 90%>


<p> En esta vez para no hacerlo bajo un medidor subjetivo, utilizaremos "extrude faces". Extrude faces nos permite una vez seleccionamos las caras a levantar, levantarlas una cierta medida que le especificamos, para luego si queremos alinear otras áreas del plano podamos hacerlo sin mayor complicación </p>


  <image
  src="CHALLENGEO3/extrudeAristas.png"
  width = 90%
  height = 90%>


  <image
  src="CHALLENGEO3/SelectAristas2.png"
  width = 90%
  height = 90%>



<h2>Resultado temporero de pirámide escalonada</h2>
<image
  src="CHALLENGEO3/Piramide.png"
  width = 90%
  height = 90%>








<h2>Creando Terreno</h2>

<p>Para crear un terreno utilizamos game 3d object similar a como creamos una esfera, cubo, cilindro etc. </p>

<image
  src="CHALLENGEO3/CreateTerrain.png"
  width = 90%
  height = 90%>



  <h2>Ajustamos las dimensiones del terreno</h2>
  <p>Para este challenge no habían dimensiones específicas, pero optamos por seguir unas muy parecidas a las del Challenge anterior.</p>

<image
  src="CHALLENGEO3/TerrainD.png"
  width = 90%
  height = 90%>


<image
  src="CHALLENGEO3/TerrainD2.png"
  width = 90%
  height = 90%>

<image
  src="CHALLENGEO3/TerrainD3.png"
  width = 90%
  height = 90%>





<h2>Preparando herramienta para crear montañas </h2>
<p> Decidimos crear montañas a nuestro terreno para que no se viera como un terreno solo con una pirámide. Las montañas nos van a ayudar a dar un poco más de concepto del ambiente. Para hacer montañas hay que elegir las brocha y su tamaño.</p>


<image
  src="CHALLENGEO3/montanas1.png"
  width = 90%
  height = 90%>



<h2>Creando montañas</h2>

<p>Una vez configuramos nuestra herramienta para crear montañas procedemos a crearlas. Pasando la brocha presionando click haremos abultaciones al terreno y si presionamos shift + click crearemos hoyos. Esta parte es un poco subjetiva pues depende de cuantas montañas quieras crear y en que lugares. En nuestro caso decidimos crear montañas en los bordes para dejar un buen espacio llano en el centro donde irán tanto la pirámide como los animales que poblarán el lugar. No obstante tambien creamos ligeras abultaciones en el terreno para que no fuera completamente liso y tuviera un tanto de textura arrugada.</p>

<image
  src="CHALLENGEO3/montanas2.png"
  width = 90%
  height = 90%>


<h2>Importando Texturas</h2>

<p>Para poder poner texturas en el terreno, primero hay que decidir qué texturas utilizaremos. Una vez decidimos que texturas utilizaremos nos aseguramos que estén guardadas en una carpeta dentro de la carpeta de Scenes. En nuestro caso decidimos elegir dos texturas, una similar a un cesped seco, y otra un poco más verde, para combinarlas y crear un buen efecto para la grama. (añadir fotos de las texturas). Las texturas depende ser formato png o jpeg</p>

<image
  src="CHALLENGEO3/importTextures.png"
  width = 90%
  height = 90%>


<h2> Añadiendo texturas</h2>
<p>Para añadir las texturas al terreno seleccionamos Paint Textures y luego Edit terrain layers y luego Create Layer. Ahi nos apareceran nuestras texturas antes guardadas y las seleccionamos ambas. La primera se va a aplicar al terreno inmediatamente, pero lo hará de una forma poco natural.</p>

<image
  src="CHALLENGEO3/AddTexturas.png"
  width = 90%
  height = 90%>



<h2>Ajustando Texturas</h2>
<p>Para ajustar la poca naturalidad con la que las texturas se aplican, vamos a Tilling settings y ajustamos los valores a unos que dependiendo de la textura puedan tener mejor relacion de aspecto con nuestro terreno. </p>
<image
  src="CHALLENGEO3/ajustandoTextura.png"
  width = 90%
  height = 90%>


<h2>Mezclando texturas</h2>
<p>Una vez ajustamos las texturas, seleccionamos la textura secundaria y con la brocha vamos dando click donde queremos implantarla </p>

<image
  src="CHALLENGEO3/MezclandoTexturas.png"
  width = 90%
  height = 90%>




<h2>Suavizando terrenos (dos fotos de before and after) </h2>

<p>Si notamos ahora con las texturas puestas nuestras montañas no tienen una forma muy adecuada, parecen mnuy puntiagudas en algunas lados y puede ser una imperfección que puede mejorarse. Utilizando Smooth Height y seleccionando la brocha podemos ir corrigiendo esas imperfecciones poco a poco.</p>



<image
  src="CHALLENGEO3/BeforeSmooth.png"
  width = 90%
  height = 90%>

<image
  src="CHALLENGEO3/AfterSmooth.png"
  width = 90%
  height = 90%>



<h2>Creando casetas de arriba de la pirámide</h2>
<p>Para crear las casetas de arriba de la piramide vamos a utilizar nuevamente probuilder. Similar a como creamos el objeto del plano que se convirtió en la pirámide, ahora crearemos un cubo. Utilizando subdivide Object dividiremos el cubo de manera que tenga 16 sub caras en cada cara. (4x4x4) </p>

<image
  src="CHALLENGEO3/DividiendoCubo.png"
  width = 90%
  height = 90%>




<h2>Dando forma a la caseta</h2>

<p>Para poder crear la abultacion del cuadrado seleccionamos las esquinas de las caras centrales. (la herramienta circulada en azul nos permite seleccionar las aristas que queramos con shift + click) </p>

<image
  src="CHALLENGEO3/SelectEsquinas.png"
  width = 90%
  height = 90%>


<h2>Haciendo forma de caseta</h2>

<p>Con la herramienta de cambiar de posición elevamos las aristas seleccionadas hacia arriba para crear una forma parecida a la deseada.</p>



<image
  src="CHALLENGEO3/haciendoCaseta.png"
  width = 90%
  height = 90%>



<h2>Modificando un poco la forma</h2>

<p>Para que no parezca tan triagnular seleccionamos las esquinas de las caras del centro (la herramienta circulada en azul te permite seleccionar las esquinas que deseas con shift + click) y las alargamos hacia al frente y hacia atras 
 para ajustar su forma con respecto a esos lados.</p>

<image
  src="CHALLENGEO3/AlargarPuntos.png"
  width = 90%
  height = 90%>







  <h2>Duplicando Casetas</h2>

  <p>Una vez estamos satisfechos con la forma de las casetas, damos click derecho y duplicate para duplicar la caseta antes hecha.</p>


<image
  src="CHALLENGEO3/Duplicate.png"
  width = 90%
  height = 90%>


<h2>Resultado preliminar de las casetas</h2>

<image
  src="CHALLENGEO3/Casetas.png"
  width = 90%
  height = 90%>










