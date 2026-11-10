# Simulador de Fase de Grupos del Mundial 

DESCRIPCIÓN GENERAL:
Durante la Copa Mundial de la FIFA 2026, los equipos compiten inicialmente en una fase de grupos. Cada grupo está conformado por 4 selecciones nacionales, las cuales juegan entre sí. Los equipos obtienen puntos de acuerdo con los resultados de cada partido y, al finalizar la fase, se genera una tabla de posiciones para determinar los clasificados a la siguiente etapa. 

Fase 0 – Equipos 
1. Crear un arreglo que contenga los nombres de los países que participan del Mundial de Futbol 2026.  
2. Solicite al usuario el ingreso de 4 paises (validar) para formar un grupo.  

Fase 1 – Partidos  
En esta etapa se simularán los partidos correspondientes a los países seleccionados. Cada equipo juega exactamente 3 partidos: uno contra cada uno de los otros 3 equipos del grupo. A esta etapa la llamaremos  "todos contra todos".  
1. Genere y muestre por pantalla los resultados de los 6 partidos. El número de goles será un 
número aleatorio entre 0 y 5 para cada equipo.  
2. Con los resultados de cada partido, llene los siguiente arreglos paralelos.  
o Goles a favor (GF) 
o Goles en contra (GC) 
o Puntos de acuerdo a las Reglas FIFA:  
    Victoria = 3 puntos al ganador, 0 al perdedor.  
    Empate = 1 punto para cada equipo. 
    Derrota = 0 puntos. 
3. Mostrar la tabla de posiciones sin ordenar.  

Fase 2 – Tabla de posiciones 
1. En esta fase se ordenará la tabla de posiciones, de acuerdo con los puntos ganados en la 
Fase 1. En caso de igualdad de puntos, el desempate es por diferencia de goles (GF - GC).  
2. Muestre la tabla de posiciones ordenada.  

Fase 3  - Clasificación 
Muestre por pantalla los equipos que clasifican a la siguiente etapa. (Los 2 primeros en la tabla de posiciones) 
