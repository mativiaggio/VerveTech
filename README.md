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

