# Building a ANN
  
[Label Encoder vs One Hot Encoder](https://contactsunny.medium.com/label-encoder-vs-one-hot-encoder-in-machine-learning-3fc273365621)
## Label Encoder
Convierte un dato categorico de texto a una variable numerica, sin embargo, esto puede ocasionar que el modelo entienda 
dicha variable numerica como cierto ordenamiento.

## One Hot Encoder
Tiene la misma funcion que el label encoder, sin embargo este distribuye las categorias existentes, supongamos
4, en 4 nuevas columnas. La categoria a la que pertenezca la fila actual estara en 1 mientras que el resto
tendran un valor 0. Una columna es asignada a una categoria.