# VerveTech
#  Dejo el [LINK DEL FIGMA](https://www.figma.com/file/mtxIWIOkvecy6Hwvu3GgKr/Verve-Tech?node-id=0%3A1) donde se podra visualizar a que se busca llegar.

# Registro de utilizacion de Bootstrap:
## Al no tener que abusar del mismo, se implementaron distintos componentes en las paginas del proyecto:
    - navbar: Se implemento la navbar responsive de bootstrap, modificando su contenido con css para matchear el estilo de la pagina, esta navbar se implemento en todos los .html del proyecto. Ademas se le agrego una transicion al menu hamburguesa con el objetivo de añadir sensacion de fluidez.

    - index.html: Se utilizo el grid de Bootstrap, encerrando todo el contenido de la pagina un div con la clase container, para asi con los div.row poder dar los correctos espacios. El grid se utilizo mas de una vez, ya que para la simulacion de productos en el index se utilizo otra grilla dentro del contenedor main_2 y main_3.

    - our_staff.html: Al igual que index.html se utilizaron los grids de bootstrap para maquetar la pagina, ademas se uso los div.row y div.col para posicionar correctamente las cards del os_header. Se implementaron los componentes card de bootstrap.

    - support.html: En esta pagina, no se uso el grid de bootstrap, sino que se uso el grid layout clasico con los media query. Se dejo de esta manera para no hacer abuso del framework como se dijo en la clase. No obstante se aplico Bootstrap en el form de esta pagina. Se uso uno de los diseños del framework retocados manualmente con css.

    - faq.html: En esta pagina, se implemento Bootstrap mediante la utilizacion de un elemento acordeon. Este elemento fue modificado para que encajara en la pagina y se le agrego una transicion de forma manual. En esta pagina se utilizaron las media query para dimensionar correctamente el header.

    - about.html: Esta pagina es muy especial, ya que hace uso y convina LOS DOS tipos de grillas, se utiliza el grid layout clasico con media querys para maquetar los elementos padre de la pagina, mientras que se usa el grid de bootstrap para posicionar correctamente las card (tambien de bootstrap) en el header, haciendo uso de div.container div.row y div.col de manera correcta.

    **Tambien se utilizo _flexbox_ y _box-modeling_ en todas las paginas para terminar de acomodar y ajustar los elementos**

# Registro segunda entrega proyecto final
## Se implementaron, mejoraron y agregaron los siguientes items:

    - Todos los html fueron ordenados, sin dejar espacios innecesarios.
    - El styles.css fue ordenado, sin dejar espacios vacios y etiquetando cada seccion para que se sepa que parte del codigo se esta leyendo.
    - Para que la entrega quede un poco mas completa, se elimino el grid del index donde habia una simulacion de una store y en cambio se creo el store.html. En esta pagina, la cual se accede desde el index por el momento, se encuentra debidamente ordenada, mediante grids de bootstrap y flexbox la tienda de la pagina. Se presto especial atencion a la utilizacion del recurso :hover y :active enseñado en la clase, por ejemplo, en el menu aside o en los botones de las tarjetas. Se tomo como referencia e inspiracion la pagina de mercadolibre.com y amazon.com para el aside.
## Dudas de la entrega:

    - En algunas ocaciones la pagina de store.html se traba o tiene bajones. Eso se debe a la alta resolucion de algunas imagenes? De ser asi, hay alguna forma de optimizarlo sin cambiar la resolucion? Es posible que sea mi computadora el problema (ya que es vieja)?

# Registro de desafio SASS
## El HTML utilizado se encuentra en pages/store.html

    - Se modifico la escritura en la hoja de estilos .scss de manera que se escriba como lo permite SASS. Se utilizo el recurso &:hover y &:active; ademas se utilizaron las variables,  creando los archivos _colors.scss, _fonts.scss y _variables.scss.
    Me hubiera gustado usar mas las variables, pero como venia escribiendo el codigo esto fue lo que pude implementar. En las paginas que siga creando (faltan algunas) voy a escribirlas utilizando solo sass y variables.

# Registro de desafio SASS II y SEO
## Se aplicaron los siguientes conceptos:
    - En la parte de SASS II se aplico mapa, localizado en _maps.scss, en el mismo se encuentra los hex del fondo del footer en cada una de las paginas, se puede probar facilmente cambiando el hexadecimal. Tambien con los colores de los botones de la pagina de inicio "Hardware" y "SOftware". Se aplico un extend (este  fue bastante basico porque no encontre una mejor manera de aplicarlo dentro de este proyecto) como "@extend .footer_op_support;". Por ultimo de aplico mixins en _mixins.scss en donde se establecio la "configuracion de imagenes" utilizando el $attach para definir el attachment; se establecio un flex-column-center-center.
    - En la parte de SEO se coloco una descripcion a cada uno de los html, un tag con las keywords y se hicieron las verificaciones de google tanto search Google como optimizacion para moviles de Google. A su vez se genero un sitemap. 

# Registro tercer entrega del proyecto final.
## Se aplicaron los siguientes cambios: 
    - Se elimino los textos simulados y se los reemplazo por texto real.
    - Se optimizo el responsive en ciertos html que fallaba.
    - Se implemento el html "building-a-new-page.html", aqui se redireccionan todas aquellas paginas que no han sido contruidas ya que no forman parte de las 5 paginas del final, con el objetivo de que no haya links sin funcionar. En el mismo se aplico un SVG.
    - Se subio la pagina a la direccion: https://vervetech.netlify.app/ .
    - Se corrigio el error en el .ico en todos los html de la pagina.