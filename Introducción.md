# Data_Analysis_Final_Proyect
Final proyect for Google Data Analyst Certificate demonstrating Excel, SQL, R and Tableu using data from CECyTEJ

Optimización de Nómina.

El Colegio de Estudios Científicos y Tecnológicos del Estado de Jalisco (CECYTEJ) es un subsistema de educación pública a nivel bachillerato que opera con fondos federales y estatales y atiende a más de 20,000 alumnos en sus 44 planteles, distribuidos en el estado de Jalisco.
Además de las clases curriculares como matemáticas, química o programación, el CECYTEJ también asigna a sus más de 800 docentes actividades extracurriculares como asesorías, mantenimiento a sus laboratorios o participaciones en competencias académicas y deportivas. 
Algunas de esas actividades extracurriculares tienen poco impacto en la educación de los alumnos y le cuesta al gobierno mantenerlas (por ejemplo, que un docente esté a cargo de cuidar un huerto o verificar que los extintores estén llenos). El objetivo principal de este proyecto es detectar en qué planteles y en cuáles actividades se están asignando recursos económicos para actividades de poco impacto, con el objetivo optimizar el gasto de la nómina. Adicionalmente, este proyecto es el trabajo final de mi diplomado de Análisis de Datos de Google.

Aspectos específicos para comprender el análisis y resultados del proyecto.

a)	Existen 4 tipos de horas que el gobierno le paga a los docentes del CECYTEJ. Base: número de horas que el docente tiene aseguradas con base a su nombramiento; no se pueden quitar y se deben asignar, preferentemente, para actividades curriculares. Fortalecimiento: número de horas con base a la antigüedad del docente, tampoco se pueden reducir. Temporales: horas adicionales que se pagan extra y varían por semestre; sí se pueden modificar y con esto reducir el gasto de la nómina (éstas serán en las que nos enfocaremos durante el proyecto). Económicas: nombre que se les da a las horas que no se pagan, pero que se acumulan al final del semestre y se convierten en días adicionales de vacaciones; se pueden modificar, pero no tendrá un impacto en la nómina. 
b)	El equipo de asignación de cargas académicas elaboró un Excel (“Relación proyectos Ago24”) con las actividades extracurriculares de todos los docentes. Para poder hacer análisis estadísticos, se agruparon todas las actividades en 10 categorías: Formación Integral, Asesorías Académicas, Cultural, Formación Dual, Deportivo, Investigación, Apoyo al plantel, Tecnológico, Tutoría Docente y Servicios Comunitarios. 
