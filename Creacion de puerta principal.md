# Creando los cubos

Para comenzar en el trabajo, creé dos cubos pensando que para crear la pared principal necesitaría dos cubos que formen ambos lados de la entrada y un cubo que se estrecharía para unir ambos 
lados y crear la puerta, pero para asegurar consistencia en tamaños, una vez creé el lado izquierdo, pensé en duplicarlo y ajustar las coordenadas del cubo.



# Trabajando con el lado izquierdo de la pared

Como el cubo izquierdo sería de lo que se basaría el cubo derecho, comencé con este para tener ambos lados de una. En esto aprendí bien a manejar los valores del scale ya que quería ir de tener un cubo 
exacto a algo más parecido a una pared. Comencé probando diferentes valores y, aunque al inicio creé varias formas extrañas tratando de ver qué pasaba al insertar valores grandes, gracias a ese proceso de 
errores logré ver cuán sensibles son los valores en relación al tamaño del cubo. Terminé con un set de scale que consideré satisfactorio para comenzar la casa. Al por fin tener el scale de la casa, 
me aseguré de posicionarla de una forma que pueda manejar las otras partes de la entrada apropiadamente. Al final, el lado izquierdo terminó con los siguientes valores:

![image](https://github.com/user-attachments/assets/3ed33528-7f9e-4829-80a1-c318e11751ff)


# Trabajando con el lado derecho de la pared

Como mencioné, una vez ya tuve el lado izquierdo terminado, dupliqué ese objeto para asegurar que sean del mismo tamaño y lo moví al lado derecho. Para las coordenadas,
me aseguré de que las coordenadas Y y Z sean iguales y di el valor opuesto para el valor X. Como pueden ver en la foto, el valor de X es el mismo, pero el lado izquierdo es negativo.
De esta forma, también me aseguro de que estén a la distancia exacta que quiero. Ya para este punto, estoy más cómodo usando los valores numéricos para mover y alterar las cosas, lo cual fue útil 
ya que es la forma más eficiente de alterar objetos en el plano 3D. El reto más grande, aparte de eso en este punto, fue manejar una distancia donde la puerta no sea muy ancha y que luego, 
al agregar el último cubo, no termine muy alta.

![Screenshot from 2024-09-03 21-58-48](https://github.com/user-attachments/assets/8008335f-2f52-4ffa-9fc1-de3e1c460b32)


# Trabajando con la puerta


Aquí viene la parte más interesante para mí: crear el margen de la parte superior que da la ilusión de la puerta y conecta ambas paredes simultáneamente. Comencé esta parte nuevamente manipulando 
el cubo para encontrar el tamaño exacto que quería. Fue un poco más trabajoso que la pared, ya que necesitaba algo que no se viera ni se notara que es un objeto distinto; quería que se viera como un 
solo objeto, todo conectado. Traté de crear primero el largo perfecto del cubo para que las puertas estén a una distancia satisfactoria y que no estén ni muy lejos, pero no muy cerca tampoco, 
ya que la ilusión de la puerta dependía todo de esto. Una vez tuve la distancia que quería, traté de manejar el scale de tal forma que terminara con algo parecido a una plancha de madera; 
por lo menos eso es lo que tenía en mente en esta parte. Una vez tuve algo que se veía como quería, decidí rotar ese plano en el eje Z a 180 grados para que esté en posición de conectar ambas paredes. 
Para terminar esta parte, tocaba lo más complicado: unir ambas paredes. Traté de hacer esto con el mouse, moviendo el cubo hasta que a ojo se viera bien y anotando los valores de la escala 
para ajustarlos con un poco más de detalle. Esta parte me tomó un poco de tiempo, ya que no importaba lo que hiciera, aún se podía ver que había un cubo "clipping" los otros dos cubos. 
Hasta que en un punto decidí mover la cámara y descubrí que a cierta distancia no se notaba este detalle. Así que me dediqué a encontrar los valores que me dieran exactamente lo que quería en este punto, 
y poco a poco conecté ambas paredes. Esta fue la parte más trabajosa, ya que incluía manejar un cubo para tener una forma distinta a todo lo demás en la casa y que conectara ambas paredes, 
mostrara un espacio que representara la puerta y no se notara la unión de objetos. Pero a la misma vez, fue la parte donde más aprendí porque el tiempo que me tomó trabajar con todos los valores de scale, 
rotation, y position fue tiempo que logré sentirme un poco más cómodo manejando objetos en espacio 3D.

![Screenshot from 2024-09-03 21-58-53](https://github.com/user-attachments/assets/6eaf425d-d6e5-4d9b-ac06-f1258dfd2db0)


# Producto final

![Screenshot from 2024-09-03 21-59-01](https://github.com/user-attachments/assets/921ffec4-65e7-446e-96ef-f5c3fc730a13)
