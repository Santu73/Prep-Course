
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* Funciones Callback


RESOLUCION:

1_ 
  Callback: Es cuando pasamos como argumento una funcion a otra funcion, Esta recibe el nombre de CALLBACK.

  EJ:
  function animal(animal){
      return "Hola" + animal
  }
    
  function saludar(animal, cb){  
      return cb(animal)
  }   

  Resumiendo, al escribir cb que significa callback, esto tiene que recibir una funcion ya declarada, para luego invocarla y ejecutarla. Ademas tiene que recibir un parametro de la funcion declarada.

  DATO: no necesariamente se tiene que escribir cb, tambien puede ser como func o function, siempre y cuando se respete el orden y ubicación de estos.