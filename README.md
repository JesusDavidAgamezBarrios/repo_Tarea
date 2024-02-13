### Javascript

### clase de Date

### Metodo de instanciacion

### Date.prototype.getDate()

Retorna el día del mes (`1`–`31`) para la fecha especificada acorde a la hora local.

`let day = new Date().getDate();`

`console.log(day);`

el retorna el dia en el que se ejecuto el codigo  es 13 (ya que hoy es 13 de febrero)



### Date.prototype.getDay()

Retorna el día de la semana (`0`–`6`) para la fecha especificada acorde a la hora local.

`let day = new Date().getDay();
console.log(day)`

retorna el dia que se ejecuta el dia ,el resultado de hoy es 2(MARTES) 



### Date.prototype.getFullYear()

Retorna el año (4 dígitos para años de 4 dígitos) para la fecha especificada acorde a la hora local.

`let day = new Date().getFullYear();
console.log(day)`

retorna el año en el que se ejecuta en este caso el 2024



### Date.prototype.getFullHours()

Retorna la hora (`0`–`23`) para la fecha especificada acorde a la hora local.

`let day = new Date().getHours();
console.log(day)`

retorna la hora en la que es ejecutado, en este caso las 7(am)

 ###  Date.prototype.getMilliseconds()

Retorna los milisegundos (`0`–`999`) para la fecha especificada acorde a la hora local.



`let day = new Date().getMilliseconds();
console.log(day)`

da como resultado los milisegundos en la que es ejecutado en este caso 570

### Date.prototype.getMinutes()

Retorna los minutos (`0`–`59`) para la fecha especificada acorde a la hora local.

`let day = new Date().getMinutes();
console.log(day)`

genera el resultado en el minuto que fue ejecutado el codigo, en este caso es 42

### Date.prototype.getMonth()

Retorna el mes (`0`–`11`) para la fecha especificada acorde a la hora local.

`let day = new Date().getMonth();
console.log(day)`

el resultado es el mes en el que es ejecutado el codigo en este caso es el 1(Febrero)


### Date.prototype.getSeconds()

Retorna los segundos (`0`–`59`) para la fecha especificada acorde a la hora local.

`let day = new Date().getSeconds();
console.log(day)`

retorna el resultado cuando se ejecuta el codigo , en este caso es 34(Segundos)



### Date.prototype.getTime()

Retorna el valor númerico de la fecha especificada como el número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC. (Retona valores negativos para fechas previas.)

`let day = new Date().getTime();
console.log(day)`

retorna el resultado cuando se ejecuta el codigo en este caso  1707828605945

### Date.prototype.getTimezoneOffset()

Retona la diferencia horaria en minutos para la hora local.

`let day = new Date().getTimezoneOffset();
console.log(day)`

retorna como resultado cuando se ejecuta el codigo 300

### Date.prototype.getUTCDate()

Retorna el día (fecha) del mes (`1`–`31`) para la fecha especificada acorde a la hora local.

`let day = new Date().getUTCDate()` 

`console.log(day)`

da como resultado el dia en que fue ejecutado el codigo, en este caso el 13 (13 de febrero que se ejecuto el codigo)

### Date.prototype.getUTCDay()

Retona el día de la semana (`0`–`6`) para la fecha especificada en hora universal.

`let day = new Date().getUTCDay()` 

`console.log(day)`

retorna el dia que se ejecuto el codigo en este es el 2( Martes)

### Date.prototype.getUTCFullYear()

Retona el año (4 dígitos para años de 4 dígitos) para la fecha especificada acorde a la hora universal.

`let day = new Date().getUTCFullYear()` 

`console.log(day)`

retorna el año en el que fue ejecutado el codigo en este 2024

### Date.prototype.getUTCHours()

Retona la hora (`0`–`23`) para la fecha especificada acorde a la hora universal.

`let day = new Date().getUTCHours()` 

`console.log(day)`

retorna la hora que fue ejecutado el codigo en este caso el 13 ( 13 de febrero)

### Date.prototype.getUTCMilliseconds()

Retona los milisegundos (`0`–`999`) para la fecha especificada acorde a la hora universal.

`let day = new Date().getUTCMilliseconds()` 

`console.log(day)`

retorna el dia en que fue ejecutado