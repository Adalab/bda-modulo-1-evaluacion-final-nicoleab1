
# Ejercicio de evaluación : TiendaOnline

En este ejercicio de evaluación, se ha creado una clase llamada TiendaOnline que tiene 3 atributos y 7 métodos que permiten realizar algunos de los procesos que se necesitarían en sus operaciones diarias.

## Atributos

Los **atributos** con los que cuenta esta clase son los siguientes: 

+ **Inventario**
+ **Clientes**
+ **Ventas totales**

Los **métodos** que se han creado para esta clase se detallan a continuación:

- **agregar_producto** : Este método permite ingresar nuevos productos al inventario. En caso de que el producto ya exista, este método añadirá la cantidad indicada a la cantidad existente de dicho producto. Para utilizarlo debes llamar al método y proporcionar los siguientes parámetros: "nombre", "precio", "cantidad".

- **ver_inventario** : Este método permite ver cual es la situación del inventario en el momento en que este método sea llamado. Dará los detalles de: Nombre (del producto), precio, y cantidad.

- **buscar_producto** : Este método permite buscar un producto en el inventario, al ingresar el nombre del producto como parámetro y devuelve la información de dicho producto.

- **actualizar stock** : El siguiente método que tiene esta clase es el de actualizar stock, cuyos parámetros a insertar son el nombre del producto, y la cantidad que deseas añadirle al stock. 

- **eliminar_producto** : Este método permite eliminar productos de nuestro inventario, solo hace falta ingresar el nombre del producto que uno desea eliminar como parámetro.

- **calcular_valor_inventario** : Con este método el usuario puede saber el monto total en dólares al que asciende su inventario con los precios dados. 

- **realizar_compra**: Este método le muestra al cliente la lista de productos que existen en el inventario, para que el cliente pueda introducir el nombre del producto que desea adquirir. Posteriormente deberá ingresar la cantidad, y repetir este proceso hasta que ya haya elegido todos los productos que desee. En este punto ingresa la palabra "listo" y el método le dirá el monto al que asciende su carrito. Si el cliente eligiera un monto mayor al existente en inventarios, se le informará al respecto y debe iniciar el proceso de nuevo introduciendo un monto menor.

## Cuestiones importantes:

Las palabras que se ingresen deben estar escritas en minúscula.
