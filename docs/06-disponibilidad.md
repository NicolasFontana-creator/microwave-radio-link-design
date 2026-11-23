# Desvanecimiento y disponibilidad estimada

El informe usa tres procedimientos con salidas diferentes. Para interpretarlos hay que identificar el mecanismo, el margen usado, la unidad de probabilidad y el criterio de error.

| Procedimiento | Entradas del TP | Resultado e interpretación |
|---|---|---|
| Margen empírico requerido | D = 5,88 km, f = 22,078 GHz, A = 1, B = 0,25, R = 0,9999 | 8,28 dB según la expresión del TP, para el objetivo especificado |
| Predicción de multitrayecto | KQ ≈ 1,2069 × 10⁻⁴, P₀ ≈ 0,5417, M = 27,78 dB | P(F) ≈ 9,03 × 10⁻⁴. El paso a porcentaje requiere confirmar la convención original |
| Plantilla antes de diversidad | Contribuciones por fading plano, selectivo y lluvia | Tiempo excedido total ≈ 0,126476 %, equivalente a una disponibilidad teórica de 99,873524 % bajo los supuestos de la plantilla |

Para el primer método el TP evalúa $30\log_{10}D+10\log_{10}(6ABf)-10\log_{10}(1-R)-70$. Para el segundo usa $P(F)=P_0 10^{-M/10}$ y $P_0=K_Q fD^3$. Si 0,00090315 representa una fracción, la disponibilidad sería 99,909685 %. Si representa un porcentaje, sería 99,999097 %. La definición de la fuente del modelo determina qué conversión corresponde.

La plantilla suma aproximadamente 0,0368561 % de desvanecimiento plano, 0,00001255 % selectivo y 0,08960758 % de lluvia. El criterio «cumple» asociado a 0,2 % para BER 10⁻⁶ difiere de la meta de 0,01 % de indisponibilidad. La cifra posterior a diversidad requiere justificar una arquitectura de diversidad. La línea BER 10⁻³ carece de un umbral utilizable. Ninguno de estos resultados constituye una serie de mediciones operativas.

Fuente primaria: TP, pp. 19–23 y 39. [Revisión técnica](revision-tecnica.md).
