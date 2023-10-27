Aplicación de listado de personas
Esta es una aplicación de escritorio en Java que permite registrar, listar, modificar y eliminar personas. La aplicación utiliza una base de datos para almacenar la información.

Clases
Persona
La clase Persona representa a una persona y tiene los siguientes campos:

id: el identificador único de la persona.
nombre: el nombre completo de la persona.
tel: el número de teléfono de la persona.
email: la dirección de correo electrónico de la persona.
La clase tiene dos constructores: uno vacío y otro que toma tres argumentos. También tiene métodos getter y setter para cada campo, así como un método toString() que devuelve una representación en cadena del objeto.

ListadoDePersonasApp
La clase ListadoDePersonasApp es la clase principal de la aplicación y contiene el método main(). El método crea una instancia de la clase Persona y la imprime en la consola. La aplicación utiliza el constructor vacío para crear el objeto, luego establece los campos utilizando los métodos setter.

Requisitos
Para ejecutar esta aplicación, necesitará tener instalado Java en su computadora.
