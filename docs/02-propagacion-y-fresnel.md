# Propagación, curvatura y zonas de Fresnel

Para un obstáculo situado a distancias $d_1$ y $d_2$ de las estaciones, con $D=d_1+d_2$, el radio de la zona de orden $n$ es

$$r_n=\sqrt{\frac{n\lambda d_1 d_2}{D}},\qquad \lambda=c/f.$$

En esta ecuación las longitudes se expresan en metros. En el modelo de radio terrestre efectivo, la protuberancia es $b=d_1d_2/(2kR_T)$ con $R_T=6371$ km y unidades homogéneas. Se suma al obstáculo para compararlo con la recta entre centros de antena. El despejamiento relativo de la primera zona es $(h_{haz}-h_{obst}-b)/r_1$.

**Reproducción en un punto.** A 2,44 km, con $D=5{,}88$ km y $f=22{,}078$ GHz, la recta entre 138 y 84,1 m pasa a 115,63 m. Para una copa a 111,5 m resulta $r_1=4{,}40$ m.

| Factor k | Protuberancia | Despejamiento vertical aproximado | Fracción de F1 libre |
|---|---:|---:|---:|
| 4/3 | 0,49 m | 3,64 m | 82,7 % |
| 2/3 | 0,99 m | 3,15 m | 71,4 % |

El informe indica más de 100 % y 91 % de despejamiento de F1, respectivamente, y 27 % de obstrucción de F2 para k = 4/3. El anexo obtiene radios de 4,4 y 6,22 m con 6,15 km y 23 GHz. Al deducir alturas parte de 25 m en Villa Fontana y obtiene 11,2 m en el otro extremo. El diseño adopta 23 y 12 m. La tabla anterior reproduce un punto con los parámetros adoptados. Para validar todo el vano se necesita reconciliar el perfil de origen y verificar todos los obstáculos.

Fuente primaria: TP, pp. 14–18 y 41–43. [Revisión de discrepancias](revision-tecnica.md).
