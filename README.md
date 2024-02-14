### Javascript

### Clase de Date

### Metodo de instanciacion

### `Date.prototype.getDate()`

Retorna el día del mes (`1`–`31`) para la fecha especificada acorde a la hora local.

`let day = new Date().getDate();`

`console.log(day);`

el retorna el dia en el que se ejecuto el codigo  es 13 (ya que hoy es 13 de febrero)



### `Date.prototype.getDay()`

Retorna el día de la semana (`0`–`6`) para la fecha especificada acorde a la hora local.

`let day = new Date().getDay();
console.log(day)`

retorna el dia que se ejecuta el dia ,el resultado de hoy es 2(MARTES) 



### `Date.prototype.getFullYear()`

Retorna el año (4 dígitos para años de 4 dígitos) para la fecha especificada acorde a la hora local.

`let day = new Date().getFullYear();
console.log(day)`

retorna el año en el que se ejecuta en este caso el 2024



### `Date.prototype.getFullHours()`

Retorna la hora (`0`–`23`) para la fecha especificada acorde a la hora local.

`let day = new Date().getHours();
console.log(day)`

retorna la hora en la que es ejecutado, en este caso las 7(am)

 ###  `Date.prototype.getMilliseconds()`

Retorna los milisegundos (`0`–`999`) para la fecha especificada acorde a la hora local.



`let day = new Date().getMilliseconds();
console.log(day)`

da como resultado los milisegundos en la que es ejecutado en este caso 570

### `Date.prototype.getMinutes()`

Retorna los minutos (`0`–`59`) para la fecha especificada acorde a la hora local.

`let day = new Date().getMinutes();
console.log(day)`

genera el resultado en el minuto que fue ejecutado el codigo, en este caso es 42

### `Date.prototype.getMonth()`

Retorna el mes (`0`–`11`) para la fecha especificada acorde a la hora local.

`let day = new Date().getMonth();
console.log(day)`

el resultado es el mes en el que es ejecutado el codigo en este caso es el 1(Febrero)


### `Date.prototype.getSeconds()`

Retorna los segundos (`0`–`59`) para la fecha especificada acorde a la hora local.

`let day = new Date().getSeconds();
console.log(day)`

retorna el resultado cuando se ejecuta el codigo , en este caso es 34(Segundos)



### `Date.prototype.getTime()`

Retorna el valor númerico de la fecha especificada como el número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC. (Retona valores negativos para fechas previas.)

`let day = new Date().getTime();
console.log(day)`

retorna el resultado cuando se ejecuta el codigo en este caso  1707828605945

### `Date.prototype.getTimezoneOffset()`

Retona la diferencia horaria en minutos para la hora local.

`let day = new Date().getTimezoneOffset();
console.log(day)`

retorna como resultado cuando se ejecuta el codigo 300

### `Date.prototype.getUTCDate()`

Retorna el día (fecha) del mes (`1`–`31`) para la fecha especificada acorde a la hora local.

`let day = new Date().getUTCDate()` 

`console.log(day)`

da como resultado el dia en que fue ejecutado el codigo, en este caso el 13 (13 de febrero que se ejecuto el codigo)

### `Date.prototype.getUTCDay()`

Retona el día de la semana (`0`–`6`) para la fecha especificada en hora universal.

`let day = new Date().getUTCDay()` 

`console.log(day)`

retorna el dia que se ejecuto el codigo en este es el 2( Martes)

### `Date.prototype.getUTCFullYear()`

Retona el año (4 dígitos para años de 4 dígitos) para la fecha especificada acorde a la hora universal.

`let day = new Date().getUTCFullYear()` 

`console.log(day)`

retorna el año en el que fue ejecutado el codigo en este 2024

### `Date.prototype.getUTCHours()`

Retona la hora (`0`–`23`) para la fecha especificada acorde a la hora universal.

`let day = new Date().getUTCHours()` 

`console.log(day)`

retorna la hora que fue ejecutado el codigo en este caso el 13 ( 13 de febrero)

### `Date.prototype.getUTCMilliseconds()`

Retona los milisegundos (`0`–`999`) para la fecha especificada acorde a la hora universal.

`let day = new Date().getUTCMilliseconds()` 

`console.log(day)`

retorna los segundos en que fue ejecutado en este caso es 566

### `Date.prototype.getUTCMinutes()` (en-US)

Retorna los minutos (`0`–`59`) para la fecha especificada acorde a la hora universal.

`let day = new Date().getUTCMinutes()` 

`console.log(day)`

retorna los minutos en que fue ejecutado en este caso es 13

### `Date.prototype.getUTCMonth()` (en-US)

Retonar el mes (`0`–`11`) para la fecha especificada acorde a la hora universal.

`let day = new Date().getUTCMonth()` 

`console.log(day)`

retorna el mes en que fue ejecutado en este caso es 1

### `Date.prototype.getUTCSeconds()` (en-US)

Retorna los segundos (`0`–`59`) para la fecha especificada acorde a la hora universal.

`let day = new Date().getUTCSeconds()` 

`console.log(day)`

retorna los secundos en que fue ejecutado en este caso es 44

### `Date.prototype.getYear()` (en-US)

Retorna el año (usualmente de 2 a 3 dígitos) para la fecha especificada acorde a la hora local. Usa `getFullYear()`en su lugar

`let day = new Date().getUTCgetYear()` 

`console.log(day)`

retorna los años en que fue ejecutado en este caso es 124

### `Date.prototype.setDate()` (en-US)

Establece el día del mes para la fecha especificada acorde a la hora local.

`const event = new Date('August 19, 1975 23:15:30');`

`event.setDate(24);`

`console.log(event.getDate());`
// Expected output: 24

`event.setDate(32);`
// Only 31 days in August!

`console.log(event.getDate());`
// Expected output: 1

### `Date.prototype.setFullYear()`

Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha espefica acorde a la hora local.

`const event = new Date('August 19, 1975 23:15:30');`

`event.setFullYear(1969);`

`console.log(event.getFullYear());`
// Expected output: 1969

`event.setFullYear(0);`

`console.log(event.getFullYear());`
// Expected output: 0

### `Date.prototype.setHours()` (en-US)

Establece la hora para una fecha especifica acorde a la hora local.

`const event = new Date('August 19, 1975 23:15:30');`
`event.setHours(20);`

`console.log(event);`
// Expected output: "Tue Aug 19 1975 20:15:30 GMT+0200 (CEST)"
// Note: your timezone may vary

`event.setHours(20, 21, 22);`

`console.log(event);`
// Expected output: "Tue Aug 19 1975 20:21:22 GMT+0200 (CEST)"



### `Date.prototype.setMilliseconds()`

Establece los milisegundos para una fecha especifica acorde a la hora local.

`const event = new Date('August 19, 1975 23:15:30');`

`console.log(event.getMilliseconds());`
// Expected output: 0

`event.setMilliseconds(456);`

`console.log(event.getMilliseconds());`
// Expected output: 456



### `Date.prototype.setMinutes()` (en-US)

Establece los minutos para una fecha especifica acorde a la hora local.

`const event = new Date('August 19, 1975 23:15:30');`

`event.setMinutes(45);`

`console.log(event.getMinutes());`
// Expected output: 45

`console.log(event);`
// Expected output: "Tue Aug 19 1975 23:45:30 GMT+0200 (CEST)"
// Note: your timezone may vary

### `Date.prototype.setMonth()`

Establece el mes para una fecha especifica acorde a la hora local.

`const event = new Date('August 19, 1975 23:15:30');`

`event.setMonth(3);`

`console.log(event.getMonth());`
// Expected output: 3

`console.log(event);`
// Expected output: "Sat Apr 19 1975 23:15:30 GMT+0100 (CET)"
// Note: your timezone may vary



### `Date.prototype.setSeconds()` (en-US)

Establece los segundos para una fecha especifica acorde a la hora local.

`const event = new Date('August 19, 1975 23:15:30');`

`event.setSeconds(42);`

`console.log(event.getSeconds());`
// Expected output: 42

`console.log(event);`
// Expected output: "Sat Apr 19 1975 23:15:42 GMT+0100 (CET)"
// Note: your timezone may vary



### `Date.prototype.setTime()` (en-US)

Establece el objeto `Date` al tiempo representado por un número de milisegundos desde el 1 de Enero de 1970, 00:00:00 UTC. Usa números negativos para fechas previas.

`const launchDate = new Date('July 1, 1999, 12:00:00');`
`const futureDate = new Date();`
`futureDate.setTime(launchDate.getTime());`

`console.log(futureDate);`
// Expected output: "Thu Jul 01 1999 12:00:00 GMT+0200 (CEST)"

`const fiveMinutesInMillis = 5 * 60 * 1000;`
`futureDate.setTime(futureDate.getTime() + fiveMinutesInMillis);`

`console.log(futureDate);`
// Expected output: "Thu Jul 01 1999 12:05:00 GMT+0200 (CEST)"
// Note: your 

### `Date.prototype.setUTCDate()` (en-US)

Establece el día del mes para la fecha especificada acorde a la hora universal.

`const event = new Date('August 19, 1975 23:15:30 GMT-3:00');`

`console.log(event.getUTCDate());`
// Expected output: 20

`event.setUTCDate(19);`

`console.log(event.getUTCDate());`
// Expected output: 19



### `Date.prototype.setUTCFullYear()` (en-US)

Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha espefica acorde a la hora universal.

`const event = new Date('December 31, 1975 23:15:30 GMT-3:00');`

`console.log(event.getUTCFullYear());`
// Expected output: 1976

`console.log(event.toUTCString());`
// Expected output: "Thu, 01 Jan 1976 02:15:30 GMT"

`event.setUTCFullYear(1975);`

`console.log(event.toUTCString());`
// Expected output: "Wed, 01 Jan 1975 02:15:30 GMT"



### `Date.prototype.setUTCHours()` (en-US)

Establece la hora para una fecha especifica acorde a la hora universal.

`const event = new Date('August 19, 1975 23:15:30 GMT-3:00');`

`console.log(event.toUTCString());`
// Expected output: "Wed, 20 Aug 1975 02:15:30 GMT"

`console.log(event.getUTCHours());`
// Expected output: 2

`event.setUTCHours(23);`

`console.log(event.toUTCString());`
// Expected output: "Wed, 20 Aug 1975 23:15:30 GMT"



### `Date.prototype.setUTCMilliseconds()` (en-US)

Establece los milisegundos para una fecha especifica acorde a la hora universal.



`const date1 = new Date('2018-01-24T12:38:29.069Z');`

`console.log(date1.getUTCMilliseconds());`
// Expected output: 69

`date1.setUTCMilliseconds(420);`

`console.log(date1.getUTCMilliseconds());`
// Expected output: 420**

### `Date.prototype.setUTCMinutes()` (en-US)

Establece los minutos para una fecha especifica acorde a la hora universal.

`const date1 = new Date('December 31, 1975, 23:15:30 GMT+11:00');`

`console.log(date1.getUTCMinutes());`
// Expected output: 15

`date1.setUTCMinutes(25);`

`console.log(date1.getUTCMinutes());`
// Expected output: 25

### `Date.prototype.setUTCMonth()` (en-US)

Establece el mes para una fecha especifica acorde a la hora universal.

`const event = new Date('December 31, 1975 23:15:30 GMT-3:00');`

`console.log(event.toUTCString());`
// Expected output: "Thu, 01 Jan 1976 02:15:30 GMT"

`console.log(event.getUTCMonth());`
// Expected output: 0

`event.setUTCMonth(11);`

`console.log(event.toUTCString());`
// Expected output: "Wed, 01 Dec 1976 02:15:30 GMT"

### `Date.prototype.setUTCSeconds()` (en-US

Establece los segundos para una fecha especifica acorde a la hora universal.

`const date1 = new Date('December 31, 1975, 23:15:30 GMT+11:00');`

`console.log(date1.getUTCSeconds());`
// Expected output: 30

`date1.setUTCSeconds(39);`

`console.log(date1.getUTCSeconds());`
// Expected output: 39

### `Date.prototype.setYear()` (en-US)

Establece el año (usualmente de 2 a 3 dígitos) para una fecha especifica acorde a la hora local. Usa `setFullYear()` en su lugar.

`const theBigDay = new Date();`

`theBigDay.setYear(96);`
`theBigDay.setYear(1996);`
`theBigDay.setYear(2000);`



### `Date.prototype.toDateString()`

Retona la "fecha" del objeto `Date` como una cadena facil de leer por humanos `'Thu Apr 12 2018'`.

`const event = new Date(1993, 6, 28, 14, 39, 7);`

`console.log(event.toString());`
// Expected output: "Wed Jul 28 1993 14:39:07 GMT+0200 (CEST)"
// Note: your timezone may vary

`console.log(event.toDateString());`
// Expected output: "Wed Jul 28 1993"



### `Date.prototype.toISOString()`

Convierte una fecha a una cadena siguiendo el ISO 8601 de Formato Extendido.

`const event = new Date('05 October 2011 14:48 UTC');`
`console.log(event.toString());`
// Expected output: "Wed Oct 05 2011 16:48:00 GMT+0200 (CEST)"
// Note: your timezone may vary

`console.log(event.toISOString());`
// Expected output: "2011-10-05T14:48:00.000Z"



### `Date.prototype.toJSON()`

Retorna una cadena representando el objeto `Date`usando `toISOString()` Destinado a ser usado por `JSON.stringify()`

`const event = new Date('August 19, 1975 23:15:30 UTC');`

`const jsonDate = event.toJSON();`

`console.log(jsonDate);`
// Expected output: "1975-08-19T23:15:30.000Z"

`console.log(new Date(jsonDate).toUTCString());`
// Expected output: "Tue, 19 Aug 1975 23:15:30 GMT"

### `Date.prototype.toGMTString()` (en-US)

Retona una cadena representando el objeto `Date` basado en la zona horaria GMT (UTC). Usa `toUTCString()`en su lugar.



### `Date.prototype.toLocaleDateString()`

Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.

`const event = new Date(Date.UTC(2012, 11, 20, 3, 0, 0));`
`const options = {`
  `weekday: 'long',`
  `year: 'numeric',`
  `month: 'long',`
  `day: 'numeric',`
`};`

`console.log(event.toLocaleDateString('de-DE', options));`
// Expected output (varies according to local timezone): Donnerstag, 20. Dezember 2012

`console.log(event.toLocaleDateString('ar-EG', options));`
// Expected output (varies according to local timezone): الخميس، ٢٠ ديسمبر، ٢٠١٢

`console.log(event.toLocaleDateString(undefined, options));`
// Expected output (varies according to local timezone and default locale): Thursday, December 20, 2012



### `Date.prototype.toLocaleString()`

Retorna una cadena con una representación sensible a la localización de esta fecha. Sobrescribe el método `Object.prototype.toLocaleString()`

`const event = new Date(Date.UTC(2012, 11, 20, 3, 0, 0));`

// British English uses day-month-year order and 24-hour time without AM/PM
`console.log(event.toLocaleString('en-GB', { timeZone: 'UTC' }));`
// Expected output: "20/12/2012, 03:00:00"

// Korean uses year-month-day order and 12-hour time with AM/PM
`console.log(event.toLocaleString('ko-KR', { timeZone: 'UTC' }));`
// Expected output: "2012. 12. 20. 오전 3:00:00"



### `Date.prototype.toLocaleTimeString()`

Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.

// Depending on timezone, your results will vary
`const event = new Date('August 19, 1975 23:15:30 GMT+00:00');`

`console.log(event.toLocaleTimeString('en-US'));`
// Expected output: "1:15:30 AM"

`console.log(event.toLocaleTimeString('it-IT'));`
// Expected output: "01:15:30"

`console.log(event.toLocaleTimeString('ar-EG'));`
// Expected output: "١٢:١٥:٣٠ ص"

### `Date.prototype.toString()` (en-US)

Retorna una cadena representando el objeto especificado `Date`Sobrescribe el método `Object.prototype.toString()`

`const event = new Date('August 19, 1975 23:15:30');`

`console.log(event.toString());`
// Expected output: "Tue Aug 19 1975 23:15:30 GMT+0200 (CEST)"
// Note: your timezone may vary

### `Date.prototype.toTimeString()` (en-US)

Retona la porción de "tiempo" del objeto `Date`a una cadena legible para humanos.

`const event = new Date('August 19, 1975 23:15:30');`

`console.log(event.toTimeString());`
// Expected output: "23:15:30 GMT+0200 (CEST)"
// Note: your timezone may vary



### `Date.prototype.toUTCString()`

Convierte una fecha a una cadena usando la zona horaria UTC.

`const event = new Date('14 Jun 2017 00:00:00 PDT');`

`console.log(event.toUTCString());`
// Expected output: "Wed, 14 Jun 2017 07:00:00 GMT"

### `Date.prototype.valueOf()` (en-US)

Retona el valor primitivo de un objeto `Date`Sobrescribe el método `Object.prototype.valueOf()`

`const date1 = new Date(Date.UTC(96, 1, 2, 3, 4, 5));`

`console.log(date1.valueOf());`
// Expected output: 823230245000

`const date2 = new Date('02 Feb 1996 03:04:05 GMT');`

`console.log(date2.valueOf());`
// Expected output: 823230245000



 ## Ejemplos

### Distintas maneras de crear un objeto Date

Los siguientes ejemplos muestran distintas maneras de crear fechas en JavaScript:

**Nota:** Transformar las cadenas de fechas con el constructor `Date` (y `Date.parse`, son equivalentes) es escasamente recomendado debido las diferencias e inconsistencias entre navegadores.

`let today = new Date();`
`let birthday = new Date("December 17, 1995 03:24:00");`
`let birthday = new Date("1995-12-17T03:24:00");`
`let birthday = new Date(1995, 11, 17); // el mes es indexado como 0`
`let birthday = new Date(1995, 11, 17, 3, 24, 0);`
`let birthday = new Date(628021800000); // pasando la marca temporal de la época`

### Obtener fecha, mes y año u hora

`const date = new Date();`
`const [month, day, year] = [`
  `date.getMonth(),`
  `date.getDate(),`
  `date.getFullYear(),`
`];`
`const [hour, minutes, seconds] = [`
  `date.getHours(),`
  `date.getMinutes(),`
  `date.getSeconds(),`
`];`

### Interpretación de los años de dos dígitos

`new Date()` hereda de forma no deseada, comportamiento inconsistente con años expresados en dos dígitos, cuando una llamada `new Date()` es dada a un año expresado en dos dígitos, ese valor del año no es tratado como un año literal y usado como tal si no que es interpretado como una diferencia desde el año `1900`, pero en otros casos, como una diferencia desde el año `2000`.

`let date = new Date(98, 1); // Sun Feb 01 1998 00:00:00 GMT+0000 (GMT)`
`let date = new Date(22, 1); // Wed Feb 01 1922 00:00:00 GMT+0000 (GMT)`
`let date = new Date("2/1/22"); // Tue Feb 01 2022 00:00:00 GMT+0000 (GMT)`

`// Método heredado; siempre interpreta los años en dos digitos como relativos al 1900`
`date.setYear(98);`
`date.toString(); // Sun Feb 01 1998 00:00:00 GMT+0000 (GMT)`
`date.setYear(22);`
`date.toString(); // Wed Feb 01 1922 00:00:00 GMT+0000 (GMT)`

Por lo tanto, crear y obtener fechas entre los años `0` y `99`, preferiblemente usa los métodos `setFullYear()`y `getFullYear()`

// Método preferido; nunca interpreta ningun valor como una diferencia relativa,
// pero en su lugar valor del año tal y como está
`date.setFullYear(98);`
`date.getFullYear(); // 98 (no 1998)`
`date.setFullYear(22);`
`date.getFullYear(); // 22 (no 1922, no 2022)`



### Calculando el tiempo transcurrido

Los siguientes ejemplos muestran como determinar el tiempo transcurrido entre dos fechas JavaScript en milisegundos.

Debido a las diferentes duraciones de los días (debido a los cambios horarios para aprovechar la luz del sol), meses, y años, expresar el tiempo transcurrido en unidades mayores a horas, minutos y segundos requiere abordar un número de inconvenientes, y deberia ser revisado minuciosamente antes de intentarse.

// Usando objetos Date
`let start = Date.now();`

// El tiempo a expresar va aquí:
`doSomethingForALongTime();`
`let end = Date.now();`
`let elapsed = end - start;` // tiempo transcurrido en milisegundos

// Usando métodos internos
`let start = new Date();`

// El tiempo a expresar va aquí:
`doSomethingForALongTime();`
`let end = new Date();`
`let elapsed = end.getTime() - start.getTime();` // tiempo transcurrido en milisegundos

// Probar una función y regresar su valor
`function printElapsedTime(fTest) {`
  `let nStartTime = Date.now(),`
    `vReturn = fTest(),`
    `nEndTime = Date.now();`

  `console.log(`
    `Tiempo transcurrido: ${String(nEndTime - nStartTime)} milisegundos,`
  `);`
  `return vReturn;`
`}`

`let yourFunctionReturn = printElapsedTime(yourFunction);`

### Obtener el número de segundos desde la Época ECMAScript

`let seconds = Math.floor(Date.now() / 1000);`

En este caso, es más importante retornar únicamente un entero que una simple división no hará. Es también importante sólo retornar realmente el tiempo transcurrido. (Esa es la razón por la que este código usa `Math.floor()` y no `Math.round()`