# Datos Grado Seguridad Pública y Privada

Conjuntos de datos en csv para la materia de estadística en el grado de seguridad pública y privada-

## BD1. Crímenes en Berlin (Berlin_crimes.csv)

Berlín es una ciudad multicultural y con una imagen del crimen muy especial. Por ejemplo, no hay sangrientas guerras de drogas, guetos o vecindarios donde la policía teme llegar. En este banco de datos se recoge la información de delitos cometidos en el periodo de 2012 a 2016 en cada uno de los barrios de la ciudad. La información recogida es:

01) Year: Año de registro
02) District: Distrito
03) Code: Código del barrio
04) Location: Nombre del barrio
05) Robbery: Robos menores
06) Street_robbery: Hurtos callejeros
07) Injury: Lesiones
08) Agg_assault: Asaltos
09) Threat: Amenazas
10) Theft: Hurtos
11) Car: Robos de coches
12) From_car: Robos dentro de los coches
13) Bike: Robos de bicicletas
14) Burglary: Otros robos
15) Fire: Incendios
16) Arson: Incendios provocados
17) Damage: Danños
18) Graffiti: Grafitis
19) Drugs: Drogas
20) Local: Otros delitos menores

El tipo de preguntas que se plantea la comunidad son: ¿Qué parte de Berlín es más peligrosa? ¿Qué crímenes están creciendo? ¿Qué crímenes están bajando?


## BD2. Crímenes en Irlanda (Ireland_Garda_Crimes.csv)

Este conjunto de datos contiene información completa de todos los tipos de delitos cometidos en Irlanda desde el año 2003 hasta 2019. Los datos son proporcionados por la policia Irlandesa de froma trimestral. Los delitos vienen codificados según el código penal irlandés. Los delitos sonsiderados son:

01) Homicide offences (Homicidios),
02) Sexual offences (Delitos sexuales),
03) Attempts/threats to murder, assaults, harassments and related offences (
Intentos / amenazas de asesinato, asaltos, hostigamientos y delitos relacionados),
04) Dangerous or negligent acts (Actos peligrosos o negligentes),
05) Kidnapping and related offences (Secuestro),
06) Robbery/extortion and hijacking offences (Extorsión),
07) Burglary and related offences (Robo),
08) Theft and related offences (Hurtos),
09) Fraud/ deception and related offences (Fraude),
10) Controlled Drug offences (Drogas),
11) Weapons and Explosives offences (Armas y explosivos),
12) Damage to Property and to the Environment (Daños contra la propiedad o el medio ambiente),
13) Public order and other social code offences (Orden público y otras infracciones del código social),
15) Offences against government/ justice procedures and organisation of crime (Delitos contra los procedimientos del gobierno / justicia y la organización del delito).

Los datos recogidos son:

01) REGION: Región de Irlanda,
02) GARDA_DIVISION: División de la policia irlandesa,
03) OFFENCE_CODE: Código del delito,
04) OFFENCE: Delito,
05) TYPE_OF_OFFENCE: Tipo de delito,
06) PERIOD: Periodo de registro obtenido como año-trimestre,
07) TOTAL: número de delitos registrados. 


## BD3. Crímenes locales 2012 (LocalCrime2012.csv)

El conjunto de datos se extrajo del sitio web del FBI-UCR y contiene los delitos registrados para todas las poblaciones de menos de 250.000 habitantes para el año 2012. La lista de variables consideradas son:

01) Population: Población total, 
02) Violentcrimetotal: Delitos violentos, 
03) MurderandManslaughter: Homicidio y homicidio involuntario, 
04) Forciblerape: Violación forzada, 
05) Robbery: Robo, 
06) Aggravatedassault: Asalto con agravantes, 
07) Propertycrimetotal: Delitos contra la propiedad, 
08) Burglary: ,
09) Larcenytheft, 
10) Motorvehic_theft: Robo de vehículos, 
11) lat: Latitud, 
12) long: Longitud

## BD4. Asesinatos cometidos por policias en EEUU (PoliceKillingsUS.csv)

El asesinato en 2014 de Michael Brown en Ferguson, Missouri, comenzó el movimiento de protesta que culminó con "Black Lives Matte"r y un mayor interés en la responsabilidad policial en este tipo de situaciones en todo el país.

Desde el 1 de enero de 2015, The Washington Post ha estado compilando una base de datos de cada tiroteo mortal en los Estados Unidos por un oficial de policía en el cumplimiento de su deber. Es difícil encontrar datos confiables de antes de este período, ya que los incidentes policiales no se han documentado exhaustivamente y las estadísticas sobre brutalidad policial no están disponibles. El Washington Post almacena más de una docena de detalles sobre cada asesinato, incluida la raza, edad y sexo del fallecido, si la persona estaba armada y si la víctima estaba experimentando una crisis de salud mental. Han reunido esta información de los sitios web de las fuerzas del orden, nuevos informes locales, redes sociales y mediante el monitoreo de bases de datos independientes como "Asesinado por la policía" y "Encuentros fatales". El Post también ha realizado informes adicionales en muchos casos.

Las variables consideadas son:

01) id = identificador del incidente,
02) name = nombre del fallecido,
02) date = fecha del incidente,
03) manner_death = tipo de fallecimiento,
04) armed = arma que portaba el fallecido
05) age = edad del fallecido,
06) gender = sexo del fallecido (M = Hombres, F = Mujeres),
07) race = raza del fallecido (A = Asiático, W = Blanco, H = Hispano, B = Negro, O = Oceanía),
08) city = ciudad del incidente,
09) state = estado del incidente,
10) signs_of_mental_illness = Signos de enfermedad mental (TRUE o FALSE),
11) threat_level = nivel de amenaza del fallecido,
12) flee = método de huida del fallecido,
13) body_camera = camara de policia (TRUE o FALSE)

## BD5. Estadísticas asesinatos, población y crímenes (deaths_and_stats.csv)

Este conjunto de datos reúne datos relacionados con la violencia policial en los Estados Unidos. En esta caso, se centra en las muertes de ciudadanos y policías. Las variables recogidas son:

01) State = Estado,
02) City = Ciudad,
03) PD = Departamento de policia,
04) Black_Killed = Negros asesinados,
05) Hispanic_Killed = Hispanos asesinados,
06) Native_American_Killed = Nativos americanos asesinados,
07) Asian_Killed = Asiáticos asesinados,
08) Pacific_Islanders_Killed = Indigenas del pacifíco asesinados,
09) White_People_Killed = Blancos asesinados,
10) Unknown_Race_Killed = Raza desconocida,
11) Total = Población de la ciudad en el momento de recogida de datos,
12) Black = Total de negros,
13) White = Total de blancos,
14) Amer_Indian = Total de indios americanos,
15) Asian = Total de asiáticos,
16) Hawaiian = Total de hawaianos,
17) Other = Total de otros,
18) Two_or_more_races = dos o mas razas en la ciudad,
19) Hispanic = Hispanos,
20) Black_White_Dissimilarity_Index = índice de disimilaridad entre blancos y negros,
21) Murder_nonnegligent_manslaughter = Asesinatos u homicios involuntarios,
22) Violent_crimes_2013 = Víctimas de crímenes violentos en 2013,
23) Violent_crimes_2014 = Víctimas de crímenes violentos en 2014,
24) Violent_crimes_2015 = Víctimas de crímenes violentos en 2015,
25) Violent_crimes_2016 = Víctimas de crímenes violentos en 2016,
26) Violent_crimes_2017 = Víctimas de crímenes violentos en 2017,
27) Violent_crimes_2018 = Víctimas de crímenes violentos en 2018,
28) TotalArrests_2013 = Arrestos totales en 2013,
29) TotalArrests_2014 = Arrestos totales en 2014,
30) TotalArrests_2015 = Arrestos totales en 2015,
31) TotalArrests_2016 = Arrestos totales en 2016,
32) TotalArrests_2017 = Arrestos totales en 2017,
33) TotalArrests_2018 = Arrestos totales en 2018


## BD6. Base datos FBI (2010 a 2019) (FBI.csv)

The "Murder Accountability Project" es la base de datos más completa de homicidios en los Estados Unidos actualmente disponible. Este conjunto de datos incluye asesinatos del Informe Suplementario de Homicidios del FBI desde 1976 hasta el presente y datos de la Ley de Libertad de Información sobre más de 22,000 homicidios que no fueron reportados al Departamento de Justicia. En este caso considermos unicamente los datos desde 2010. Las varaibles registradas son:

Record ID;Agency Code;Agency.Name;Agency.Type;City;State;Year;Month;Incident;Crime.Type;Crime.Solved;Victim.Sex;Victim.Age;Victim.Race;Victim.Ethnicity;Perpetrator.Sex;Perpetrator.Age;Perpetrator.Race;Perpetrator.Ethnicity;Relationship;Weapon;Victim.Count;Perpetrator.Count;Record.Source



Este conjunto de datos incluye la edad, la raza, el sexo, el origen étnico de las víctimas y los autores, además de la relación entre la víctima y el autor y el arma utilizada.



