# Modulo-trafico
Este es el modulo de trafico permite mostrar en un mapa según el estado de las vías


## 1. Información que maneja

- Tráfico lento: se usa para mostrar que los carros avanzan despacio en cierto punto. Funciona para que otros usuarios eviten esa ruta.  
- Accidente: marca en qué lugar ocurrió un choque. Ayuda a desviar el tráfico.  
- Construcción: señala dónde hay obras en la vía. Importante para la ruta.  
- Vía libre: muestra que el camino está despejado. Es útil para confirmar cuál es la mejor opción.  
- Inseguridad (valor agregado): permite reportar zonas peligrosas (robos, protestas u otros eventos).  

Cada evento lleva:
- Tipo de evento (ejemplo: accidente).  
- Punto en el mapa (ubicación).  
- Fecha y hora.  


## 2. Operaciones del módulo

1. Ver mapa con el tráfico y eventos.  
2. Registrar eventos: accidente, construcción, inseguridad.  
3. Mostrar íconos según el evento.  
4. Filtrar eventos: ver solo accidentes, tráfico o solo inseguridad.  
5. Ver lista de eventos recientes con lugar y hora. 
6. Incluir filtro para ver solo un evento 
7. Pruebas y ajustes

## 3. Limitaciones

- Necesita internet para mostrar el mapa y los datos. 
- Si se usa Google Maps: el plan gratis es limitado.
- Depende de la comunidad: si nadie reporta, la información puede ser poca.  

## 4. Alcance inicial (primera versión)

 - Mostrar el mapa. 
- Permitir que el usuario registre un evento.  
- Ver íconos en el mapa.  
- Mostrar lista sencilla de eventos.  

Más adelante se puede mejorar con rutas alternativas.  


## 5. Cronograma de desarrollo

Semana Actividad:

1 Investigar APIs (Google Maps) y definir cuál usar.
2 Crear el mapa básico (solo mostrarlo). 
3  Hacer que se puedan registrar eventos.
4 Mostrar los eventos en el mapa con íconos.
5 Agregar la lista de eventos recientes.
6  Incluir filtro para ver solo un tipo de evento. 
7  Pruebas y ajustes. 

## 6. Valor agregado frente a Google Maps y Waze

- Incluir alertas de inseguridad (atracos, protestas).  
- Mostrar puntos de transporte público (paraderos, estaciones).
