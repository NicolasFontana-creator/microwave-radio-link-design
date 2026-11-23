# Revisión técnica del informe académico

Las páginas corresponden al TP de Fontana y Terlin. «Verificado» indica que se comprobó la operación o relación indicada. La trazabilidad de equipos y la aplicabilidad física se evalúan por separado.

| Dato original y página | Problema | Verificación efectuada | Corrección propuesta | Estado |
|---|---|---|---|---|
| 5,88 km en el perfil y 6,15 km en el anexo (pp. 13–19, 41–43) | Cambian las distancias parciales y la geometría | Para el obstáculo a 2,44 km quedan 3,44 o 3,71 km | Fijar los extremos de referencia y regenerar el perfil | Pendiente |
| F1 = 4,4 m, F2 = 6,22 m, cálculo a 23 GHz (pp. 16–18, 41–43) | El cuerpo menciona 22 GHz y el anexo parte de 25 m | Para 5,88 km, 22,078 GHz y alturas 23/12 m se obtienen 82,7 % y 71,4 % de F1 libre a 2,44 km según k | Repetir el cálculo punto por punto con el perfil acordado | Pendiente |
| 0,03 km en tabla 4 y 0,30 km en plantilla (pp. 14, 22) | La identificación del obstáculo que genera 6,02 dB es ambigua | Se contrastaron posición y despejamiento registrados | Vincular cada fila de la plantilla a un obstáculo del perfil | Requiere información adicional |
| −41,72 y −47,68 dBm (pp. 19, 22) | Los dos presupuestos usan pérdidas diferentes | 22 + 71 − 134,72 = −41,72 y 22 + 71 − 140,68 = −47,68 | Presentar ambos casos y sus hipótesis; conservar la diferencia de redondeo de 0,01 dB en la plantilla | Verificado |
| Margen 27,78 dBm (p. 19) | La diferencia de niveles absolutos es relativa | −41,72 − (−69,5) = 27,78 | Expresar el margen en dB | Verificado |
| 22 dBm y −69,5 dBm para 128-QAM (pp. 19, 22, 47–49) | La correspondencia completa entre variante, banda y BER no se acredita con la tabla recortada | Se contrastaron tabla 7, figuras del fabricante y entrada de plantilla; BER 10⁻³ figura sin umbral válido | Conservar como entradas del diseño; obtener tabla completa y referencia RFU | Requiere información adicional |
| Atenuación de lluvia de 24,46 dB (pp. 19–22) | El cálculo y la plantilla emplean pares de coeficientes diferentes | (0,1155; 1,0329) frente a (0,0946; 1,0813). El primer par reproduce aproximadamente 5,48 dB/km | Unificar frecuencia, polarización, fuente climática y modelo | Pendiente |
| P(F) ≈ 0,00090315 y disponibilidad próxima a 99,999 % (p. 21) | La conversión depende de si P(F) es fracción o porcentaje | Las dos interpretaciones arrojan 99,909685 % o 99,999097 % | Recuperar la definición de unidades del modelo | Requiere información adicional |
| Tiempo excedido total antes de diversidad (p. 22) | La condición «cumple» usa un criterio distinto del objetivo de 99,99 % | La suma de los componentes es 0,126476 %; su complemento es 99,873524 % | Identificar BER, objetivo y arquitectura al informar cada cifra | Verificado |
| SC1-220, montaje directo y 0 dB de alimentador (pp. 43–45, 50–51) | Compatibilidad y pérdida dependen del kit; el anexo incluye 2+0 | Se distinguieron diámetro, ganancia y supuestos de montaje de la configuración propuesta | Obtener referencia de antena, RFU, interfaz y adaptador | Requiere información adicional |
| 35 m de CAT6 de 24 AWG (pp. 34–38, 51–56) | La tabla de distancias especifica otras combinaciones | La pérdida a 100 MHz pertenece al cable de datos; 19,9 × 0,35 = 6,965 dB | Confirmar categoría, calibre, blindaje y alimentación con la referencia de cable | Requiere información adicional |
| Canal 9 y par dúplex (pp. 43–49) | La canalización y la autorización para operar son cuestiones distintas | El arreglo citado reproduce 21.462 y 22.694 MHz y 1.232 MHz de separación | Identificar el par como dato académico | Verificado |

[Fuentes y alcance del diseño](08-conclusiones-y-referencias.md).
