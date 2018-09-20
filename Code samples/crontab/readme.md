#Instanciando un Script en Crontab

## lectura
`crontab -l`
muestra la lista de crontab
## escritura
`crontab -e`
editar la tabla crontab. 
      Con esto se pueden agregar más scripts

## Estructura del crontrab
MHDMSUC
* Minuto
* Hora
* Dia
* Mes
* Semana
* Usuario
* Comando

`*       *       *       *       * 	user PATH/run.ext`



## ejemplo de  
*       *       *       *       *       python $HOME/src/cronjobs/now.py >> $HOME/src/output$

