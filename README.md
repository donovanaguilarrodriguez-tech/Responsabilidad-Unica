# Responsabilidad-Unica
En este proyecto se separan los datos del libro y la forma en que se guarda.
La clase Libro contiene unicamente los atributos y datos propios del libro como el titulo y el autor.
La clase Guardar se encarga unicamente de guardar o exportar la informacion.
De esta forma, si el dia de manana se quiere cambiar la forma de guardar los datos, por ejemplo a una base de datos, solo se modifica la clase Guardar sin tocar para nada la clase Libro.
