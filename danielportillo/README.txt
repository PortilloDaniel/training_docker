En el Workshop se desarrollaron dos actividades por las cuales se pretende medir la disminuciòn de peso
de una imagen cuando se optimiza su còdigo. Como se evidencia la imagen con ID 0.3.0 que ejecuta el Dockerfile 1 (Anexo) y que
inicialmente tiene un peso de 15 Mb. Posteriormente, se ejecuta el Dockerfile 2 cuyo ID es 0.4.0, el peso de està imagen 
pasa de 15 Mb a 14.8.

Aunque no es una disminuciòn sustancial se entiende que se deben instalar dos paquetes y que esto implica consumo de recursos
de procesamiento y almacenamiento

Finalmente, Entrypoint y Cmd permiten la ejecuciòn de parametros en los contenedores, dichos comandos son ejecutados 
al iniciar un contenedor. Sin embargo, los comandos ejecutados en CMD tiene la ventaja de que pueden ser detenidos o anulados,
mientras que un comando ejecutado o iniciado por Entrypoint no puede ser tenido si en el codigo no se ha creado una bandera 
de tipo --entrypoint 

