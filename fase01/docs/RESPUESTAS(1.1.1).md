## 1.1.1 Variables y tipos de datos

# Qué es una variable

     Una variable es un contenedor que almacena un tipo de dato concreto, el valor de la misma puede variar a lo largo de la ejecucion de un programa, La variable en no es el valor, solo almacena.

# Tipos primitivos (número, texto, booleano, nulo, indefinido)

    Los tipos de datos mas basicos son:

      *** number ***
       datos numericos, estos se dividen en:
        integer: int;
        float;
        double;
        y otros poco usados en la programacion convencional, estos se usan mayormente en ciencia de datos, etc...;

        ejemplo:
        5; -3; 0 = int;
        3.14; 0.5 = float;
        4.09040989393...... = double;

      *** string ***
      Textos y cadeas de texto;
      estos llevan comillas simples(' ') o dobles (" ") para diferenciarlos de los numeros y otros tipos de datos;

        "charls" = string
        "a" = string
        "Hola mundo" = string
        "53" = string !!!!

      *** booleano(boolean) ***

      es un tipo de datos que puede tener solo dos posibles valores:
      true y false;

      por lo general se usa para logica y su manejo puede llegar a ser complicado;

      *** nulo(null) ***

      es la forma de declarar uns variable sin valor a proposito, es como decirle al ordenador, aqui no hay datos pq lo decidi asi;

      ejemplo:

      let inventario = null;


      *** Undefined ***

      significa aun no hay valor, aparece cuando declaras una variable pero no le das un valor.

      ejemplo:

      let inventario;

# Declaración y asignación

    Declaracion de una variable no es mas que q crearla y ponerle un nombre(o etiqueta).

      Ejemplo:
        variable edad;
        variable x;
        variable etc;

    El proceso de asignacion no es mas que gurdar n tipo de dato dentro de una variable declarada previamente (aunq tambien dicha asignacion puede ocurrir durante la declaracion)

      Ejemplo:
        edad = 28;
        x = 'azul';
        etc = true;
        variable nombre = Aliadex;

      El signo "=" es el que mayormente asigna el tipo de dato de la variable.

    Los nombres de las variables deben respetar ciertos parametros:

      *Deben comenzar con letras;

        edad; perro; casa123(correcto)
        1edad; *casa; (error)

      *No deben contener espacios;

        granHermano; jardin_infantil;(correcto)
        gran hermano; (error)

      *No pueden usarse palabras reservadas del lenguaje en el q se declaran;
        entero, vacio, texto (correcto)
        int; void; string; (error)

    El contenido de una variable puede cambiar(por eso su nombre)excepto en algunos lenguajes o declarandolas como constantes. el contenido de una variable siempre sera el ultimo asignado y su contenido anterior desaparece.

      Ejemplo:

      variable casa = 'azul';
      casa = 'verde';

      ahora casa contiene el string "verde";

    En la mayoria de los lenguajes de programacion 'casa' es diferente de 'Casa' ya que distinguen mayusculas de minusculas;


    Esta es solo un consejo, se considera buena practica que las variables hagan referencia al tipo de dato que van a contener o a la funcion q van a cumplir, ya q asi otra persona pueda con solo ver nombre de la variable tener una idea de su contenido o funcion especificos;

# Constantes vs variables

Constantes: Variables cullo contenido no va a cambiar a lo largo de la ejecucion del programa;

Variable: Ya su nombre lo dice, explicarlo seria redundante;

Ejemplo:

contante nombre = 'Aliadex';
nombre = 'Robert'; (error, las constantes no pueden variar su contenido)

variable edad = 25;
edad = 35; (correcto)

El uso de variables o constantes no es ni deve ser una una disputa entre estilos de declaracion , simplemente pq ambas tienen casos donde es mejor usar una u otra;

Ejemplo:
constante PI = 3.14;
(buena practica, el valor de pi no deberia cambiar ya q calculos, formulas o acciones del programa pueden depender de ella)
variable PI = 3.14;
(mala practica, si por error se asigna otro valor a pi, el resultado puede ser desastroso.)

    constante edad = 22;
    (mala practica, que pasa el año proximo?)
    variable edad = 22;
    (buena practica, asi cada año q pase no hay que eliminar edad y volverla a declarar con otro contenido)

Reglas de oro para Constantes:

    *No se pueden declarar constantes sin asignarles un valor;

    *Se considera buena practica nombrarlas en mayusculas, asi otra persona sabe casi de inmediato q es una variable y q su contenido no es modificable;
