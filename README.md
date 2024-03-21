# tp1-orgaDatos
75.06/95.58 Organización de Datos

# airline_data.csv
| # | Columna | Descripción |
| --- | --- | --- |
| 1 | reviews | Contiene el texto de las revisiones de los vuelos. Los pasajeros han compartido sus experiencias y opiniones sobre los vuelos en esta columna.|
|2| rates | Indica las calificaciones otorgadas por los revisores a los vuelos. Parece ser una escala de calificación del 1 al 10, donde 10 podría indicar una experiencia excelente y 1 podría indicar una experiencia muy pobre.|
|3| date | Fecha en que se realizó la revisión del vuelo. Está en un formato de fecha que incluye el día, el mes y el año. de la aerolínea.|
|4| country | País del revisor que dejó la revisión del vuelo. Indica el país de origen del pasajero que realizó la revisión.|

# cleaned-reviews.csv
El conjunto de datos "cleaned-reviews.csv" parece ser una versión limpia y modificada del conjunto de datos original "airline_data.csv"
| # | Columna | Descripción |
| --- | --- | --- |
| 1 | reviews | Contiene el texto de las revisiones de los vuelos. Los pasajeros han compartido sus experiencias y opiniones sobre los vuelos en esta columna.|
|2| rates | Indica las calificaciones otorgadas por los revisores a los vuelos. Parece ser una escala de calificación del 1 al 10, donde 10 podría indicar una experiencia excelente y 1 podría indicar una experiencia muy pobre.|
|3| date | Fecha en que se realizó la revisión del vuelo. Formato de fecha ("YYYY-MM-DD") en comparación con el conjunto de datos original.|
|4| country | País del revisor que dejó la revisión del vuelo. Indica el país de origen del pasajero que realizó la revisión.|
|5| verified | Indicar si la revisión ha sido verificada o no. Es una columna booleana donde "True" indica que la revisión ha sido verificada y "False" indica lo contrario.|
|6| comments | Comentarios adicionales asociados con las revisiones de los vuelos. Puede incluir detalles específicos sobre la experiencia del pasajero.|

# customer_airways_data.csv
| # | Columna | Descripción |
| --- | --- | --- |
|1| Num_passengers | Cantidad de pasajeros que viajaron|
|2| Sales_channel | Canal de venta por el cual fue realizada la reserva.|
|3| Trip_type | Puede ser Round Trip (ida y vuelta), One way (solo ida) o Circle trip (secuencia de tramos)|
|4| Purchase_lead | Número de días entre el momento de la reserva y el momento del viaje |
|5| Lenght_of_stay | Número de días en el destino antes del regreso.|
|6| Flight_hour | Horario de partida del vuelo.|
|7| Flight_day | Dia de la semana de partida del vuelo.|
|8| Route | Destino.|
|9| Booking_origin | País desde donde se realizó la reserva.|
|10| Wants_extra_bags | Si el cliente solicitó equipaje extra al hacer la reserva. Si (1) o no (0).|
|11| wants_preferred_seat | Es una columna binaria que indica si el pasajero desea un asiento preferencial (1) o no (0).|
|12| wants_in_flight_meals | Es una columna binaria que indica si el pasajero desea comidas durante el vuelo (1) o no (0) |
|13| flight_duration | Representa la duración del vuelo en horas. |
|14| booking_complete | Es una columna binaria que indica si la reserva del vuelo está completa (1) o no (0). |

# filtered_customer_booking.csv
El conjunto de datos "filtered_customer_booking.csv" parece ser una versión limpia y modificada del conjunto de datos original "customer_airways_data.csv". 
La columna "flight_day" ha cambiado de string a int (dias de la semana).
