<h1>Challenge 03 - ¡Viva México!

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

<h2>Un cambio pequeño a la luz...</h2>

<p>Antes...</p>
<image src="CHALLENGE03-2/23-DirLight1.png" width=80% height=80%>
<p>¡Despúes!</p>
<image src="CHALLENGE03-2/24-DirLight2.png" width=80% height=80%>

<h2>Añadiendo materiales (color) a la pirámide</h2>

<p>Para añadirle textura o color a la pirámide, tenemos que crear materiales y aplicárselos. Si nos dirigimos a <code>Assets -> Create -> Material</code>, se nos abrirá una nueva ventana donde podemos editar el nuevo material que creamos. Además, se debe poder ver el nuevo material en nuestra carpeta de <code>Assets</code>. A este material nuevo lo llamamos <code>PyramidMat</code>.</p>

<p>En el Inspector, editamos los parámetros como se muestran en la siguiente imagen. Le damos una superficie no metálica, opaca, y con un color dorado.</p>

<image src="CHALLENGE03-2/MatEx1.png">
<image src="CHALLENGE03-2/MatEx2.png">

<p>Si ahora realizamos un "drag and drop" de nuestro material hacia la pirámide, obtendremos un excelente resultado.</p>

<image src="CHALLENGE03-2/25-Mat1.png" width=80% height=80%>

<p>Para darle más color a nuestra pirámide, crearemos un segundo material con un color distinto y se lo aplicaremos. Creamos otro material y a este le llamamos <code>PyramidMat2</code>.</p>

<image src="CHALLENGE03-2/MatEx3.png">
<image src="CHALLENGE03-2/MatEx4.png">

<p>Ahora, para aplicar más colores a la pirámide, tendremos que realizar un proceso un poco distinto. Ya no es tan simple como "drag and drop" el material.</p>

<p>Seleccionamos la pirámide y abrimos la ventana de ProBuilder nuevamente. Nos dirigimos hacia una nueva pestaña: el <code>Material Editor</code>. En la sección de <code>Material Palette</code>, veremos una lista de materiales vacía. Llenaremos los primeros dos encasillados con los materiales que creamos. En la siguiente imagen se muestra el resultado:</p>

<image src="CHALLENGE03-2/MatEx5.png">

<p>En nuestro caso, <code>PyramidMat2</code> ahora está asociado con el botón <code>Alt + 2</code>.</p>

<p>Ahora, seleccionamos todas las caras superiores del primer nivel...</p>

<image src="CHALLENGE03-2/27-Mat3.png" width=80% height=80%>

<p>Oprimimos el botón de <code>Alt + 2</code> que asociamos con el material...</p>

<image src="CHALLENGE03-2/28-Mat4.png" width=80% height=80%>

<p>...y ahora, le hemos añadido más color a nuestra pirámide.</p>
<p>Ahora, simplemente repetiremos el proceso para los otros niveles de la pirámide.</p>

<image src="CHALLENGE03-2/29-Mat5.png" width=80% height=80%>
<image src="CHALLENGE03-2/30-Mat6.png" width=80% height=80%>
<image src="CHALLENGE03-2/31-Mat7.png" width=80% height=80%>
<image src="CHALLENGE03-2/32-Mat8.png" width=80% height=80%>
<image src="CHALLENGE03-2/33-Mat9.png" width=80% height=80%>

<p>También le añadiremos color a las esquinas de la rampa para simular las escaleras principales.</p>

<image src="CHALLENGE03-2/34-Mat10.png" width=80% height=80%>
<image src="CHALLENGE03-2/35-Mat11.png" width=80% height=80%>

<p>¡Finalmente hemos completado la pirámide!</p>

<image src="CHALLENGE03-2/36-Mat12.png" width=80% height=80%>