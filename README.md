Proyecto



# Instalación
## Descargar los datos
- Clonar este repositorio en su computadora o descarguelo como ZIP
- Utilice alguna aplicación como Jupyter para abrir el contenido del documento.

# Background
Los datos utilizados en el proyecto se han extraído de la tabla de datos "On-Time Performance" de la base de datos "On-Time" de la biblioteca de datos "TranStats". Para más información visitar "https://www.transtats.bts.gov/Tables.asp?DB_ID=120".

# Breve descripción de los features
Con el fin de evitar ambigüedad se da una breve descrición de el significado de cada uno de los features.

- MONTH = Mes en el que ocurre el vuelo.
- DAY OF MONTH = Día del mes en que ocurre el vuelo.
- FL DATE = Fecha completa en que ocurre el vuelo
- UNIQUE CARRIER = Código asignado por IATA y comúnmente utilizado para identificar un transportista.
- ORIGIN = Aeropuerto del que proviene el vuelo.
- ORIGIN CITY NAME = Ciudad de la que proviene el vuelo.
- ORIGIN STATE ABR = Abreviación del estado del que proviene el vuelo.
- ORIGIN STATE NM = Nombre completo del estado del que proviene el vuelo.
- ORIGIN WAC = Código de área mundial del aeropuerto.
- DEST = Aeropuerto destino.
- DEST CITY NAME = Nombre de la ciudad donde se ubica el aeropuerto destino.
- DEST STATE ABR = Abreviación del nombre del estado donde se ubica el aeropuerto destino.
- DEST STATE NM = Nombre completo del estado donde se ubica el aeropuerto.
- DEST WAC = Código de área mundial del aeropuerto.
- DEP TIME = Hora real de salida (hora local: hhmm)
- DEP DELAY = Diferencia en minutos entre la hora programada y la hora real de salida. Esta diferencia puede ser negativa si el avión sale antes de la hora programada.
- DEP DELAY NEW = Es un análogo de DEP DELAY pero considera el salir temprano como 0.
- DEP DEL 15 = Es una indicadora. Su valor es 1 si hubo más de 15 minutos de atraso en la hora de salida y 0 si no.
- DEP DELAY GROUP = Intervalos de retardo de salida (cada 15 minutos desde <-15 hasta > 180).
- DEP TIME BLK = Bloque de tiempo de salida, intervalos por hora.
- ARR TIME = Hora real de llegada (hora local: hhmm).
- ARR DELAY = Diferencia en minutos entre la hora programada y al hora de llegada real. Si llega antes entonces se usan números negativos.
- ARR DEL 15 = Es una indicadora. Su valor es 1 si hubo más de 15 minutos de atraso en la hora de llegada y 0 si no.
- ARR DELAY GROUP = Intervalos de retardo de llegada (cada 15 minutos desde <-15 hasta > 180).
- DEP TIME BLK = Bloque de tiempo de llegada, intervalos por hora.
- CANCELLED = Es una indicadora. Su valor es 1 si se canceló el vuelo y 0 si no.
- DIVERTED = Es una indicadora. Su valor es 1 si hubo alguna desviación y 0 si no.
- ACTUAL ELAPSED TIME = Tiempo efectivo del vuelo en minutos.
- FLIGHTS = Número de vuelos.
- DISTANCE = Distancia entre los aeropuertos en (millas).
- DISTANCE GROUP = Distancia en intervalos, cada 250 millas.
- CARRIER DELAY = Atraso del operador, en minutos.
- WEATHER DELAY = Atraso por el clima, en minutos.
- NAS DELAY = Atraso por el sistema de aire nacional, en minutos.
- SECURITY DELAY = Atraso por seguridad, en minutos.
- LATE AIRCRAFT DELAY = Atraso por avión atrasado, en minutos.
