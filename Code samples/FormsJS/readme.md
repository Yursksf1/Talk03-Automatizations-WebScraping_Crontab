# usar Js para llenar formularios

* ve al inspeccionador de elementos
* busca el campo de texto, ¿que atributos tiene? class id?
* usa el dom

## DOM 

`Docuement.getElementById(“NameField”).value = “MyValue”`


## Ejemplo completo
* enlace del formulario: https://goo.gl/forms/3jhi3jz7rlML8ir82



```
document.getElementsByClassName("quantumWizTextinputPaperinputInput exportInput")[0].value = "Yurley";
document.getElementsByClassName("quantumWizTextinputPaperinputInput exportInput")[1].value = "Yurley@datagran.io";
document.getElementsByClassName("quantumWizTextinputPaperinputInput exportInput")[2].value = "319001";
document.getElementsByClassName("quantumWizTextinputPapertextareaInput exportTextarea")[0].value = "Medellin Nodo Cowork";
document.getElementsByClassName("quantumWizTextinputPapertextareaInput exportTextarea")[1].value = "Is Amazing";
```
