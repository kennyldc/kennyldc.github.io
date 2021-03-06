# kennyldc.github.io

<h1>Resultados de las Regresiones Base (Panel_horarios)</h1>

<p>En estas tablas incluyo dos tipos de delitos seleccionados de la lista que investiga la Fiscalía. 
Los delitos "Tipo 1" son aquellos que están vinculados directamente con algún asesinato intencional es decir: 
Feminicidio, feminicidio por arma blanca, feminicidio por disparo de arma de fuego, feminicidio por golpes, 
homicidio por ahorcamiento, homicidio por arma blanca, homicidio por arma de fuego, homicidio por golpes y homicidios intencionales (otros). 
En el delito "Tipo 2" solo se incluye: "Violencia Familiar". 

Por la inclusion del analisis de efectos heterogeneos, se presentan ahora dos tipos de modelos distintos. 
En el primero se incluyen unicamente los efectos fijos por escuela y anio. Los errores se agrupan por escuela.
En el segundo, se quitan los efectos fijos y se corre una regresion simple (MCO) del efecto de la violencia controlando por a) tipo de financiamiento (públicas vs privadas), 
b) Turno (matutino y vespertino) y c) Rezago socioeconómico (Carencias Educativas y de Ingreso - Nivel de educacion y posesion de bienes; Carencias de servicios en vivienda- Cracateristicas fisicas de la vivienda). 
De este segundo modelo se incluyen interacciones con la violencia. Todos los errores de los coeficientes estan agrupados a nivel escuela.

Las variables de respuesta del estudio (resultados de la prueba Planea) pueden ser 2, segun la aptitud academica X  1) Prueba Lenguaje y Comunicacion (LYC)
y 2) Prueba Matematicas (MAT).

Por la construccion teorica del analisis, en esta pagina solo se presentan los datos tipo panel discriminando el horario en el que se cometen los delitos.
En el panel solo se incluyen los delitos según el tipo y turno de escuela X  1) las primarias matutinas de 7:30 a 16:30; b) Primarias Vespertinas de 13:30 a 21:30; 
c) Secundarias Matutinas 6:30 a 16:50; y d) Secundarias Vespertinas 13:30 a 21:30. Este database se identifica como: "panel_horarios" 

En otro HTML se incluyen los mismos modelos pero de la base panel que no discrimina por horarios.</p>

<h2> Efecto de los asesinatos intencionales (delitos tipo 1) alrededor de la escuela sobre la prueba LYC </h2>
<h3> Modelo con Efectos Fijos por escuela y año con errores agrupados por escuela </h3>

<table style="text-align:center"><tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="9"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="9" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td colspan="9">lyc</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td><td>(6)</td><td>(7)</td><td>(8)</td><td>(9)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Homicidios_d250_t90h</td><td>-1.496<sup>**</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.697)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h</td><td></td><td>-1.087<sup>***</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.358)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h</td><td></td><td></td><td>-0.435<sup>**</sup></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.188)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h</td><td></td><td></td><td></td><td>-0.574</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(1.379)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h</td><td></td><td></td><td></td><td></td><td>-0.519</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.654)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h</td><td></td><td></td><td></td><td></td><td></td><td>-0.215</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.347)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-1.057</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.047)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.953</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.950)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.008</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.534)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr></table>

<h3> Modelo MCO-OLS con errores agrupados por escuela </h3>

<table style="text-align:center"><tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="9"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="9" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td colspan="9">lyc</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td><td>(6)</td><td>(7)</td><td>(8)</td><td>(9)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Homicidios_d250_t90h</td><td>-3.245<sup>**</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(1.527)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h</td><td></td><td>-2.106<sup>***</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.796)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h</td><td></td><td></td><td>-0.904<sup>*</sup></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.473)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h</td><td></td><td></td><td></td><td>0.058</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(4.012)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h</td><td></td><td></td><td></td><td></td><td>-0.564</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(1.438)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h</td><td></td><td></td><td></td><td></td><td></td><td>-0.314</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.857)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-4.512</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(5.472)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-1.985</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.830)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.518</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.105)</td></tr>
<tr><td style="text-align:left">Publica</td><td>-17.576<sup>***</sup></td><td>-17.502<sup>***</sup></td><td>-17.365<sup>***</sup></td><td>-17.550<sup>***</sup></td><td>-17.504<sup>***</sup></td><td>-17.444<sup>***</sup></td><td>-17.570<sup>***</sup></td><td>-17.530<sup>***</sup></td><td>-17.477<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.348)</td><td>(0.353)</td><td>(0.371)</td><td>(0.345)</td><td>(0.346)</td><td>(0.351)</td><td>(0.345)</td><td>(0.346)</td><td>(0.350)</td></tr>
<tr><td style="text-align:left">Vespertina</td><td>1.564</td><td>1.188</td><td>1.230</td><td>1.620</td><td>1.632</td><td>1.031</td><td>1.611</td><td>1.608</td><td>1.614</td></tr>
<tr><td style="text-align:left"></td><td>(2.997)</td><td>(3.191)</td><td>(3.211)</td><td>(3.000)</td><td>(2.997)</td><td>(2.952)</td><td>(3.000)</td><td>(3.000)</td><td>(3.000)</td></tr>
<tr><td style="text-align:left">Carencias Educativas y de Ingreso</td><td>0.947<sup>***</sup></td><td>0.918<sup>***</sup></td><td>0.925<sup>***</sup></td><td>0.953<sup>***</sup></td><td>0.933<sup>***</sup></td><td>0.941<sup>***</sup></td><td>0.952<sup>***</sup></td><td>0.943<sup>***</sup></td><td>0.944<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.092)</td><td>(0.093)</td><td>(0.093)</td><td>(0.092)</td><td>(0.093)</td><td>(0.094)</td><td>(0.092)</td><td>(0.092)</td><td>(0.093)</td></tr>
<tr><td style="text-align:left">Carencias de servicios en vivienda</td><td>-1.026<sup>***</sup></td><td>-1.035<sup>***</sup></td><td>-1.073<sup>***</sup></td><td>-1.048<sup>***</sup></td><td>-1.049<sup>***</sup></td><td>-1.052<sup>***</sup></td><td>-1.056<sup>***</sup></td><td>-1.072<sup>***</sup></td><td>-1.063<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.223)</td><td>(0.229)</td><td>(0.231)</td><td>(0.223)</td><td>(0.226)</td><td>(0.234)</td><td>(0.223)</td><td>(0.225)</td><td>(0.227)</td></tr>
<tr><td style="text-align:left">Publica X Vespertina</td><td>-8.952<sup>***</sup></td><td>-8.775<sup>***</sup></td><td>-8.781<sup>***</sup></td><td>-8.952<sup>***</sup></td><td>-9.079<sup>***</sup></td><td>-8.443<sup>***</sup></td><td>-8.965<sup>***</sup></td><td>-9.015<sup>***</sup></td><td>-9.058<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(3.016)</td><td>(3.209)</td><td>(3.231)</td><td>(3.018)</td><td>(3.015)</td><td>(2.973)</td><td>(3.019)</td><td>(3.018)</td><td>(3.019)</td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Publica</td><td>-0.353</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(1.858)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Carencias Educativas y de Ingreso</td><td>0.425</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.816)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Carencias de servicios en vivienda</td><td>0.749</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(2.020)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Vespertina</td><td>4.284</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(3.436)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Publica X Vespertina</td><td>-2.652</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(3.737)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Publica</td><td></td><td>-0.592</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.900)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Carencias Educativas y de Ingreso</td><td></td><td>0.566<sup>*</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.320)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Carencias de servicios en vivienda</td><td></td><td>0.991</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.767)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Vespertina</td><td></td><td>4.052</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(4.792)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Publica X Vespertina</td><td></td><td>-1.899</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(4.843)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Publica</td><td></td><td></td><td>-0.490</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.517)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Carencias Educativas y de Ingreso</td><td></td><td></td><td>0.160</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.147)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Carencias de servicios en vivienda</td><td></td><td></td><td>0.576<sup>*</sup></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.334)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Vespertina</td><td></td><td></td><td>1.484</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(3.158)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Publica X Vespertina</td><td></td><td></td><td>-0.918</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(3.176)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Publica</td><td></td><td></td><td></td><td>-4.390</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(4.580)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td>0.242</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(1.648)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td>1.296</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(3.828)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Vespertina</td><td></td><td></td><td></td><td>0.944</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(4.842)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td>-1.063</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(5.112)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Publica</td><td></td><td></td><td></td><td></td><td>-2.246</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(1.770)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td>0.814<sup>*</sup></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.457)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td>0.529</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(1.120)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Vespertina</td><td></td><td></td><td></td><td></td><td>1.414</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(3.348)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td>1.526</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(3.647)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Publica</td><td></td><td></td><td></td><td></td><td></td><td>-1.240</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.967)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td>0.144</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.288)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td>0.391</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.616)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td>8.662<sup>***</sup></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(3.074)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td>-7.979<sup>**</sup></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(3.160)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-4.401</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(8.773)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.580</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.557)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td>6.149</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(8.924)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td>4.425</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(6.834)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-4.275</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(7.349)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-3.897<sup>*</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.334)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>1.224<sup>*</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.664)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>3.945<sup>**</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.910)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>1.406</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(3.682)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>2.482</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(4.531)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-2.342<sup>*</sup></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.295)</td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.204</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.463)</td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>1.067</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.102)</td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>1.627</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(3.212)</td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.396</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(3.459)</td></tr>
<tr><td style="text-align:left">Constant</td><td>63.026<sup>***</sup></td><td>63.124<sup>***</sup></td><td>63.174<sup>***</sup></td><td>62.950<sup>***</sup></td><td>62.971<sup>***</sup></td><td>62.980<sup>***</sup></td><td>62.957<sup>***</sup></td><td>62.968<sup>***</sup></td><td>62.965<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.276)</td><td>(0.279)</td><td>(0.295)</td><td>(0.274)</td><td>(0.274)</td><td>(0.278)</td><td>(0.273)</td><td>(0.274)</td><td>(0.278)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.487</td><td>0.488</td><td>0.488</td><td>0.487</td><td>0.487</td><td>0.487</td><td>0.487</td><td>0.487</td><td>0.487</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.487</td><td>0.488</td><td>0.488</td><td>0.486</td><td>0.487</td><td>0.487</td><td>0.486</td><td>0.487</td><td>0.487</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr></table>

<h2> Efecto de la violencia familiar (delitos tipo 2) alrededor de la escuela sobre la prueba LYC </h2>
<h3> Modelo con Efectos Fijos por escuela y año con errores agrupados por escuela </h3>

<table style="text-align:center"><tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="9"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="9" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td colspan="9">lyc</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td><td>(6)</td><td>(7)</td><td>(8)</td><td>(9)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Violencia Familiar_d250_t90h</td><td>-0.098</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.109)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h</td><td></td><td>0.011</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.056)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h</td><td></td><td></td><td>-0.023</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.029)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h</td><td></td><td></td><td></td><td>-0.204</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.192)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h</td><td></td><td></td><td></td><td></td><td>0.024</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.102)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h</td><td></td><td></td><td></td><td></td><td></td><td>-0.040</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.053)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.139</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.332)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.053</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.175)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.037</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.094)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td><td>0.828</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td><td>0.695</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr></table>

<h3> Modelo MCO-OLS con errores agrupados por escuela </h3>

<table style="text-align:center"><tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="9"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="9" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td colspan="9">lyc</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td><td>(6)</td><td>(7)</td><td>(8)</td><td>(9)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Violencia Familiar_d250_t90h</td><td>0.040</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.231)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h</td><td></td><td>0.114</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.101)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h</td><td></td><td></td><td>0.006</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.039)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h</td><td></td><td></td><td></td><td>-0.032</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.419)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h</td><td></td><td></td><td></td><td></td><td>0.175</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.205)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h</td><td></td><td></td><td></td><td></td><td></td><td>0.013</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.088)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td>1.307<sup>*</sup></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.694)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.510</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.342)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.260<sup>*</sup></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.158)</td></tr>
<tr><td style="text-align:left">Publica</td><td>-17.224<sup>***</sup></td><td>-16.529<sup>***</sup></td><td>-16.714<sup>***</sup></td><td>-17.420<sup>***</sup></td><td>-16.979<sup>***</sup></td><td>-17.017<sup>***</sup></td><td>-17.438<sup>***</sup></td><td>-17.334<sup>***</sup></td><td>-17.189<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.410)</td><td>(0.512)</td><td>(0.645)</td><td>(0.371)</td><td>(0.435)</td><td>(0.544)</td><td>(0.354)</td><td>(0.384)</td><td>(0.454)</td></tr>
<tr><td style="text-align:left">Vespertina</td><td>1.725</td><td>1.086</td><td>1.283</td><td>0.753</td><td>-0.997</td><td>-3.832</td><td>0.469</td><td>-1.178</td><td>-0.867</td></tr>
<tr><td style="text-align:left"></td><td>(2.757)</td><td>(3.098)</td><td>(3.269)</td><td>(2.874)</td><td>(2.727)</td><td>(3.847)</td><td>(2.867)</td><td>(2.459)</td><td>(3.555)</td></tr>
<tr><td style="text-align:left">Carencias Educativas y de Ingreso</td><td>1.000<sup>***</sup></td><td>0.941<sup>***</sup></td><td>1.023<sup>***</sup></td><td>0.930<sup>***</sup></td><td>0.897<sup>***</sup></td><td>0.957<sup>***</sup></td><td>0.955<sup>***</sup></td><td>0.934<sup>***</sup></td><td>0.916<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.099)</td><td>(0.112)</td><td>(0.124)</td><td>(0.098)</td><td>(0.101)</td><td>(0.112)</td><td>(0.093)</td><td>(0.096)</td><td>(0.102)</td></tr>
<tr><td style="text-align:left">Carencias de servicios en vivienda</td><td>-0.899<sup>***</sup></td><td>-0.780<sup>***</sup></td><td>-0.661<sup>**</sup></td><td>-1.102<sup>***</sup></td><td>-1.062<sup>***</sup></td><td>-0.925<sup>***</sup></td><td>-0.999<sup>***</sup></td><td>-0.905<sup>***</sup></td><td>-0.740<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.245)</td><td>(0.278)</td><td>(0.307)</td><td>(0.243)</td><td>(0.254)</td><td>(0.279)</td><td>(0.227)</td><td>(0.235)</td><td>(0.250)</td></tr>
<tr><td style="text-align:left">Publica X Vespertina</td><td>-9.468<sup>***</sup></td><td>-9.182<sup>***</sup></td><td>-9.241<sup>***</sup></td><td>-8.279<sup>***</sup></td><td>-6.632<sup>**</sup></td><td>-4.030</td><td>-7.768<sup>***</sup></td><td>-6.185<sup>**</sup></td><td>-6.688<sup>*</sup></td></tr>
<tr><td style="text-align:left"></td><td>(2.786)</td><td>(3.135)</td><td>(3.319)</td><td>(2.897)</td><td>(2.758)</td><td>(3.878)</td><td>(2.887)</td><td>(2.487)</td><td>(3.582)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Publica</td><td>-0.336</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.257)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Carencias Educativas y de Ingreso</td><td>-0.104</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.098)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Carencias de servicios en vivienda</td><td>-0.257</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.243)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Vespertina</td><td>-0.245</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(9.068)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Publica X Vespertina</td><td>0.622</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(9.073)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Publica</td><td></td><td>-0.299<sup>***</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.116)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Carencias Educativas y de Ingreso</td><td></td><td>0.001</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.038)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Carencias de servicios en vivienda</td><td></td><td>-0.092</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.092)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Vespertina</td><td></td><td>0.891</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(2.695)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Publica X Vespertina</td><td></td><td>-0.706</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(2.697)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Publica</td><td></td><td></td><td>-0.063</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.045)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Carencias Educativas y de Ingreso</td><td></td><td></td><td>-0.010</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.014)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Carencias de servicios en vivienda</td><td></td><td></td><td>-0.040</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.033)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Vespertina</td><td></td><td></td><td>0.084</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.409)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Publica X Vespertina</td><td></td><td></td><td>-0.053</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.412)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Publica</td><td></td><td></td><td></td><td>-0.447</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.484)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td>0.142</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.172)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td>0.321</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.408)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Vespertina</td><td></td><td></td><td></td><td>12.731</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(16.656)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td>-12.182</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(16.663)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Publica</td><td></td><td></td><td></td><td></td><td>-0.515<sup>**</sup></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.238)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td>0.090</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.076)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td>0.085</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.180)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Vespertina</td><td></td><td></td><td></td><td></td><td>6.979<sup>**</sup></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(3.413)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td>-6.806<sup>**</sup></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(3.422)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Publica</td><td></td><td></td><td></td><td></td><td></td><td>-0.125</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.104)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td>0.001</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.033)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td>-0.027</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.078)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td>2.682<sup>*</sup></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(1.409)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td>-2.575<sup>*</sup></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(1.414)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-1.215</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.808)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.030</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.277)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.876</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.685)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td>35.434<sup>***</sup></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.934)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-36.190<sup>***</sup></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(3.021)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.579</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.401)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.029</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.146)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.554</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.348)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>20.494<sup>***</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(7.278)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-20.654<sup>***</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(7.292)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.247</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.193)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.008</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.066)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.308<sup>*</sup></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.162)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>3.860<sup>*</sup></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.116)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-3.742<sup>*</sup></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.128)</td></tr>
<tr><td style="text-align:left">Constant</td><td>62.957<sup>***</sup></td><td>62.655<sup>***</sup></td><td>62.943<sup>***</sup></td><td>62.944<sup>***</sup></td><td>62.758<sup>***</sup></td><td>62.909<sup>***</sup></td><td>62.826<sup>***</sup></td><td>62.798<sup>***</sup></td><td>62.633<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.327)</td><td>(0.409)</td><td>(0.523)</td><td>(0.298)</td><td>(0.349)</td><td>(0.440)</td><td>(0.283)</td><td>(0.307)</td><td>(0.365)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.487</td><td>0.488</td><td>0.487</td><td>0.487</td><td>0.488</td><td>0.487</td><td>0.488</td><td>0.488</td><td>0.488</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.487</td><td>0.487</td><td>0.487</td><td>0.486</td><td>0.487</td><td>0.487</td><td>0.487</td><td>0.487</td><td>0.487</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr></table>

<h2> Efecto de los asesinatos intencionales (delitos tipo 1) alrededor de la escuela sobre la prueba MAT </h2>
<h3> Modelo con Efectos Fijos por escuela y año con errores agrupados por escuela </h3>

<table style="text-align:center"><tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="9"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="9" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td colspan="9">mat</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td><td>(6)</td><td>(7)</td><td>(8)</td><td>(9)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Homicidios_d250_t90h</td><td>-1.380</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.870)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h</td><td></td><td>-0.875<sup>*</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.485)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h</td><td></td><td></td><td>-0.182</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.235)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h</td><td></td><td></td><td></td><td>-0.422</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(1.765)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h</td><td></td><td></td><td></td><td></td><td>-1.247</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.902)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h</td><td></td><td></td><td></td><td></td><td></td><td>-0.509</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.453)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-3.483</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.981)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-2.443<sup>*</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.372)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.368</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.697)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.643</td><td>0.643</td><td>0.642</td><td>0.642</td><td>0.643</td><td>0.643</td><td>0.643</td><td>0.643</td><td>0.642</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr></table>

<h3> Modelo MCO-OLS con errores agrupados por escuela </h3>

<table style="text-align:center"><tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="9"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="9" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td colspan="9">mat</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td><td>(6)</td><td>(7)</td><td>(8)</td><td>(9)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Homicidios_d250_t90h</td><td>-5.345<sup>***</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(1.936)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h</td><td></td><td>-3.157<sup>***</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(1.049)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h</td><td></td><td></td><td>-1.481<sup>***</sup></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.568)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h</td><td></td><td></td><td></td><td>-2.949</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(4.622)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h</td><td></td><td></td><td></td><td></td><td>-3.738<sup>**</sup></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(1.902)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h</td><td></td><td></td><td></td><td></td><td></td><td>-2.881<sup>***</sup></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(1.030)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-12.736<sup>**</sup></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(5.002)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-4.363<sup>*</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.473)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-2.656<sup>*</sup></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.424)</td></tr>
<tr><td style="text-align:left">Publica</td><td>-16.956<sup>***</sup></td><td>-16.982<sup>***</sup></td><td>-16.923<sup>***</sup></td><td>-16.891<sup>***</sup></td><td>-16.927<sup>***</sup></td><td>-16.980<sup>***</sup></td><td>-16.920<sup>***</sup></td><td>-16.896<sup>***</sup></td><td>-16.873<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.488)</td><td>(0.498)</td><td>(0.524)</td><td>(0.485)</td><td>(0.488)</td><td>(0.497)</td><td>(0.484)</td><td>(0.487)</td><td>(0.491)</td></tr>
<tr><td style="text-align:left">Vespertina</td><td>-1.142</td><td>-0.766</td><td>-1.096</td><td>-1.057</td><td>-1.118</td><td>-2.044</td><td>-1.077</td><td>-1.090</td><td>-1.117</td></tr>
<tr><td style="text-align:left"></td><td>(3.783)</td><td>(4.141)</td><td>(4.154)</td><td>(3.782)</td><td>(3.783)</td><td>(3.804)</td><td>(3.782)</td><td>(3.783)</td><td>(3.783)</td></tr>
<tr><td style="text-align:left">Carencias Educativas y de Ingreso</td><td>0.653<sup>***</sup></td><td>0.651<sup>***</sup></td><td>0.671<sup>***</sup></td><td>0.661<sup>***</sup></td><td>0.651<sup>***</sup></td><td>0.682<sup>***</sup></td><td>0.664<sup>***</sup></td><td>0.655<sup>***</sup></td><td>0.649<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.124)</td><td>(0.126)</td><td>(0.131)</td><td>(0.124)</td><td>(0.124)</td><td>(0.127)</td><td>(0.124)</td><td>(0.125)</td><td>(0.125)</td></tr>
<tr><td style="text-align:left">Carencias de servicios en vivienda</td><td>-0.854<sup>***</sup></td><td>-0.805<sup>**</sup></td><td>-0.812<sup>**</sup></td><td>-0.873<sup>***</sup></td><td>-0.833<sup>***</sup></td><td>-0.815<sup>**</sup></td><td>-0.883<sup>***</sup></td><td>-0.883<sup>***</sup></td><td>-0.895<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.309)</td><td>(0.314)</td><td>(0.333)</td><td>(0.308)</td><td>(0.309)</td><td>(0.319)</td><td>(0.308)</td><td>(0.309)</td><td>(0.312)</td></tr>
<tr><td style="text-align:left">Publica X Vespertina</td><td>-7.489<sup>**</sup></td><td>-7.926<sup>*</sup></td><td>-7.424<sup>*</sup></td><td>-7.577<sup>**</sup></td><td>-7.603<sup>**</sup></td><td>-6.640<sup>*</sup></td><td>-7.550<sup>**</sup></td><td>-7.587<sup>**</sup></td><td>-7.558<sup>**</sup></td></tr>
<tr><td style="text-align:left"></td><td>(3.809)</td><td>(4.166)</td><td>(4.180)</td><td>(3.808)</td><td>(3.809)</td><td>(3.832)</td><td>(3.807)</td><td>(3.808)</td><td>(3.810)</td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Publica</td><td>1.752</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(2.296)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Carencias Educativas y de Ingreso</td><td>1.079</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.936)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Carencias de servicios en vivienda</td><td>2.006</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(2.509)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Vespertina</td><td>11.653<sup>***</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(4.310)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t90h X Publica X Vespertina</td><td>-11.969<sup>**</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(4.679)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Publica</td><td></td><td>1.263</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(1.208)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Carencias Educativas y de Ingreso</td><td></td><td>0.190</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.386)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Carencias de servicios en vivienda</td><td></td><td>0.129</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.967)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Vespertina</td><td></td><td>1.653</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(6.521)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t90h X Publica X Vespertina</td><td></td><td>-1.203</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(6.586)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Publica</td><td></td><td></td><td>0.326</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.638)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Carencias Educativas y de Ingreso</td><td></td><td></td><td>0.023</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.195)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Carencias de servicios en vivienda</td><td></td><td></td><td>0.311</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.461)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Vespertina</td><td></td><td></td><td>1.254</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(4.668)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t90h X Publica X Vespertina</td><td></td><td></td><td>-1.515</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(4.690)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Publica</td><td></td><td></td><td></td><td>-0.824</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(5.177)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td>1.411</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(1.488)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td>1.017</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(3.827)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Vespertina</td><td></td><td></td><td></td><td>9.388</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(5.982)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td>-7.701</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(6.530)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Publica</td><td></td><td></td><td></td><td></td><td>1.589</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(2.211)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td>0.427</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.601)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td>-1.186</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(1.489)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Vespertina</td><td></td><td></td><td></td><td></td><td>11.573<sup>***</sup></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(4.231)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td>-9.055<sup>**</sup></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(4.563)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Publica</td><td></td><td></td><td></td><td></td><td></td><td>1.352</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(1.181)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td>-0.276</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.352)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td>-0.238</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.811)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td>17.197<sup>***</sup></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(3.925)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td>-16.600<sup>***</sup></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(4.035)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td>7.071</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(9.286)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td>1.058</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.882)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td>8.871</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(8.458)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td>16.736<sup>**</sup></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(7.384)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d250_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-26.864<sup>***</sup></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(8.580)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.569</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.746)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.942</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.864)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>2.212</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.652)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>10.719<sup>**</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(4.486)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d500_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-9.122<sup>*</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(5.511)</td><td></td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.408</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.650)</td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.440</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.565)</td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>1.874</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.425)</td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>9.481<sup>**</sup></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(4.042)</td></tr>
<tr><td style="text-align:left">Homicidios_d1000_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-8.997<sup>**</sup></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(4.330)</td></tr>
<tr><td style="text-align:left">Constant</td><td>58.539<sup>***</sup></td><td>58.682<sup>***</sup></td><td>58.798<sup>***</sup></td><td>58.432<sup>***</sup></td><td>58.527<sup>***</sup></td><td>58.658<sup>***</sup></td><td>58.443<sup>***</sup></td><td>58.470<sup>***</sup></td><td>58.501<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.397)</td><td>(0.405)</td><td>(0.428)</td><td>(0.394)</td><td>(0.396)</td><td>(0.404)</td><td>(0.394)</td><td>(0.396)</td><td>(0.400)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.336</td><td>0.337</td><td>0.337</td><td>0.336</td><td>0.336</td><td>0.337</td><td>0.336</td><td>0.336</td><td>0.336</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.336</td><td>0.336</td><td>0.336</td><td>0.335</td><td>0.336</td><td>0.336</td><td>0.335</td><td>0.335</td><td>0.335</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr></table>

<h2> Efecto de la violencia familiar (delitos tipo 2) alrededor de la escuela sobre la prueba MAT </h2>
<h3> Modelo con Efectos Fijos por escuela y año con errores agrupados por escuela </h3>

<table style="text-align:center"><tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="9"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="9" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td colspan="9">mat</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td><td>(6)</td><td>(7)</td><td>(8)</td><td>(9)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Violencia Familiar_d250_t90h</td><td>-0.062</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.140)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h</td><td></td><td>0.030</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.070)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h</td><td></td><td></td><td>-0.057</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.036)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h</td><td></td><td></td><td></td><td>-0.069</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.258)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h</td><td></td><td></td><td></td><td></td><td>0.064</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.127)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h</td><td></td><td></td><td></td><td></td><td></td><td>-0.061</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.069)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.409</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.431)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.010</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.219)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.022</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.119)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td><td>9,763</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td><td>0.799</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.642</td><td>0.642</td><td>0.643</td><td>0.642</td><td>0.642</td><td>0.643</td><td>0.643</td><td>0.642</td><td>0.642</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr></table>

<h3> Modelo MCO-OLS con errores agrupados por escuela </h3>

<table style="text-align:center"><tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="9"><em>Dependent variable:</em></td></tr>
<tr><td></td><td colspan="9" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left"></td><td colspan="9">mat</td></tr>
<tr><td style="text-align:left"></td><td>(1)</td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td><td>(6)</td><td>(7)</td><td>(8)</td><td>(9)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Violencia Familiar_d250_t90h</td><td>0.066</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.307)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h</td><td></td><td>0.001</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.143)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h</td><td></td><td></td><td>-0.098<sup>*</sup></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.055)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h</td><td></td><td></td><td></td><td>0.262</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.574)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h</td><td></td><td></td><td></td><td></td><td>0.219</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.284)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h</td><td></td><td></td><td></td><td></td><td></td><td>-0.145</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.118)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td>1.099</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.930)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.024</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.470)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.038</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.217)</td></tr>
<tr><td style="text-align:left">Publica</td><td>-16.458<sup>***</sup></td><td>-15.839<sup>***</sup></td><td>-16.591<sup>***</sup></td><td>-16.666<sup>***</sup></td><td>-16.001<sup>***</sup></td><td>-16.566<sup>***</sup></td><td>-16.770<sup>***</sup></td><td>-16.575<sup>***</sup></td><td>-16.668<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.574)</td><td>(0.717)</td><td>(0.905)</td><td>(0.520)</td><td>(0.596)</td><td>(0.753)</td><td>(0.494)</td><td>(0.528)</td><td>(0.624)</td></tr>
<tr><td style="text-align:left">Vespertina</td><td>-1.279</td><td>0.329</td><td>2.884</td><td>-1.677</td><td>-2.838</td><td>-3.349</td><td>-2.256</td><td>-3.473</td><td>0.596</td></tr>
<tr><td style="text-align:left"></td><td>(4.251)</td><td>(4.892)</td><td>(4.658)</td><td>(3.963)</td><td>(4.154)</td><td>(5.383)</td><td>(4.016)</td><td>(3.618)</td><td>(4.712)</td></tr>
<tr><td style="text-align:left">Carencias Educativas y de Ingreso</td><td>0.758<sup>***</sup></td><td>0.606<sup>***</sup></td><td>0.678<sup>***</sup></td><td>0.648<sup>***</sup></td><td>0.562<sup>***</sup></td><td>0.566<sup>***</sup></td><td>0.652<sup>***</sup></td><td>0.585<sup>***</sup></td><td>0.572<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.134)</td><td>(0.153)</td><td>(0.166)</td><td>(0.131)</td><td>(0.137)</td><td>(0.154)</td><td>(0.126)</td><td>(0.129)</td><td>(0.139)</td></tr>
<tr><td style="text-align:left">Carencias de servicios en vivienda</td><td>-0.798<sup>**</sup></td><td>-0.596</td><td>-0.320</td><td>-0.951<sup>***</sup></td><td>-0.869<sup>**</sup></td><td>-0.662<sup>*</sup></td><td>-0.887<sup>***</sup></td><td>-0.872<sup>***</sup></td><td>-0.694<sup>**</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.339)</td><td>(0.385)</td><td>(0.425)</td><td>(0.326)</td><td>(0.345)</td><td>(0.395)</td><td>(0.312)</td><td>(0.319)</td><td>(0.350)</td></tr>
<tr><td style="text-align:left">Publica X Vespertina</td><td>-7.349<sup>*</sup></td><td>-8.673<sup>*</sup></td><td>-10.189<sup>**</sup></td><td>-7.053<sup>*</sup></td><td>-5.749</td><td>-4.397</td><td>-6.323</td><td>-5.300</td><td>-8.767<sup>*</sup></td></tr>
<tr><td style="text-align:left"></td><td>(4.286)</td><td>(4.935)</td><td>(4.719)</td><td>(3.992)</td><td>(4.189)</td><td>(5.423)</td><td>(4.042)</td><td>(3.651)</td><td>(4.745)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Publica</td><td>-0.440</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.352)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Carencias Educativas y de Ingreso</td><td>-0.156</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.126)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Carencias de servicios en vivienda</td><td>-0.138</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.309)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Vespertina</td><td>2.080</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(10.100)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t90h X Publica X Vespertina</td><td>-2.279</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(10.106)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Publica</td><td></td><td>-0.296<sup>*</sup></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.163)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Carencias Educativas y de Ingreso</td><td></td><td>0.041</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.052)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Carencias de servicios en vivienda</td><td></td><td>-0.023</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(0.129)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Vespertina</td><td></td><td>-0.941</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(2.640)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t90h X Publica X Vespertina</td><td></td><td>0.677</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td>(2.644)</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Publica</td><td></td><td></td><td>-0.013</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.063)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Carencias Educativas y de Ingreso</td><td></td><td></td><td>0.012</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.019)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Carencias de servicios en vivienda</td><td></td><td></td><td>-0.011</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.045)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Vespertina</td><td></td><td></td><td>-0.774<sup>*</sup></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.453)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t90h X Publica X Vespertina</td><td></td><td></td><td>0.566</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td>(0.457)</td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Publica</td><td></td><td></td><td></td><td>-0.726</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.670)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td>0.125</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.237)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td>0.380</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(0.558)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Vespertina</td><td></td><td></td><td></td><td>13.239</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(21.523)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td>-13.031</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td>(21.533)</td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Publica</td><td></td><td></td><td></td><td></td><td>-0.779<sup>**</sup></td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.326)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td>0.175</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.113)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td>0.161</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(0.278)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Vespertina</td><td></td><td></td><td></td><td></td><td>5.717</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(5.165)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td>-6.029</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td>(5.174)</td><td></td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Publica</td><td></td><td></td><td></td><td></td><td></td><td>-0.067</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.141)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td>0.069</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.045)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td>0.045</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(0.108)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td>1.220</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(1.868)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t29h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td>-1.618</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td>(1.873)</td><td></td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-1.148</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(1.083)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.209</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.364)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.073</td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.886)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td>42.728<sup>***</sup></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(4.102)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d250_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td>-43.591<sup>***</sup></td><td></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(4.215)</td><td></td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.732</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.534)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.333<sup>*</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.192)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.215</td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.472)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>18.853<sup>*</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(10.961)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d500_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-18.864<sup>*</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(10.974)</td><td></td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Publica</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.143</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.258)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Carencias Educativas y de Ingreso</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.125</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.091)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Carencias de servicios en vivienda</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-0.033</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(0.225)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>-1.583</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.357)</td></tr>
<tr><td style="text-align:left">Violencia Familiar_d1000_t10h X Publica X Vespertina</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>0.990</td></tr>
<tr><td style="text-align:left"></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>(2.372)</td></tr>
<tr><td style="text-align:left">Constant</td><td>58.382<sup>***</sup></td><td>58.425<sup>***</sup></td><td>59.502<sup>***</sup></td><td>58.325<sup>***</sup></td><td>58.169<sup>***</sup></td><td>58.904<sup>***</sup></td><td>58.301<sup>***</sup></td><td>58.419<sup>***</sup></td><td>58.443<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.466)</td><td>(0.586)</td><td>(0.745)</td><td>(0.424)</td><td>(0.483)</td><td>(0.615)</td><td>(0.404)</td><td>(0.430)</td><td>(0.514)</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left">Observations</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td><td>9,741</td></tr>
<tr><td style="text-align:left">R<sup>2</sup></td><td>0.336</td><td>0.337</td><td>0.339</td><td>0.336</td><td>0.337</td><td>0.338</td><td>0.336</td><td>0.336</td><td>0.336</td></tr>
<tr><td style="text-align:left">Adjusted R<sup>2</sup></td><td>0.335</td><td>0.337</td><td>0.338</td><td>0.335</td><td>0.336</td><td>0.337</td><td>0.335</td><td>0.336</td><td>0.336</td></tr>
<tr><td colspan="10" style="border-bottom: 1px solid black"></td></tr></table>
