# Aguascalientes: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Aguascalientes, Mexico, which global-law reads at `mexico/aguascalientes/acts/`.

The law of the State of Aguascalientes (Estado Libre y Soberano de Aguascalientes, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-agu/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

164 ordenamientos with 2392 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE AGUASCALIENTES | 204 | as first published, then each reform: 10 September 1917 to 8 September 2026 |
| `codigo-civil/` | CODIGO CIVIL DEL ESTADO DE AGUASCALIENTES | 128 | as first published, then each reform: 6 January 1948 to 19 January 2027 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES DEL ESTADO DE AGUASCALIENTES | 40 | as first published, then each reform: 14 September 1989 to 13 November 2018 |
| `codigo-electoral/` | CODIGO ELECTORAL DEL ESTADO DE AGUASCALIENTES | 18 | as first published, then each reform: 3 March 2015 to 6 July 2026 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE AGUASCALIENTES | 20 | as first published, then each reform: 1 January 1982 to 27 December 2025 |
| `codigo-municipal-de-aguascalientes-aguascalientes/` | CODIGO MUNICIPAL DE AGUASCALIENTES, AGUASCALIENTES | 220 | as first published, then each reform: 13 November 2007 to 1 October 2026 |
| `codigo-municipal-de-calvillo-aguascalientes/` | CODIGO MUNICIPAL DE CALVILLO, AGUASCALIENTES | 32 | as first published, then each reform: 26 November 2013 to 30 April 2026 |
| `codigo-municipal-de-pabellon-de-arteaga-aguascalientes/` | CODIGO MUNICIPAL DE PABELLON DE ARTEAGA, AGUASCALIENTES | 51 | oldest version available, then each reform: 19 April 2005 to 16 June 2026 |
| `codigo-municipal-de-san-francisco-de-los-romo-aguascalientes/` | CODIGO MUNICIPAL DE SAN FRANCISCO DE LOS ROMO, AGUASCALIENTES | 39 | as first published, then each reform: 13 February 2007 to 28 October 2025 |
| `codigo-municipal-de-san-jose-de-gracia-aguascalientes/` | CODIGO MUNICIPAL DE SAN JOSE DE GRACIA, AGUASCALIENTES | 21 | as first published, then each reform: 15 December 2009 to 24 September 2024 |
| `codigo-municipal-de-tepezala-aguascalientes/` | CODIGO MUNICIPAL DE TEPEZALA, AGUASCALIENTES | 7 | as first published, then each reform: 23 March 2010 to 16 July 2024 |
| `codigo-municipal-del-municipio-de-el-llano/` | CODIGO MUNICIPAL DEL MUNICIPIO DE EL LLANO DEL ESTADO DE AGUASCALIENTES | 20 | as first published, then each reform: 18 January 2011 to 9 October 2025 |
| `codigo-municipal-para-el-h-ayuntamiento-de-asientos-aguascal/` | CODIGO MUNICIPAL PARA EL H. AYUNTAMIENTO DE ASIENTOS, AGUASCALIENTES | 15 | as first published, then each reform: 15 October 2019 to 13 January 2026 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE AGUASCALIENTES | 135 | as first published, then each reform: 19 July 2013 to 13 October 2026 |
| `codigo-urbano/` | CODIGO URBANO PARA EL ESTADO DE AGUASCALIENTES | 24 | as first published, then each reform: 21 December 2022 to 30 June 2026 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE AGUASCALIENTES | 56 | as first published, then each reform: 27 November 2007 to 22 September 2026 |
| `ley-de-adquisiciones-arrendamientos-y-servicios/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y SERVICIOS DEL ESTADO DE AGUASCALIENTES Y SUS MUNICIPIOS | 11 | as first published, then each reform: 24 March 2015 to 13 August 2024 |
| `ley-de-agua/` | LEY DE AGUA PARA EL ESTADO DE AGUASCALIENTES | 31 | as first published, then each reform: 25 July 2000 to 28 April 2026 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 28 August 2021 to 23 January 2024 |
| `ley-de-asociaciones-publico-privadas-y-proyectos-de-prestaci/` | LEY DE ASOCIACIONES PUBLICO - PRIVADAS Y PROYECTOS DE PRESTACION DE SERVICIOS DEL ESTADO Y MUNICIPIOS DE -- ANTES LEY DE PROYECTOS DE PRESTACION DE SERVICIOS DEL ESTADO DE -- AGUASCALIENTES | 8 | as first published, then each reform: 12 November 2013 to 14 August 2024 |
| `ley-de-bibliotecas-publicas-y-de-fomento-a-la-lectura/` | LEY DE BIBLIOTECAS PUBLICAS Y DE FOMENTO A LA LECTURA DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 13 August 2024 |
| `ley-de-bienes/` | LEY DE BIENES PARA EL ESTADO DE AGUASCALIENTES | 7 | as first published, then each reform: 28 December 2023 to 26 March 2026 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO PARA EL ESTADO DE AGUASCALIENTES | 11 | as first published, then each reform: 7 April 2015 to 21 April 2026 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE AGUASCALIENTES | 4 | as first published, then each reform: 24 September 2013 to 1 January 2023 |
| `ley-de-ciencia-tecnologia-innovacion-y-emprendimiento-para-e/` | LEY DE CIENCIA, TECNOLOGIA, INNOVACION Y EMPRENDIMIENTO PARA EL DESARROLLO DE LA SOCIEDAD DEL CONOCIMIENTO DEL ESTADO DE AGUASCALIENTES | 12 | as first published, then each reform: 1 October 2022 to 23 December 2025 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE AGUASCALIENTES | 10 | as first published, then each reform: 4 November 1996 to 22 December 2020 |
| `ley-de-creacion-de-la-universidad-tecnologica-metropolitana/` | LEY DE CREACION DE LA UNIVERSIDAD TECNOLOGICA METROPOLITANA DE AGUASCALIENTES | 5 | as first published, then each reform: 4 September 2018 to 8 May 2025 |
| `ley-de-cultura/` | LEY DE CULTURA DEL ESTADO DE AGUASCALIENTES | 7 | as first published, then each reform: 26 October 2010 to 11 June 2024 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE AGUASCALIENTES | 35 | as first published, then each reform: 23 January 2007 to 9 June 2026 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO DE AGUASCALIENTES | 27 | as first published, then each reform: 1 January 2009 to 9 June 2026 |
| `ley-de-deuda-publica-y-disciplina-financiera/` | LEY DE DEUDA PUBLICA Y DISCIPLINA FINANCIERA DEL ESTADO DE AGUASCALIENTES Y SUS MUNICIPIOS | 1 | as first published: 9 May 2017 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE AGUASCALIENTES | 32 | as first published, then each reform: 26 May 2020 to 14 July 2026 |
| `ley-de-ejecucion-de-sanciones-penales/` | LEY DE EJECUCION DE SANCIONES PENALES DEL ESTADO DE AGUASCALIENTES | 4 | as first published, then each reform: 18 June 2011 to 3 February 2015 |
| `ley-de-estacionamientos-de-vehiculos-para-los-municipios/` | LEY DE ESTACIONAMIENTOS DE VEHICULOS PARA LOS MUNICIPIOS DEL ESTADO DE AGUASCALIENTES | 4 | as first published, then each reform: 10 April 1989 to 6 October 2020 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION PARA EL ESTADO DE AGUASCALIENTES | 6 | as first published, then each reform: 17 April 2007 to 24 June 2026 |
| `ley-de-fiscalizacion-superior/` | LEY DE FISCALIZACION SUPERIOR DEL ESTADO DE AGUASCALIENTES | 13 | as first published, then each reform: 22 November 2011 to 7 July 2026 |
| `ley-de-fomento-a-la-produccion-cinematografica-y-audiovisual/` | LEY DE FOMENTO A LA PRODUCCION CINEMATOGRAFICA Y AUDIOVISUAL DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 4 June 2024 |
| `ley-de-fomento-a-las-organizaciones-de-la-sociedad-civil/` | LEY DE FOMENTO A LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL DEL ESTADO DE AGUASCALIENTES -ANTES LEY QUE REGULA LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL DEL ESTADO DE AGUASCALIENTES- | 11 | as first published, then each reform: 1 December 2010 to 26 November 2024 |
| `ley-de-fomento-para-el-desarrollo-de-los-jovenes-emprendedor/` | LEY DE FOMENTO PARA EL DESARROLLO DE LOS JOVENES EMPRENDEDORES DEL ESTADO DE AGUASCALIENTES | 5 | as first published, then each reform: 17 October 2017 to 25 November 2025 |
| `ley-de-fomento-para-el-desarrollo-forestal-sustentable/` | LEY DE FOMENTO PARA EL DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE AGUASCALIENTES | 4 | as first published, then each reform: 12 September 2006 to 7 May 2019 |
| `ley-de-fomento-para-el-uso-de-la-bicicleta-en-el-estado-de-a/` | LEY DE FOMENTO PARA EL USO DE LA BICICLETA EN EL ESTADO DE AGUASCALIENTES | 1 | as first published: 11 September 2018 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE AGUASCALIENTES | 38 | as first published, then each reform: 4 January 1984 to 27 May 2025 |
| `ley-de-hacienda-del-municipio-de-aguascalientes-aguascalient/` | LEY DE HACIENDA DEL MUNICIPIO DE AGUASCALIENTES, AGUASCALIENTES -- ANTES LEY DE HACIENDA DEL MUNICIPIO DE AGUASCALIENTES, AGUASCALIENTES, PARA EL EJERCICIO FISCAL DE 1986 -- | 26 | as first published, then each reform: 1 January 1986 to 28 November 2023 |
| `ley-de-hacienda-del-municipio-de-asientos-aguascalientes/` | LEY DE HACIENDA DEL MUNICIPIO DE ASIENTOS, AGUASCALIENTES | 4 | as first published, then each reform: 1 January 2013 to 17 April 2023 |
| `ley-de-hacienda-del-municipio-de-calvillo-aguascalientes/` | LEY DE HACIENDA DEL MUNICIPIO DE CALVILLO, AGUASCALIENTES | 9 | as first published, then each reform: 3 January 1986 to 25 December 2018 |
| `ley-de-hacienda-del-municipio-de-cosio-aguascalientes/` | LEY DE HACIENDA DEL MUNICIPIO DE COSIO, AGUASCALIENTES | 1 | as first published: 27 December 2025 |
| `ley-de-hacienda-del-municipio-de-el-llano-aguascalientes/` | LEY DE HACIENDA DEL MUNICIPIO DE EL LLANO, AGUASCALIENTES | 4 | as first published, then each reform: 4 July 1994 to 24 August 2010 |
| `ley-de-hacienda-del-municipio-de-jesus-maria-aguascalientes/` | LEY DE HACIENDA DEL MUNICIPIO DE JESUS MARIA, AGUASCALIENTES | 11 | as first published, then each reform: 26 January 2010 to 27 December 2025 |
| `ley-de-hacienda-del-municipio-de-pabellon-de-arteaga-aguasca/` | LEY DE HACIENDA DEL MUNICIPIO DE PABELLON DE ARTEAGA, AGUASCALIENTES | 9 | as first published, then each reform: 3 January 1986 to 18 May 2017 |
| `ley-de-hacienda-del-municipio-de-rincon-de-romos-aguascalien/` | LEY DE HACIENDA DEL MUNICIPIO DE RINCON DE ROMOS, AGUASCALIENTES | 9 | as first published, then each reform: 3 January 1986 to 1 January 2020 |
| `ley-de-hacienda-del-municipio-de-san-francisco-de-los-romo-a/` | LEY DE HACIENDA DEL MUNICIPIO DE SAN FRANCISCO DE LOS ROMO, AGUASCALIENTES | 12 | as first published, then each reform: 19 July 1995 to 27 December 2025 |
| `ley-de-hacienda-del-municipio-de-san-jose-de-gracia-aguascal/` | LEY DE HACIENDA DEL MUNICIPIO DE SAN JOSE DE GRACIA, AGUASCALIENTES | 8 | as first published, then each reform: 3 January 1986 to 18 May 2017 |
| `ley-de-hacienda-del-municipio-de-tepezala-aguascalientes/` | LEY DE HACIENDA DEL MUNICIPIO DE TEPEZALA, AGUASCALIENTES | 7 | as first published, then each reform: 3 January 1986 to 18 May 2017 |
| `ley-de-imagen-institucional/` | LEY DE IMAGEN INSTITUCIONAL PARA EL ESTADO DE AGUASCALIENTES Y SUS MUNICIPIOS | 1 | as first published: 15 October 2019 |
| `ley-de-informacion-estadistica-y-geografica/` | LEY DE INFORMACION ESTADISTICA Y GEOGRAFICA DEL ESTADO DE AGUASCALIENTES | 4 | as first published, then each reform: 27 February 2001 to 4 July 2017 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE AGUASCALIENTES PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 4 | as first published, then each reform: 1 January 2026 to 29 August 2026 |
| `ley-de-ingresos-del-municipio-de-aguascalientes-aguascalient/` | LEY DE INGRESOS DEL MUNICIPIO DE AGUASCALIENTES, AGUASCALIENTES PARA EL EJERCICIO FISCAL 2026 | 2 | as first published, then each reform: 1 January 2026 to 24 March 2026 |
| `ley-de-ingresos-del-municipio-de-asientos-aguascalientes-par/` | LEY DE INGRESOS DEL MUNICIPIO DE ASIENTOS, AGUASCALIENTES, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-calvillo-aguascalientes-par/` | LEY DE INGRESOS DEL MUNICIPIO DE CALVILLO, AGUASCALIENTES, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-cosio-aguascalientes-para-e/` | LEY DE INGRESOS DEL MUNICIPIO DE COSIO, AGUASCALIENTES, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-jesus-maria-aguascalientes/` | LEY DE INGRESOS DEL MUNICIPIO DE JESUS MARIA, AGUASCALIENTES PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 24 February 2026 |
| `ley-de-ingresos-del-municipio-de-pabellon-de-arteaga-aguasca/` | LEY DE INGRESOS DEL MUNICIPIO DE PABELLON DE ARTEAGA, AGUASCALIENTES PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-rincon-de-romos-aguascalien/` | LEY DE INGRESOS DEL MUNICIPIO DE RINCON DE ROMOS, AGUASCALIENTES, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-san-francisco-de-los-romo-a/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN FRANCISCO DE LOS ROMO, AGUASCALIENTES, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-san-josre-de-gracia-aguasca/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN JOSRE DE GRACIA, AGUASCALIENTES, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-tepezala-aguascalientes-par/` | LEY DE INGRESOS DEL MUNICIPIO DE TEPEZALA, AGUASCALIENTES, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-instituciones-asistenciales-para-ninas-ninos-y-adoles/` | LEY DE INSTITUCIONES ASISTENCIALES PARA NIÑAS, NIÑOS Y ADOLESCENTES EN EL ESTADO DE AGUASCALIENTES | 6 | as first published, then each reform: 8 November 2016 to 26 November 2024 |
| `ley-de-integracion-social-y-productiva-de-personas-con-disca/` | LEY DE INTEGRACION SOCIAL Y PRODUCTIVA DE PERSONAS CON DISCAPACIDAD PARA EL ESTADO DE AGUASCALIENTES -- ANTES LEY DE INTEGRACION SOCIAL Y PRODUCTIVA DE PERSONAS CON DISCAPACIDAD -- | 14 | as first published, then each reform: 14 May 2000 to 11 June 2024 |
| `ley-de-justicia-constitucional/` | LEY DE JUSTICIA CONSTITUCIONAL DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 28 December 2023 |
| `ley-de-justicia-indigena/` | LEY DE JUSTICIA INDIGENA DEL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 17 March 2015 to 26 June 2018 |
| `ley-de-la-agencia-de-energia/` | LEY DE LA AGENCIA DE ENERGIA DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 3 September 2024 |
| `ley-de-la-comision-de-derechos-humanos/` | LEY DE LA COMISION DE DERECHOS HUMANOS DEL ESTADO DE AGUASCALIENTES | 19 | as first published, then each reform: 11 June 2013 to 24 June 2026 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD DEL ESTADO DE AGUASCALIENTES | 14 | as first published, then each reform: 5 April 2016 to 21 April 2026 |
| `ley-de-la-procuraduria-estatal-de-proteccion-al-ambiente/` | LEY DE LA PROCURADURIA ESTATAL DE PROTECCION AL AMBIENTE, DEL ESTADO DE AGUASCALIENTES | 14 | as first published, then each reform: 1 August 2003 to 23 April 2026 |
| `ley-de-la-universidad-intercultural-para-la-igualdad-de-agua/` | LEY DE LA UNIVERSIDAD INTERCULTURAL PARA LA IGUALDAD DE AGUASCALIENTES -- ANTES LEY DE LA UNIVERSIDAD INTERCULTURAL PARA LA IGUALDAD DEL ESTADO DE AGUASCALIENTES -- | 4 | as first published, then each reform: 3 May 2025 to 21 April 2026 |
| – | – | 3 | as first published, then each reform: 12 April 2022 to 9 November 2024 |
| `ley-de-la-universidad-tecnologica-del-norte-de-aguascaliente/` | LEY DE LA UNIVERSIDAD TECNOLOGICA DEL NORTE DE AGUASCALIENTES | 7 | as first published, then each reform: 27 June 2000 to 30 June 2026 |
| `ley-de-la-universidad-tecnologica-el-retono-aguascalientes/` | LEY DE LA UNIVERSIDAD TECNOLOGICA EL RETOÑO, AGUASCALIENTES | 2 | as first published, then each reform: 8 August 2023 to 9 November 2024 |
| `ley-de-los-derechos-de-las-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE LAS NIÑAS, NIÑOS Y ADOLESCENTES PARA EL ESTADO DE AGUASCALIENTES | 74 | as first published, then each reform: 4 June 2015 to 7 July 2026 |
| `ley-de-mediacion-y-conciliacion/` | LEY DE MEDIACION Y CONCILIACION DEL ESTADO DE AGUASCALIENTES | 5 | as first published, then each reform: 28 December 2004 to 11 May 2021 |
| `ley-de-mejora-regulatoria-y-gestion-empresarial/` | LEY DE MEJORA REGULATORIA Y GESTION EMPRESARIAL PARA EL ESTADO DE AGUASCALIENTES | 5 | as first published, then each reform: 29 November 2019 to 16 January 2024 |
| `ley-de-movilidad-y-seguridad-vial/` | LEY DE MOVILIDAD Y SEGURIDAD VIAL DEL ESTADO DE AGUASCALIENTES | 4 | as first published, then each reform: 16 December 2025 to 23 May 2026 |
| `ley-de-obras-publicas-y-servicios-relacionados/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS PARA EL ESTADO DE AGUASCALIENTES Y SUS MUNICIPIOS | 6 | as first published, then each reform: 11 July 2019 to 24 June 2026 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE AGUASCALIENTES | 5 | as first published, then each reform: 27 February 2018 to 8 August 2024 |
| `ley-de-planeacion-para-el-desarrollo/` | LEY DE PLANEACION PARA EL DESARROLLO DEL ESTADO DE AGUASCALIENTES | 5 | as first published, then each reform: 1 July 2021 to 28 May 2024 |
| `ley-de-premios-que-otorga-el-congreso/` | LEY DE PREMIOS QUE OTORGA EL CONGRESO DEL ESTADO DE AGUASCALIENTES | 13 | as first published, then each reform: 27 November 2007 to 25 February 2026 |
| `ley-de-prestacion-de-servicios-para-la-atencion-cuidado-y-de/` | LEY DE PRESTACION DE SERVICIOS PARA LA ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL PARA EL ESTADO DE AGUASCALIENTES | 3 | as first published, then each reform: 5 April 2016 to 28 May 2024 |
| `ley-de-presupuesto-gasto-publico-y-responsabilidad-hacendari/` | LEY DE PRESUPUESTO, GASTO PUBLICO Y RESPONSABILIDAD HACENDARIA DEL ESTADO DE AGUASCALIENTES Y SUS MUNICIPIOS | 21 | as first published, then each reform: 1 January 2015 to 27 December 2025 |
| `ley-de-prevencion-social-de-la-violencia-y-la-delincuencia-c/` | LEY DE PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA CON PARTICIPACION CIUDADANA DEL ESTADO DE AGUASCALIENTES | 7 | as first published, then each reform: 31 January 2015 to 30 April 2025 |
| `ley-de-proteccion-a-los-animales/` | LEY DE PROTECCION A LOS ANIMALES PARA EL ESTADO DE AGUASCALIENTES | 20 | as first published, then each reform: 6 November 2001 to 21 October 2025 |
| `ley-de-proteccion-ambiental/` | LEY DE PROTECCION AMBIENTAL PARA EL ESTADO DE AGUASCALIENTES | 37 | as first published, then each reform: 15 February 2000 to 5 May 2026 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE AGUASCALIENTES | 12 | as first published, then each reform: 9 July 2013 to 19 May 2026 |
| `ley-de-proteccion-contra-la-exposicion-al-humo-de-tabaco/` | LEY DE PROTECCION CONTRA LA EXPOSICION AL HUMO DE TABACO DEL ESTADO DE AGUASCALIENTES | 4 | as first published, then each reform: 29 November 2019 to 2 July 2024 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-los-suj/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE LOS SUJETOS OBLIGADOS DEL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 17 June 2025 to 13 January 2026 |
| `ley-de-proteccion-y-fomento-del-patrimonio-cultural/` | LEY DE PROTECCION Y FOMENTO DEL PATRIMONIO CULTURAL DEL ESTADO DE AGUASCALIENTES | 7 | as first published, then each reform: 30 September 2001 to 24 January 2023 |
| `ley-de-remuneraciones-de-los-servidores-publicos/` | LEY DE REMUNERACIONES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE AGUASCALIENTES Y SUS MUNICIPIOS | 1 | as first published: 9 July 2019 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE AGUASCALIENTES | 10 | as first published, then each reform: 1 January 2011 to 14 May 2024 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE AGUASCALIENTES | 14 | as first published, then each reform: 2 August 2017 to 14 July 2026 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE AGUASCALIENTES | 87 | as first published, then each reform: 7 June 1999 to 13 October 2026 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE AGUASCALIENTES | 3 | as first published, then each reform: 29 August 2024 to 17 June 2025 |
| `ley-de-seguridad-privada/` | LEY DE SEGURIDAD PRIVADA DEL ESTADO DE AGUASCALIENTES | 11 | as first published, then each reform: 25 June 2003 to 11 June 2024 |
| `ley-de-seguridad-y-servicios-sociales-para-los-servidores-pu/` | LEY DE SEGURIDAD Y SERVICIOS SOCIALES PARA LOS SERVIDORES PUBLICOS DEL ESTADO DE AGUASCALIENTES | 11 | as first published, then each reform: 27 May 2018 to 6 October 2026 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 17 June 2025 to 13 January 2026 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE AGUASCALIENTES | 11 | as first published, then each reform: 17 April 2007 to 9 June 2026 |
| `ley-de-victimas/` | LEY DE VICTIMAS DEL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 1 January 2022 to 4 July 2023 |
| `ley-de-video-vigilancia/` | LEY DE VIDEO VIGILANCIA DEL ESTADO DE AGUASCALIENTES | 8 | as first published, then each reform: 23 June 2009 to 31 May 2023 |
| `ley-de-voluntad-anticipada/` | LEY DE VOLUNTAD ANTICIPADA PARA EL ESTADO DE AGUASCALIENTES | 1 | as first published: 7 April 2009 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE AGUASCALIENTES | 5 | as first published, then each reform: 20 April 2021 to 13 January 2026 |
| `ley-del-colegio-de-estudios-cientificos-y-tecnologicos/` | LEY DEL COLEGIO DE ESTUDIOS CIENTIFICOS Y TECNOLOGICOS DEL ESTADO DE AGUASCALIENTES | 3 | as first published, then each reform: 4 July 1994 to 24 January 2023 |
| `ley-del-instituto-aguascalentense-de-la-juventud-aguascalien/` | LEY DEL INSTITUTO AGUASCALENTENSE DE LA JUVENTUD, AGUASCALIENTES | 4 | as first published, then each reform: 3 January 2018 to 9 May 2023 |
| `ley-del-instituto-aguascalentense-de-las-personas-adultas-ma/` | LEY DEL INSTITUTO AGUASCALENTENSE DE LAS PERSONAS ADULTAS MAYORES, AGUASCALIENTES | 2 | as first published, then each reform: 1 October 2022 to 2 April 2024 |
| `ley-del-instituto-de-asesoria-y-defensoria-publica/` | LEY DEL INSTITUTO DE ASESORIA Y DEFENSORIA PUBLICA DEL ESTADO DE AGUASCALIENTES | 10 | as first published, then each reform: 18 March 2003 to 23 December 2025 |
| `ley-del-instituto-de-atencion-integral-de-enfermedades-renal/` | LEY DEL INSTITUTO DE ATENCION INTEGRAL DE ENFERMEDADES RENALES DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 28 October 2023 |
| `ley-del-instituto-de-capacitacion-para-el-trabajo/` | LEY DEL INSTITUTO DE CAPACITACION PARA EL TRABAJO DEL ESTADO DE AGUASCALIENTES | 3 | as first published, then each reform: 31 October 1994 to 14 May 2024 |
| `ley-del-instituto-de-educacion-de-aguascalientes/` | LEY DEL INSTITUTO DE EDUCACION DE AGUASCALIENTES | 4 | as first published, then each reform: 26 May 2020 to 27 May 2026 |
| `ley-del-instituto-de-servicios-de-salud/` | LEY DEL INSTITUTO DE SERVICIOS DE SALUD DEL ESTADO DE AGUASCALIENTES | 6 | as first published, then each reform: 14 June 2011 to 6 June 2023 |
| `ley-del-instituto-de-vivienda-social-y-ordenamiento-de-la-pr/` | LEY DEL INSTITUTO DE VIVIENDA SOCIAL Y ORDENAMIENTO DE LA PROPIEDAD DEL ESTADO DE AGUASCALIENTES | 6 | as first published, then each reform: 1 March 2011 to 24 December 2024 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE AGUASCALIENTES | 14 | as first published, then each reform: 2 June 1980 to 2 July 2024 |
| `ley-del-patronato-de-la-feria-nacional-de-san-marcos-aguasca/` | LEY DEL PATRONATO DE LA FERIA NACIONAL DE SAN MARCOS, AGUASCALIENTES | 5 | as first published, then each reform: 9 January 1991 to 28 October 2023 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 30 August 2005 |
| `ley-del-procedimiento-administrativo/` | LEY DEL PROCEDIMIENTO ADMINISTRATIVO DEL ESTADO DE AGUASCALIENTES | 8 | as first published, then each reform: 15 February 1999 to 31 December 2019 |
| `ley-del-procedimiento-contencioso-administrativo/` | LEY DEL PROCEDIMIENTO CONTENCIOSO ADMINISTRATIVO PARA EL ESTADO DE AGUASCALIENTES | 18 | as first published, then each reform: 24 September 1999 to 14 July 2026 |
| `ley-del-servicio-civil-de-carrera/` | LEY DEL SERVICIO CIVIL DE CARRERA PARA EL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 11 January 2002 to 9 August 2005 |
| `ley-del-servicio-profesional-de-carrera-judicial-del-poder-j/` | LEY DEL SERVICIO PROFESIONAL DE CARRERA JUDICIAL DEL PODER JUDICIAL DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 28 December 2023 |
| `ley-del-sistema-estatal-anticorrupcion-de-aguascalientes/` | LEY DEL SISTEMA ESTATAL ANTICORRUPCION DE AGUASCALIENTES | 8 | as first published, then each reform: 9 May 2017 to 13 January 2026 |
| `ley-del-sistema-estatal-de-asistencia-social-y-de-integracio/` | LEY DEL SISTEMA ESTATAL DE ASISTENCIA SOCIAL Y DE INTEGRACION FAMILIAR, DEL ESTADO DE AGUASCALIENTES | 22 | as first published, then each reform: 11 April 2000 to 24 June 2026 |
| `ley-del-sistema-estatal-de-seguridad-publica-de-aguascalient/` | LEY DEL SISTEMA ESTATAL DE SEGURIDAD PUBLICA DE AGUASCALIENTES | 35 | as first published, then each reform: 29 January 2011 to 22 September 2026 |
| `ley-municipal/` | LEY MUNICIPAL PARA EL ESTADO DE AGUASCALIENTES | 53 | as first published, then each reform: 7 October 2003 to 6 July 2026 |
| `ley-organica-de-la-administracion-publica-estatal-de-aguasca/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA ESTATAL DE AGUASCALIENTES | 16 | as first published, then each reform: 1 October 2022 to 26 March 2026 |
| `ley-organica-de-la-escuela-normal-de-aguascalientes/` | LEY ORGANICA DE LA ESCUELA NORMAL DE AGUASCALIENTES | 1 | as first published: 19 July 2022 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE AGUASCALIENTES | 11 | as first published, then each reform: 21 January 2020 to 13 October 2026 |
| `ley-organica-de-la-universidad-autonoma-de-aguascalientes/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DE AGUASCALIENTES | 8 | as first published, then each reform: 24 February 1974 to 9 November 2024 |
| `ley-organica-de-la-universidad-tecnologica-de-aguascalientes/` | LEY ORGANICA DE LA UNIVERSIDAD TECNOLOGICA DE AGUASCALIENTES | 1 | as first published: 21 May 2024 |
| `ley-organica-de-la-universidad-tecnologica-de-calvillo/` | LEY ORGANICA DE LA UNIVERSIDAD TECNOLOGICA DE CALVILLO DEL ESTADO DE AGUASCALIENTES -- ANTES LEY DE CREACION DE LA UNIVERSIDAD TECNOLOGICA DE CALVILLO, AGUASCALIENTES -- | 4 | as first published, then each reform: 9 July 2013 to 27 May 2026 |
| `ley-organica-del-instituto-aguascalentense-de-las-personas-m/` | LEY ORGANICA DEL INSTITUTO AGUASCALENTENSE DE LAS PERSONAS MIGRANTES | 4 | as first published, then each reform: 4 February 2023 to 28 April 2026 |
| `ley-organica-del-instituto-estatal-de-seguridad-publica/` | LEY ORGANICA DEL INSTITUTO ESTATAL DE SEGURIDAD PUBLICA | 5 | as first published, then each reform: 7 March 2000 to 28 July 2015 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE AGUASCALIENTES | 4 | as first published, then each reform: 28 December 2023 to 24 March 2026 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE AGUASCALIENTES | 30 | as first published, then each reform: 14 September 2018 to 13 October 2026 |
| `ley-organica-del-tribunal-de-justicia-administrativa/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 2 December 2023 |
| `ley-para-el-control-de-las-entidades-paraestatales/` | LEY PARA EL CONTROL DE LAS ENTIDADES PARAESTATALES DEL ESTADO DE AGUASCALIENTES | 18 | as first published, then each reform: 21 March 1988 to 24 June 2026 |
| `ley-para-el-desarrollo-agricola/` | LEY PARA EL DESARROLLO AGRICOLA DEL ESTADO DE AGUASCALIENTES | 12 | as first published, then each reform: 21 June 2018 to 5 May 2026 |
| `ley-para-el-desarrollo-pecuario/` | LEY PARA EL DESARROLLO PECUARIO DEL ESTADO DE AGUASCALIENTES | 7 | as first published, then each reform: 21 June 2018 to 13 January 2026 |
| `ley-para-el-fomento-a-la-economia-la-inversion-y-el-empleo/` | LEY PARA EL FOMENTO A LA ECONOMIA, LA INVERSION Y EL EMPLEO PARA EL ESTADO DE AGUASCALIENTES | 20 | as first published, then each reform: 12 July 1999 to 28 April 2026 |
| `ley-para-evitar-el-desperdicio-de-alimentos-en-el-estado-de/` | LEY PARA EVITAR EL DESPERDICIO DE ALIMENTOS EN EL ESTADO DE AGUASCALIENTES | 3 | as first published, then each reform: 18 July 2017 to 14 May 2024 |
| `ley-para-la-administracion-y-enajenacion-de-bienes-del-secto/` | LEY PARA LA ADMINISTRACION Y ENAJENACION DE BIENES DEL SECTOR PUBLICO PARA EL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 3 January 2016 to 24 January 2023 |
| `ley-para-la-atencion-y-prevencion-de-la-desaparicion-de-pers/` | LEY PARA LA ATENCION Y PREVENCION DE LA DESAPARICION DE PERSONAS EN EL ESTADO DE AGUASCALIENTES | 7 | as first published, then each reform: 27 June 2020 to 2 July 2024 |
| `ley-para-la-atencion-proteccion-e-inclusion-de-personas-con/` | LEY PARA LA ATENCION, PROTECCION E INCLUSION DE PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA EN EL ESTADO DE AGUASCALIENTES Y SUS MUNICIPIOS | 1 | as first published: 14 January 2026 |
| `ley-para-la-igualdad-entre-mujeres-y-hombres/` | LEY PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE AGUASCALIENTES | 15 | as first published, then each reform: 17 March 2020 to 24 June 2026 |
| `ley-para-la-prevencion-atencion-integral-y-control-de-las-ad/` | LEY PARA LA PREVENCION, ATENCION INTEGRAL Y CONTROL DE LAS ADICCIONES PARA EL ESTADO DE AGUASCALIENTES | 3 | as first published, then each reform: 8 August 2023 to 23 December 2025 |
| `ley-para-la-proteccion-a-la-vida/` | LEY PARA LA PROTECCION A LA VIDA PARA EL ESTADO DE AGUASCALIENTES | 1 | as first published: 24 September 2024 |
| `ley-para-la-proteccion-de-las-abejas-y-el-desarrollo-apicola/` | LEY PARA LA PROTECCION DE LAS ABEJAS Y EL DESARROLLO APICOLA DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 13 January 2026 |
| `ley-para-la-proteccion-de-las-personas-que-intervienen-en-el/` | LEY PARA LA PROTECCION DE LAS PERSONAS QUE INTERVIENEN EN EL ENJUICIAMIENTO PENAL PARA EL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 15 April 2015 to 14 July 2015 |
| `ley-para-la-proteccion-de-los-derechos-de-las-personas-migra/` | LEY PARA LA PROTECCION DE LOS DERECHOS DE LAS PERSONAS MIGRANTES DEL ESTADO DE AGUASCALIENTES | 3 | as first published, then each reform: 7 November 2023 to 24 June 2026 |
| `ley-para-la-proteccion-de-personas-defensoras-de-derechos-hu/` | LEY PARA LA PROTECCION DE PERSONAS DEFENSORAS DE DERECHOS HUMANOS Y PERIODISTAS DEL ESTADO DE AGUASCALIENTES | 3 | as first published, then each reform: 1 January 2024 to 13 October 2026 |
| `ley-para-la-proteccion-especial-de-las-personas-adultas-mayo/` | LEY PARA LA PROTECCION ESPECIAL DE LAS PERSONAS ADULTAS MAYORES DEL ESTADO DE AGUASCALIENTES -- ANTES LEY PARA LA PROTECCION ESPECIAL DE LOS ADULTOS MAYORES DEL ESTADO DE AGUASCALIENTES -- | 27 | as first published, then each reform: 14 July 2009 to 24 June 2026 |
| `ley-para-prevenir-y-erradicar-la-discriminacion/` | LEY PARA PREVENIR Y ERRADICAR LA DISCRIMINACION DEL ESTADO DE AGUASCALIENTES | 11 | as first published, then each reform: 24 April 2012 to 30 April 2025 |
| `ley-para-prevenir-y-erradicar-la-trata-de-personas-en-el-est/` | LEY PARA PREVENIR Y ERRADICAR LA TRATA DE PERSONAS EN EL ESTADO DE AGUASCALIENTES | 6 | as first published, then each reform: 31 January 2017 to 24 June 2026 |
| `ley-para-prevenir-y-sancionar-la-tortura-en-el-estado-de-agu/` | LEY PARA PREVENIR Y SANCIONAR LA TORTURA EN EL ESTADO DE AGUASCALIENTES | 5 | as first published, then each reform: 15 May 1995 to 7 June 2016 |
| `ley-para-prevenir-atender-y-erradicar-la-violencia-escolar-e/` | LEY PARA PREVENIR, ATENDER Y ERRADICAR LA VIOLENCIA ESCOLAR EN EL ESTADO DE AGUASCALIENTES | 9 | as first published, then each reform: 18 February 2014 to 21 April 2026 |
| `ley-por-la-que-se-crea-la-universidad-de-la-policia-y-cienci/` | LEY POR LA QUE SE CREA LA UNIVERSIDAD DE LA POLICIA Y CIENCIAS DE LA SEGURIDAD DE AGUASCALIENTES | 6 | as first published, then each reform: 4 February 2023 to 24 June 2026 |
| `ley-que-crea-el-colegio-de-bachilleres/` | LEY QUE CREA EL COLEGIO DE BACHILLERES DEL ESTADO DE AGUASCALIENTES | 1 | as first published: 26 June 1985 |
| `ley-que-crea-el-colegio-de-educacion-profesional-tecnica/` | LEY QUE CREA EL COLEGIO DE EDUCACION PROFESIONAL TECNICA DEL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 31 May 1999 to 24 March 2015 |
| `ley-que-crea-el-instituto-aguascalentense-de-las-mujeres-agu/` | LEY QUE CREA EL INSTITUTO AGUASCALENTENSE DE LAS MUJERES, AGUASCALIENTES | 9 | as first published, then each reform: 20 November 2001 to 24 January 2023 |
| `ley-que-crea-el-instituto-de-infraestructura-fisica-educativ/` | LEY QUE CREA EL INSTITUTO DE INFRAESTRUCTURA FISICA EDUCATIVA DEL ESTADO DE AGUASCALIENTES | 2 | as first published, then each reform: 23 October 2015 to 28 November 2017 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
