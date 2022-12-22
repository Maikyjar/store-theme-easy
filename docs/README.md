# store-theme-easy

# EASY Colombia

Proyecto realizado sobre la base de un minimum boilerplate theme de vtex io, su construccion es el resultado del desarrollo del bootcamp de vtex university y la documentacion oficial, tiene como objetivo replicar la pagina oficial de Easy.

![imagen](/assets/img/michael--itgloberspartnercl.myvtex.com_.png)

[ejemplo de link](https://michael--itgloberspartnercl.myvtex.com/)

# Configuraciones

### Paso 1 - Configuración Básica

Para iniciar con el desarrollo de este proyecto inicialmente debes instalar un editor de codigo, ademas de tener instalado Git y Git Bash, ademas de realizar la instalacion y configuracion del CLI de VTEX IO.

### Paso 2 - Clonación del repositorio

Estando en este repositorio te dirijes a la parte superior derecha das click en "Code", copias la direccion HTTPS, te dirijes al directorio o carpeta de tu computador en donde deseas colocar el proyecto, con click izquierdo seleccionas "Git Bash here" y despues escribes el comando: git clone "y pegas la direccion que copiaste anteriormente".

### Paso 3 - Editar el Manifest.json

En el Manifest.json debes cambiar el nombre del vendor por el correspondiente, colocar el nombre de preferencia a la tienda.

### Paso 4 - Instalar apps necesarias

Todas las apps necesarias para el inicio del proyecto se van a instalar en el momento que se realice el link de la aplicacion lo unico es verificar que el vendor corresponda al partner habilitado ya que se va a realizar la respectiva autenticacion, con el comando vtex ls en la consola, puedes mirar las dependencias instaladas.

### Paso 5 - Cambiar el store-theme predeterminado

Para este paso debemos ir a nuestra store-theme:

    https://yourWorkspace--yourPartner.myvtex.com/admin

Despues de estar ahí, debemos ir a STORE SETTINGS luego a CMS y por ultimo a Pages, editamos la opcion Home y en el apartado de templates por default debemos seleccionar:

    yourPartner.store-theme@0.x:store.home

### Paso 6 - Ejecute un preview de la tienda

Por ultimo procedemmos a colocar el comando `vtex link` en nuestra consola estando en la raiz del proyecto, ya con este proceso se debe mostrar toda la tienta en el workspace que se este ejecutando.

### Dependencies
1. Store-theme
2. Store GraphQl

### Store Component Apps nativas VTEX IO

```json
    "vtex.store": "2.x",
    "vtex.store-header": "2.x",
    "vtex.product-summary": "2.x",
    "vtex.store-footer": "2.x",
    "vtex.store-components": "3.x",
    "vtex.styleguide": "9.x",
    "vtex.slider": "0.x",
    "vtex.carousel": "2.x",
    "vtex.shelf": "1.x",
    "vtex.menu": "2.x",
    "vtex.minicart": "2.x",
    "vtex.product-details": "1.x",
    "vtex.product-kit": "1.x",
    "vtex.search-result": "3.x",
    "vtex.login": "2.x",
    "vtex.my-account": "1.x",
    "vtex.flex-layout": "0.x",
    "vtex.rich-text": "0.x",
    "vtex.store-drawer": "0.x",
    "vtex.locale-switcher": "0.x",
    "vtex.product-quantity": "1.x",
    "vtex.product-identifier": "0.x",
    "vtex.product-specification-badges": "0.x",
    "vtex.product-review-interfaces": "1.x",
    "vtex.telemarketing": "2.x",
    "vtex.order-placed": "2.x",
    "vtex.stack-layout": "0.x",
    "vtex.tab-layout": "0.x",
    "vtex.responsive-layout": "0.x",
    "vtex.slider-layout": "0.x",
    "vtex.iframe": "0.x",
    "vtex.breadcrumb": "1.x",
    "vtex.sticky-layout": "0.x",
    "vtex.add-to-cart-button": "0.x",
    "vtex.store-link": "0.x",
    "vtex.store-icons": "0.x",
    "vtex.store-image": "0.x",
    "vtex.modal-layout": "0.x",
    "vtex.search": "2.x",
    "vtex.disclosure-layout": "1.x",
    "vtex.product-price": "1.x",
    "vtex.product-specifications": "1.x",
```

### Custom Apps

```json
    "itgloberspartnercl.whatsapp-button": "0.x",
    "itgloberspartnercl.bullets-diagramation": "0.x",
    "itgloberspartnercl.add-to-cart-info": "0.x",
    "itgloberspartnercl.custom-department-search": "0.x",
    "itgloberspartnercl.pdf-reader": "0.x",
    "itgloberspartnercl.quick-order": "0.x",
    "itgloberspartnercl.special-diagramation": "0.x"
```

Contributors
1. Michael Alvarez