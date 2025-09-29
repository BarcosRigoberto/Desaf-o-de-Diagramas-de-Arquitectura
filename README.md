# Diagramas de SeñApp
Estos diagramas representan algunas estructuras importantes de la web app de aprendizaje de lenguaje de Señas Argentino SeñApp
## [Diagrama de Componentes](https://github.com/BarcosRigoberto/Desaf-o-de-Diagramas-de-Arquitectura/blob/main/Diagramas/Diagrama%20de%20Componentes.png)
Este diagrama representa la interaccion de los servicios principales de SeñApp y sus interacciones, util para entender que partes del sistema son importantes para el funcionamiento correcto de la web app.
- Frontend contiene la interfaz de los niveles y la autenticacion de usuario
- Backend contiene la gestion de los servicios tales como la gestion de usuarios, de niveles y lecciones y de evaluacion (Puntajes)
- La base de datos es de donde se extraen las lecciones y usuarios registrados
## [Diagrama de Flujo](https://github.com/BarcosRigoberto/Desaf-o-de-Diagramas-de-Arquitectura/blob/main/Diagramas/Diagrama%20de%20Flujo.png)
Este diagrama representa el funcionamiento de las lecciones de SeñApp incluyendo la logica de la cantidad de lecciones por nivel y la suma de puntos, esencial como guia para entender que sucede cada vez que un usuario entra a un nivel.
- Contiene entradas de datos
- Muestra las consignas para mayor claridad
- Verifica si las respuestas son correctas y premia al usuario o le indica los errores
- Un nivel tiene cierta cantidad de lecciones una vez terminan se cierra el nivel, muestra los resultados finales y permite continuar con el siguiente.
### Integrantes
Gustavo Ariel Barcos (https://github.com/BarcosRigoberto)
Emilio Appella (https://github.com/Emilito2007)
Agustin Ardenghi
