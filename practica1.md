Esta practica es básica pues organiza un diseño de interface (UI), hay botones de acción, áreas de texto y despligue con propiedades de ocultar

![](Practica1parte1.jpg)


![](Practica1parte2.jpg)


```
/**
                                 
,------. ,------.,--.    ,-----. 
|  .--. '|  .---'|  |   '  .--./ 
|  '--' ||  `--, |  |   |  |     
|  | --' |  |`   |  '--.'  '--'\ 
`--'     `--'    `-----' `-----'

Área de Código Fuente para el formulario UI sencillo

POR: René Solis
Fecha: 5-3-19
Notas:  Para uso de estudiantes PFLC Bloque I de Informática.

**/

onEvent("btnCuantasLetras", "click", function(event) {
  // console.log("btnCuantasLetras clicked!");
  // Checamos si tiene algo el btnNombre
  //
  var txtNombre = getText("txtNombre");
  var intCuantasLetras = 0;
  
  // Esta validacion pregunta si hay algo capturado de lo contrario lo salta.
  if (txtNombre.length > 1) {
    console.log("No esta vacio");
    intCuantasLetras = txtNombre.length;
    
    // Desplegar numero de letras
    setText("txtCuantasLetras", "Cuenta con "+ intCuantasLetras +" caracteres el nombre");
    showElement("txtCuantasLetras");
    
  } 
});

//Boton para Borrar el Formulario
onEvent("btnBorrar", "click", function(event) {

  // Desplegar numero de letras
  setText("txtCuantasLetras", " ");
  setText("txtNombre", " ");
  hideElement("txtCuantasLetras");
     
});
```
