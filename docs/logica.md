## Nombre del proyecto
Closet

## Descripcion
La aplicación del closet tiene como finalidad ayudar al usuario a comprar ropa de segunda mano. 
En la aplicación el usuario puede ver las prenedas disponibles y elegir la prenda que quiere comprar y despues podrá ver la información del producto.


## Flujo Principal 
1. El usuario ingresa ingresa al Landing.
2. El usuario hace clic sobre el botón comprar. 
3. El usuario se redirige a la pantalla de los productos.
4. El usuario ve los productos
5. El usuario pasa el mouse por encima del producto.
6. El producto aumenta su tamaño y muestra la información del producto.

## Pseudocódigo 
### Flujo para el botón comprar : 
1. Al hacer clic en la bandera verde: 
- El sprite del botón comprar se muestra. 

2. Al hacer clic sobre el botón de comprar:
- Se esconde el botón de comprar
- Se cambia el fondo a la pagina de "comprar"
- se envia el mensaje Comprar 
### Flujo para el sprite del pantalón
1. Al hacer clic en la bandera verde: 
El sprite del pantalón se oculta.

2. Al recibir el mensaje de "comprar" que viene del sprite del botón "comprar":
- El sprite del pantalón se muestra.

### Flujo para el sprite cambiante del pantalón
1. Al hacer clic sobre la bandera verde: 
- Se ubica el sprite del pantalon en la posición x:0 y:0
- Se ajusta el tamaño del sprite del pantalón al 100%
    - Luego, dentro de un bucle infinito: 
    - Si [el puntero del mouse está tocando el sprite del pantalon]
        - [Ajusta su tamaño a 150%]
        - [Envía un mensaje "info"]
    - Si no: 
    -   [Ajusta el tamaño del mouse a 100%]
            
## Simulación en Scractch 




