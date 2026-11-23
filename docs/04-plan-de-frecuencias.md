# Plan de frecuencias y capacidad

El ejercicio utiliza dos portadoras para transmisión y recepción simultáneas (FDD). En el arreglo utilizado de UIT-R F.637-5, con referencia de 21.196 MHz e índice 9, se obtienen los siguientes centros de canal.

| Rama | Cálculo en MHz | Frecuencia |
|---|---|---:|
| Baja | 21.196 + 14 + 28 × 9 | 21,462 GHz |
| Alta | 21.196 + 1.246 + 28 × 9 | 22,694 GHz |

La separación dúplex es 1.232 MHz. El canal ocupa nominalmente 28 MHz. El informe emplea la media de 22,078 GHz para el balance analítico. El par pertenece al ejercicio académico. Una asignación administrativa para operar requeriría documentación específica.

| Estado de modulación | Capacidad indicada en la tabla 7 | Potencia adoptada | Sensibilidad indicada |
|---|---:|---:|---:|
| 64-QAM | 139–170 Mbit/s | 22 dBm | −73 dBm |
| 128-QAM | 167–205 Mbit/s | 22 dBm | −69,5 dBm |

El límite inferior de 128-QAM supera la meta de 155 Mbit/s. El intervalo de 64-QAM contiene la meta y su extremo inferior queda por debajo. Deben confirmarse el perfil de capacidad Ethernet y el umbral de la variante de radio para el BER elegido.

Fuente primaria: TP, tabla 7 y pp. 43–49. [UIT-R F.637-5](https://www.itu.int/rec/R-REC-F.637-5-202202-I/en).
