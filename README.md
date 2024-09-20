# Challenge-03 ¡Viva México!



<h1>Reflexión </h1>
<h2>Gabriel Romero</h2>
<h2>Sebastian Ramirez</h2>
<h2>Yadiel Mercado</h2>
<p>Encontré muy interesante la gran variedad de assets que se pueden conseguir en el store de Unity. Aun cuando estés en un “budget” y no quieras usar mucho dinero en assets, hay una gran variedad de opciones gratis y de costo muy bajo que se ven increíbles. Personalmente, me encantan las opciones “Low Poly” porque me gusta ver como los artistas hacen la naturaleza como árboles, piedras y plantas con pocos recursos así haciendo assets que no son pesados en términos de memoria pero aun con esa circunstancia se ven hermosos. Muchos juegos que me han encantado son una mezcla entre el estilo "low-poly" con shaders "Cel-shaded" y casi todos son juegos indies. Esto me empuja a esforzarme a entender y aprender cómo usar estos elementos para algún día crear mi propio videojuego.</p>



<h2>LORE</h2>
<p>Necuazomoc era una ciudad granjera de la civilizacion azteca. Aquí, vivía una comunidad de granjeros quienes cosechaban mucho maíz en sus terrenos grandes y habichuelas detrás de sus hogares. En su centro, había una gran pirámide hermosa donde hacían sacrificios a los dioses para así asegurar una cosecha maravillosa con que puedan intercambiar y tener sobras para alimentarse bien. Alrededor de esta pirámide, había un río rodeado por árboles que separaban la ciudad del suelo sagrado de la pirámide, nadie excepto los curas que llevaban sacrificios y aquellos “Llamados” pueden entrar a esta área. Estos “Llamados” usualmente eran personas escogidas por los dioses mismos para que entren a la pirámide, pero nadie sabía qué era lo que sucedió con estas personas, ya que al ir, nunca regresaban. </p>
	<p>Una noche, volvió a ocurrir una llamada divina por lo cual estos escogidos abandonaron sus vidas y caminaron hacia la tierra sagrada de la pirámide para servirle a sus dioses. Al llegar, la tierra en la que se paraban tembló horriblemente y llegaron unos vientos fuertes y ruidosos y al final, una luz tan brillante que dejó a todos los llamados ciegos e inconscientes.Al abrir sus ojos, estaban aún en la tierra sagrada de la pirámide, pero notaron que algo se sentía diferente en el aire. Intentaron dar la vuelta a la ciudad cuando se dieron cuenta que no había nada después del terreno de su pirámide, solo un bosque infinito de árboles grandes y verdes. Algunos salieron a verificar si encontraban un fin a este bosque infinito pero se rindieron luego de muchas horas y regresaron a la pirámide. Al regresar, se dan cuenta que los animales que antes estaban hechos de…origami.</p>
<p>Ningún llamado podía creer lo que estaban viendo: serpientes, aves, vacas, cerdos, conejos y gallos…hechos de papel?! Comenzó un pánico entre todos, ¿qué comerían ahora? No encuentran sus cosechas y los animales estaban hechos de papel! Aun con estos pensamientos, dos personas hambrientas fueron a perseguir uno de los gallos del área cual corrió hacia la pirámide y chocó contra su base lo cual causó otro gran terremoto. Al finalizar este terremoto, no hubo vientos ni luces, pero los llamados poco a poco se congelaron al mirar a la cima de su pirámide, donde ahora se encontraban dos gallos origamis gigantescos.
-”Hermano” se detuvo el primer gallo “Al parecer tenemos visitantes.”
-”Esto será MUY divertido” dijo mientras reía el segundo gallo.
-”Bienvenidos todos… a la tierra del Origami!”</p>


<h2>Preparando Herramientas de trabajo.</h2>

<h3>Comenzamos Instalando el Paquete <strong>ProBuilder</strong> que nos facilitará la creación de la pirámide.</h3>

<image
  src="CHALLENGE03/PKmanager.png"
  width = 80%
  height = 80%>

  <p>Nos aseguramos de buscar bajo <strong>Unity Registry</strong> e instalamos ProBuilder</p>

<image
  src="CHALLENGE03/ProBuilder.png"
  width = 80%
  height = 80%>



<h2>Abriendo ProBuilder Window</h2>
<p>Una vez instalado ProBuilder abrimos el "probuilder window". Seleccionamos Tools>Probuilder>Probuilder Window </p>

<image
src="CHALLENGE03/PBwindow.png"
width = 80%
height = 80%>



<h2>Creando un nuevo plano</h2>
<p> Para crear un nuevo plano que luego modificaremos en una pirámide seleccionamos <Code>New Shape</Code> y elegimos <code>Plane</code>. Los height cuts y width cuts hacen referencia a en cuantos "pedazos" va a estar dividido el plano. Nosotros instamos por decidir los cuts entre 10 o 12, pero esto es algo que pueda cambiarse pues se podrá seguir dividiendo en más pedazos. Luego para decidir en donde iba a estar situado el plano deslizamos el click por el campo.</p>

  <image
  src="CHALLENGE03/PLANO.png"
  width = 80%
  height = 80%>



<h2>Vamos seleccionando las áreas del plano que queremos levantar para ir dandole la forma de pirámide</h2>
<p> Para escoger las caras que queremos levantar seleccionamos el botón circulado en azul. Luego junto con <code> Shift + Click</code> nos permite seleccionar varias caras a la vez.</p>

  <image
  src="CHALLENGE03/SelectCenter.png"
  width = 80%
  height = 80%>



<h2> Agrandar parte del plano </h2>
<p> Una vez seleccionada el área en cuestión con el paso anterior, utilizando la herramienta de escalar, levantamos el área.</p>

  <image
  src="CHALLENGE03/expandirPlano.png"
  width = 80%
  height = 80%>


<h2> Continuar agrandando otras partes de la pirámide </h2>
<p> Seguimos la misma metodología para seleccionar las aristas que queremos seguir levantando.</p> 

  <image
  src="CHALLENGE03/SeleccionarAristas.png"
  width = 80%
  height = 80%>


<p> En esta vez para no hacerlo bajo un medidor subjetivo, utilizaremos <Code>Extrude Faces</Code>. Esta opción nos permite, una vez seleccionamos las caras a levantar, levantarlas una cierta medida que le especificamos, para luego si queremos alinear otras áreas del plano podamos hacerlo sin mayor complicación.</p>


  <image
  src="CHALLENGE03/extrudeAristas.png"
  width = 80%
  height = 80%>


  <image
  src="CHALLENGE03/SelectAristas2.png"
  width = 80%
  height = 80%>


<h2>Resultado temporero de pirámide escalonada</h2>
<image
  src="CHALLENGE03/Piramide.png"
  width = 80%
  height = 80%>

<h2>Añadiendo las casetas al tope de la pirámide</h2>

<p>Para crear las casetas, primero debemos utilizar ProBuilder para crear más caras en la parte superior. Escogemos todas las caras en la parte superior y utilizamos la operación de <code>Subdivide Faces</code> para lograr esto.</p>

<image src="CHALLENGE03-2/01-PyramidTop1.png" width=80% height=80%>
<image src="CHALLENGE03-2/ProBuilderEx1.png">

<p>Ahora que hemos subdividido las caras, seleccionamos algunas cerca de los costados donde se ubicarán las casetas como se muestra en la siguiente imagen:</p>

<image src="CHALLENGE03-2/02-PyramidTop2.png" width=80% height=80%>
<image src="CHALLENGE03-2/03-PyramidTop3.png" width=80% height=80%>

<p>Ahora realizamos la extrusión y...</p>

<image src="CHALLENGE03-2/04-PyramidTop4.png" width=80% height=80%>

<p>¡Voilá!</p>

<image src="CHALLENGE03-2/05-PyramidTop5.png" width=80% height=80%>
<image src="CHALLENGE03-2/06-PyramidTop6.png" width=80% height=80%>

<h2>Creando la escalera principal</h2>

<p>Para realizar la escalera principal de la pirámide, primero tuvimos que ubicar en cuál de los lados se encontrará la entrada principal. Luego de esto, tenemos que "aplanar" los muros a lo largo del centro de la pirámide para simular una rampa que ocupa toda su altura.</p>
<p>Escogemos algunas caras en el segundo nivel más alto de la pirámide...</p>

<image src="CHALLENGE03-2/07-Ramp1.png" width=80% height=80%>

<p>Utilizamos la operación de <code>Extrude Faces</code>...</p>

<image src="CHALLENGE03-2/08-Ramp2.png" width=80% height=80%>

<p>Luego seleccionamos las <bold>esquinas</bold> (<code>Edges</code>) de las caras que levantamos...</p>

<image src="CHALLENGE03-2/09-Ramp3.png" width=80% height=80%>

...y las llevamos hacia el tope de su próximo nivel inferior.

<image src="CHALLENGE03-2/10-Ramp4.png" width=80% height=80%>

<p>Ahora, ya hemos creado una rampa desde el segundo nivel más alto hasta el tope de la pirámide. Vamos a extender esta rampa para que llegue hasta la superficie. Para lograr esto, repetimos los pasos anteriores para los otros niveles.</p>

<p>Ahora para el tercer nivel más alto...</p>

<image src="CHALLENGE03-2/11-Ramp5.png" width=80% height=80%>
<image src="CHALLENGE03-2/12-Ramp6.png" width=80% height=80%>
<image src="CHALLENGE03-2/13-Ramp7.png" width=80% height=80%>
<image src="CHALLENGE03-2/14-Ramp8.png" width=80% height=80%>

<p>Para el cuarto nivel...</p>

<image src="CHALLENGE03-2/15-Ramp9.png" width=80% height=80%>
<image src="CHALLENGE03-2/16-Ramp10.png" width=80% height=80%>
<image src="CHALLENGE03-2/17-Ramp11.png" width=80% height=80%>
<image src="CHALLENGE03-2/18-Ramp12.png" width=80% height=80%>

<p>...y ahora, ¡para el último nivel!</p>

<image src="CHALLENGE03-2/19-Ramp13.png" width=80% height=80%>
<image src="CHALLENGE03-2/20-Ramp14.png" width=80% height=80%>
<image src="CHALLENGE03-2/21-Ramp15.png" width=80% height=80%>

<p>Listo.</p>

<image src="CHALLENGE03-2/22-Ramp16.png" width=80% height=80%>

<h2>Creación del Terreno</h2>

<p>Para crear un terreno utilizamos un <code>Game 3D Object</code> similar a como creamos una esfera, cubo, cilindro etc.</p>

<image
  src="CHALLENGE03/CreateTerrain.png"
  width = 80%
  height = 80%>



  <h2>Ajustamos las dimensiones del terreno</h2>
  <p>Para este challenge no habían dimensiones específicas, pero optamos por seguir unas muy parecidas a las del Challenge anterior. <strong>Importante</strong> notar las opciones de configuración del terreno donde se modifican sus valores.</p>


<p>Ajustando <CODE>Mesh Resolution</CODE></p>
<image
  src="CHALLENGE03/TerrainD.png"
  width = 30%
  height = 30%>

<p>Ajustando <CODE>Heightmap Resolution</CODE></p>
<image
  src="CHALLENGE03/TerrainD2.png"
  width = 30%
  height = 30%>
  
<p>Ajustando <CODE>Height</CODE></p>
<image
  src="CHALLENGE03/TerrainD3.png"
  width = 30%
  height = 30%>





<h2>Preparando herramienta para crear montañas </h2>
<p> Decidimos crear montañas a nuestro terreno para que no se viera como un terreno solo con una pirámide. Las montañas nos van a ayudar a dar un poco más de concepto del ambiente. Para hacer montañas hay que elegir las brocha y su tamaño.</p>


<image
  src="CHALLENGE03/montanas1.png"
  width = 30%
  height = 30%>



<h2>Creando montañas</h2>
<p>Una vez configuramos nuestra herramienta para crear montañas procedemos a crearlas. Pasando la brocha presionando <code>Click</code> haremos abultaciones al terreno y si presionamos <code>Shift + Click</code> crearemos hoyos. Esta parte es un poco subjetiva pues depende de cuantas montañas quieras crear y en que lugares. En nuestro caso decidimos crear montañas en los bordes para dejar un buen espacio llano en el centro donde irán tanto la pirámide como los animales que poblarán el lugar. No obstante tambien creamos ligeras abultaciones en el terreno para que no fuera completamente liso y tuviera un tanto de textura arrugada.</p>

<image
  src="CHALLENGE03/montanas2.png"
  width = 80%
  height = 80%>


<h2>Importando Texturas</h2>
<p>Para poder poner texturas en el terreno, primero hay que decidir qué texturas utilizaremos. Una vez decidimos que texturas utilizaremos nos aseguramos que estén guardadas en una carpeta dentro de la carpeta de Scenes. En nuestro caso decidimos elegir dos texturas, una similar a un cesped seco, y otra un poco más verde, para combinarlas y crear un buen efecto para la grama. (añadir fotos de las texturas). Las texturas pueden ser formato <Code>png</Code> o <code>jpeg</code>. </p>

<image
  src="importTextures.png"
  width = 80%
  height = 80%>

<p>Textura de césped seco.</p>
<image
  src="CHALLENGE03/Texturas/dry+grass+ground-2048x2048.png"
  width = 30%
  height = 30%>

<p>Textura de césped verde.</p>
  <image
  src="CHALLENGE03/Texturas/green+grass-1024x1024.png"
  width = 30%
  height = 30%>

<p>Textura de césped con barro.</p>
  <image
  src="muddy.png"
  width = 30%
  height = 30%>

<h2> Añadiendo texturas</h2>
<p>Para añadir las texturas al terreno seleccionamos <code>Paint Textures</code> y luego <code>Edit terrain layers</code>, entonces presionamos <code>Create Layer</code>. Ahi nos aparecerán nuestras texturas antes guardadas y las seleccionamos ambas. La primera se va a aplicar al terreno inmediatamente, pero lo hará de una forma poco natural.</p>

<image
  src="CHALLENGE03/AddTexturas.png"
  width = 80%
  height = 80%>



<h2>Ajustando Texturas</h2>
<p>Para ajustar la poca naturalidad con la que las texturas se aplican, vamos a <code>Tilling settings</code> y ajustamos los valores a unos que dependiendo de la textura puedan tener mejor relacion de aspecto con nuestro terreno. </p>
<image
  src="CHALLENGE03/ajustandoTextura.png"
  width = 80%
  height = 80%>


<h2>Mezclando texturas</h2>
<p>Una vez ajustamos las texturas, seleccionamos la textura secundaria y con la brocha vamos dando <code>Click</code> donde queremos implantarla.</p>

<image
  src="CHALLENGE03/MezclandoTexturas.png"
  width = 80%
  height = 80%>

  <p>Una vez que se continuó con los demás trabajos se añadió la textura del césped con barro.</p>

  <image
  src="muddy2.png"
  width = 80%
  height = 80%>




<h2>Suavizando terrenos (dos fotos de before and after) </h2>

<p>Si notamos ahora con las texturas puestas nuestras montañas no tienen una forma muy adecuada, parecen mnuy puntiagudas en algunas lados y puede ser una imperfección que puede mejorarse. Utilizando <code>Smooth Height</code> y seleccionando la brocha podemos ir corrigiendo esas imperfecciones poco a poco. Damos <code>Click</code> por donde queramos suavizar</p>


<p>Terreno antes de suavizarlo.</p>
<image
  src="CHALLENGE03/BeforeSmooth.png"
  width = 65%
  height = 65%>

<p>Terreno suavizado</p>
<image
  src="CHALLENGE03/AfterSmooth.png"
  width = 65%
  height = 65%>


<h2> Creando Lago</h2>

<p>Para crear de alguna manera algo que simule ser un lago en los alrededores de la ciudad utilizamos un <code>Game 3D Object Cube</code> </p>
<p>Pero antes de comenzar con el cubo debemos crear el material con el que se pintará. Para esto creamos un nuevo Folder que llamaremos <code>Materials</code>.</p>


<image
  src="materials.png"
  width = 65%
  height = 65%>


<p>Una vez creado el Folder procedemos a crear el material.</p>

<image
  src="materials2.png"
  width = 65%
  height = 65%>

  <p> Luego decidimos el color que tendrá el material, en esta área podemos ajustarlo conforme a nuestras necesidades y gustos. <strong>Importante</strong> notar que el <code>surface type</code> es <code>transparent</code> para crear un poco el efecto de transparencia del agua.</p>

<image
  src="color.png"
  width = 65%
  height = 65%>



  <h2>Aplicando el material al cubo</h2>
<p>Una vez el material y el cubo están creados solo queda arrastrar el material hacia el cubo y la magia ocurrirá.</p>
<image
  src="pintar.png"
  width = 65%
  height = 65%>
<h2>Duplicando y alargando cubo</h2>
  
<p> Ya que tenemos un cubo del color que deseamos solo queda alargarlo para que ocupe todo el espacio que queremos y duplicarlo para que cubra los otros angulos del terreno.</p>
<image
  src="rio.png"
  width = 65%
  height = 65%>

<h2>Buscando assets en el asset store</h2>
<p>Primero, iremos al tope de nuestra ventana de Unity y vamos a: <code>Windows > Asset Store</code></p>

<image
src="AssetStore/assetstore.png"
width = 65%
height = 65%>

<p>Luego, cuando abra una ventanita de asset store le daremos al boton <code>Search online</code> que nos llevara a nuestro navegador y podremos buscar assets</p>

<image
src="AssetStore/assetstore2.png"
width = 65%
height = 65%>

<p>Dentro del asset store, buscaremos tres assets que usaremos en nuestro mundo <code>Low Poly Vegetation Kit Lite</code>, <code>Stylized NPC - Peasant Nolant (DEMO)</code> y <code>Origami Animals Pack</code>. Le daremos al boton de: <code>Add to My Assets > Open In Unity</code>.</p>

<image
src="AssetStore/plantlife.png"
width = 65%
height = 65%>

<image
src="AssetStore/civilians.png"
width = 65%
height = 65%>

<image
src="AssetStore/origami.png"
width = 65%
height = 65%>

<p>Cuando ya bajemos todos los assets que usaremos, al darle <code>Add to My Assets > Open In Unity</code> al ultimo asset pack instalado o manualmente buscarlo de la manera:</p>

<image
src="AssetStore/packageman.png"
width = 65%
height = 65%>

<image
src="AssetStore/packageman2.png"
width = 65%
height = 65%>

<p>Podramos ver que en la esquina de abajo en la derecha habra un boton <code>Download</code> que presionaremos y cuando termine le daremos al <code>Import</code> para poder usar los assets en nuestro proyecto. Con esto, estaremos CASI listos para poblar nuestra escena.</p>

<h2>Haciendo upgrade los assets del store al URP que usamos en nuestro proyecto</h2>
<p>Es muy posible que cuando intente usar los assets de la internet, no se vean muy bien renderizados en su Unity, esto es porque los renderers pueden diferir entre asset y tu propio Unity. Para poder usarlos, tendremos que usar algo llamado <code>Window > Rendering > Render Pipeline Converter</code> para upgrade los shaders <code>Built-in</code> al <code>URP</code> que utilizamos en este proyecto</p>

<image
src="AssetStore/rpc.png"
width = 65%
height = 65%>

<p>Al estar en la ventana del RPC, cambiaremos el dragdown a <code>Built-in to URP</code>. Luego, le marcaremos todas las cajitas negras vacias que se nos presenten como <code>Rendering Settings</code> y le daremos <code>Initialize Converters</code>. </p>

<image
src="AssetStore/rpc2.png"
width = 65%
height = 65%>

<p>Cuando este termine, le daremos clic a <code>Convert Assets</code> para finalizar el proceso. Ya debemos poder ver nuestros assets importados sin problema alguno!</p>

<image
src="AssetStore/final.png"
width = 65%
height = 65%>

<h2>Final result</h2>
<image
src="AssetStore/last.jpg"
width = 65%
height = 65%>
  
